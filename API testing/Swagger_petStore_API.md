#API testiranje_Swagger PetStore

This document contains examples of basic HTTPS requests for Swagger Pet Stor created using Postman.The link to the Postman collection is [here](https://www.postman.com/payload-physicist-42439854/workspace/qa-portfolio/collection/26864893-b0f26524-8266-4d9d-8809-f6bc44255d8a?action=share&creator=26864893)
and the main parts of the requests are written below.

## 1.POST Add a new pet with valid input

**url request and method**

POST {{baseUrl}}/pet

**Authorization :** API Key

**Body**

  {
    "id": *{{petID}}*,
    
    "category": {
    
      "id": 100,
      
      "name": "string"
      
    },
    
    "name": "doggie",
    
    "photoUrls": \[
    
      "string"
      
    \],
    
    "tags": \[
    
      {
      
        "id": 100,
        
        "name": "string"
        
     }
     
    \],
    
    "status": "available"
    
  }

**Scripts**

**Pre-request**

pm.variables.**set**("petID", Math.floor(Math.random() \* 1000));

**Post-request**

pm.test("Status code is 200", **function** () {

    pm.response.to.have.status(200);

});

pm.test("Response time is less than 300ms", **function** () {

    pm.expect(pm.response.responseTime).to.be.below(300);

});

pm.test("Content-Type is present", **function** () {

    pm.response.to.have.header("Content-Type");

});

pm.collectionVariables.**get**("petID");



## 2.GET Verify add a new pet

**url request and method**

GET {{baseUrl}}/pet/25


﻿**Authorization**: API Key
 

**Scripts**

**Pre-request**

/

**Post-request**

pm.test("Status code is 200", **function** () {

    pm.response.to.have.status(200);

});


## 3.PUT Update an existing pet


**url request and method**

PUT {{baseUrl}}/pet


**Authorization:** API Key

**Body**

{

  "id": 10,

  "category": {

    "id": 10,

    "name": "string"

  },

  "name": "doggie",

  "photoUrls": \[

    "string"

  \],

  "tags": \[

    {

      "id": 10,

      "name": "string"

    }

  \],

  "status": "available"

}

## 4.DELETE Remove a pet from the store

**url request and method**

DELETE {{baseUrl}}/pet/651

**Authorization:** API Key

**Scripts**

**Post-scripts**

pm.test("Status code is 200", **function** () {

    pm.response.to.have.status(200);

});

pm.test("Verify pet is removed", **function** () {

    **var** responseBody = pm.response.json();

    // Check if the response code is 200

    pm.expect(responseBody.code).to.equal(200);

    // Check if the type is "unknown"

    pm.expect(responseBody.type).to.equal("unknown");

    // Check if the message is "651"

    pm.expect(responseBody.message).to.equal("651");

});

pm.test("Content-Type is present", **function** () {

    pm.response.to.have.header("Content-Type");

});

## 5.DELETE Remove non-existent pet from the store

**url request and method**

DELETE {{baseUrl}}/pet/1


**Authorization:** API Key


**Scripts**

**Post-scripts**

pm.test("Status code is 404", **function** () {

    pm.response.to.have.status(404);

});
