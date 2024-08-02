# This document shows test cases for the basic functionalities of the Company Benefits feature.



## Test Case ID: TC1

Test Priority (Low/Medium/High): **High**

Test Modul: **Company Benefits**

Test Title: **Verify Add new Company Benefits Group with the required
fields.**


Test Designed by: **Aleksandra Karić**

Test Designed date: 12.6.2024.

Test Executed by: **Aleksandra Karić**

Test Executed date: 12.6.2024.

Precondition:

1.  The user is logged in as an HR

<table>
<colgroup>
<col style="width: 5%" />
<col style="width: 25%" />
<col style="width: 35%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>No</th>
<th>Test Steps</th>
<th>Test Data</th>
<th>Expected Result</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1</td>
<td>Click on the <strong>Company Benefits</strong> tab</td>
<td></td>
<td><p>The user is redirected to <strong>Company Benefits</strong>
page</p>
<p> </p></td>
</tr>
<tr class="even">
<td>2</td>
<td>Click on the <em><strong>Add Local Benefit Group</strong></em>
button</td>
<td></td>
<td>The <em><strong>Add Local Benefit Group</strong></em> form is
open</td>
</tr>
<tr class="odd">
<td>3</td>
<td>Fill in the <em><strong>Name</strong></em> field with valid
data</td>
<td>Enter the minimum number of  characters that contain <u>lowercase
and uppercase letters, special characters, and number </u></td>
<td>The entered data is displayed</td>
</tr>
<tr class="even">
<td>4</td>
<td>Click on the <em><strong>Category</strong></em> dropdown menu</td>
<td></td>
<td>The field outline turns blue and the dropdown menu is opened</td>
</tr>
<tr class="odd">
<td>5</td>
<td>Click the category from the dropdown list</td>
<td>Choose the first option from the list.</td>
<td>The dropdown list is closed and the selected category is displayed
in the <em><strong>Category</strong></em> field</td>
</tr>
<tr class="even">
<td>6</td>
<td>Fill in the <em><strong>Summary</strong></em> field with valid
data</td>
<td>Enter the minimum number of  characters (20) that contain
<u>lowercase and uppercase letters, special characters, and
number </u></td>
<td>The entered data is displayed</td>
</tr>
<tr class="odd">
<td>7</td>
<td>In the <em><strong>Picture,</strong></em> field drag and drop an
image with valid dimensions and format.</td>
<td>Choose an image with a landscape orientation, dimension 500x500px,
and JPG, JPEG, or <strong>PNG</strong> format</td>
<td>The image is displayed</td>
</tr>
<tr class="even">
<td>8.</td>
<td>Click the <em><strong>Create</strong></em> button</td>
<td></td>
<td>The <em><strong>Add Local Benefit Group</strong></em> form is
closed, a successful alert message appears and company benefit is
displayed on the list</td>
</tr>
</tbody>
</table>



## Test Case ID: TC2

Test Priority (Low/Medium/High): **High**

Test Modul: **Company Benefits**

Test Title: **Verify Edit Company Benefits Group filling all fields.**


Test Designed by: **Aleksandra Karić**

Test Designed date: 12.6.2024

Test Executed by: **Aleksandra Karić**

Test Executed date: 12.6.2024.

Precondition:

1.  The user is logged in as an HR <br />  
2.  There is a created Benefit Group

<table>
<colgroup>
<col style="width: 5%" />
<col style="width: 26%" />
<col style="width: 36%" />
<col style="width: 32%" />
</colgroup>
<thead>
<tr class="header">
<th>No</th>
<th>Test Steps</th>
<th>Test Data</th>
<th>Expected Result</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1</td>
<td>Click on the <strong>Company Benefits</strong> tab</td>
<td></td>
<td><p>The user is redirected to <strong>Company Benefits</strong>
page</p>
<p> </p></td>
</tr>
<tr class="even">
<td>2</td>
<td>Click on the Edit icon</td>
<td></td>
<td>The <em><strong>Edit Local Benefit Group</strong></em> form is
open</td>
</tr>
<tr class="odd">
<td>3</td>
<td>Fill in the <em><strong>Name</strong></em> field with valid
data</td>
<td>Enter the maximum number of  characters (30) that contain
<u>lowercase and uppercase letters, special characters, and
number </u></td>
<td>The entered data is displayed</td>
</tr>
<tr class="even">
<td>4</td>
<td>Click on the <em><strong>Category</strong></em> dropdown menu</td>
<td></td>
<td>The field outline turns blue and the dropdown menu is opened</td>
</tr>
<tr class="odd">
<td>5</td>
<td>Scroll down and click on the last category from the dropdown
list</td>
<td></td>
<td>The dropdown list is closed and the selected category is displayed
with the previous one in the <em><strong>Category</strong></em>
field.</td>
</tr>
<tr class="even">
<td>6</td>
<td>Fill in the <em><strong>Summary</strong></em> field with valid
data</td>
<td>Enter the maximum number of  characters (90) that contain
<u>lowercase and uppercase letters, special characters, and
number </u></td>
<td>The entered data is displayed</td>
</tr>
<tr class="odd">
<td>7</td>
<td>Fill in the <em><strong>Description</strong></em> field with valid
data.</td>
<td>Enter the maximum number of  characters (1001) that contain
<u>lowercase and uppercase letters, special characters, and
number </u></td>
<td>The entered data is displayed</td>
</tr>
<tr class="even">
<td>8</td>
<td>Click on the Bin icon to remove the previous picture from the
<em><strong>Picture</strong></em> field</td>
<td></td>
<td>The <em><strong>Picture</strong></em> field is empty and contains
only placeholders</td>
</tr>
<tr class="odd">
<td>9</td>
<td>Click the <em><strong>Picture</strong></em> field</td>
<td></td>
<td>The User’s folder is opened</td>
</tr>
<tr class="even">
<td>10</td>
<td>Select an image with a valid characteristic</td>
<td><p>landscape orientation, dimension 1920x1097px,</p>
<p>format  JPG</p></td>
<td>The image is uploaded.</td>
</tr>
<tr class="odd">
<td>11</td>
<td>Click the <em><strong>Update</strong></em> button</td>
<td></td>
<td>The <em><strong>Edit Local Benefit Group</strong></em> form is
closed, a successful alert message appears and the changes are
saved.</td>
</tr>
</tbody>
</table>



## Test Case ID: TC3

Test Priority (Low/Medium/High): **High**

Test Modul: **Company Benefits**

Test Title: **Verify that the user has added local benefits in the
benefits group with the required fields.**


Test Designed by: **Aleksandra Karić**

Test Designed date: 12.6.2024

Test Executed by: **Aleksandra Karić**

Test Executed date: 12.6.2024.

Precondition:

1.  The user is logged in as an HR <br /> 
2.  There is a created Benefit Group

<table>
<colgroup>
<col style="width: 5%" />
<col style="width: 26%" />
<col style="width: 18%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>No</th>
<th>Test Steps</th>
<th>Test Data</th>
<th>Expected Result</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1</td>
<td>Click on the <strong>Company Benefits</strong> tab</td>
<td></td>
<td><p>The user is redirected to <strong>Company Benefits</strong>
page</p>
<p> </p></td>
</tr>
<tr class="even">
<td>2</td>
<td>Click the Benefit Group card</td>
<td></td>
<td>The <em><strong>Benefit Group</strong></em> card expands.</td>
</tr>
<tr class="odd">
<td>3</td>
<td>Click the <em><strong>Add Benefit</strong></em> button</td>
<td></td>
<td>The <em><strong>Add Local Benefit</strong></em> form opens</td>
</tr>
<tr class="even">
<td>4</td>
<td>Fill in the <em><strong>Name</strong></em> field with valid
data</td>
<td></td>
<td>The entered data is displayed</td>
</tr>
<tr class="odd">
<td>5</td>
<td>Click the <em><strong>Expiration type</strong></em> dropdown
menu</td>
<td></td>
<td>The field outline turns blue and the dropdown menu is opened</td>
</tr>
<tr class="even">
<td>6</td>
<td>Click the expiration type from the dropdown list</td>
<td>Choose the first option from the list.</td>
<td>The dropdown list is closed and the selected type is displayed in
the <em><strong>Expiration type</strong></em> field</td>
</tr>
<tr class="odd">
<td>7</td>
<td>Fill in the <em><strong>Benefit price in tokens</strong></em> field
with valid data.</td>
<td>Enter number</td>
<td>The entered data is displayed</td>
</tr>
<tr class="even">
<td>8</td>
<td>Fill in the <em><strong>Summary</strong></em> field with valid
data</td>
<td></td>
<td>The entered data is displayed</td>
</tr>
<tr class="odd">
<td>9</td>
<td>Click the <em><strong>Create</strong></em> button</td>
<td></td>
<td>The <em><strong>Add Local Benefit</strong></em> form is closed, a
successful alert message appears and the benefit is displayed on the
Company Benefit Group list.</td>
</tr>
</tbody>
</table>

<br /> 

## Test Case ID: TC4

Test Priority (Low/Medium/High): **High**

Test Modul: **Company Benefits**

Test Title: **Verify that tokens are returned to the user after deleting
the selected benefit.**


Test Designed by: **Aleksandra Karić**

Test Designed date: 12.6.2024

Test Executed by: **Aleksandra Karić**

Test Executed date: 12.6.2024.

Precondition:

1.  The user is logged in as an HR <br /> 
2.  There is one employee who has a subscription to the Company benefit
    that costs more than 0 tokens

<table>
<colgroup>
<col style="width: 5%" />
<col style="width: 40%" />
<col style="width: 9%" />
<col style="width: 44%" />
</colgroup>
<thead>
<tr class="header">
<th>No</th>
<th>Test Steps</th>
<th>Test Data</th>
<th>Expected Result</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>Click on the <strong>Employees</strong> tab</td>
<td></td>
<td>The user is redirected to the <strong>Employee</strong> page</td>
</tr>
<tr class="even">
<td>1</td>
<td>Click on the employee from the precondition and check the token
status</td>
<td></td>
<td>The list of benefits is displayed</td>
</tr>
<tr class="odd">
<td>2</td>
<td>Click the Company Benefit tab</td>
<td></td>
<td>The user is redirected to the Company benefit page</td>
</tr>
<tr class="even">
<td>3</td>
<td>Click on a specific benefit Group.</td>
<td></td>
<td>The list of benefits within the Group is displayed</td>
</tr>
<tr class="odd">
<td>4</td>
<td>Click the <em><strong>Delete</strong></em> icon/button for
benefit</td>
<td></td>
<td>The <em><strong>pop-up notification</strong></em> appears</td>
</tr>
<tr class="even">
<td>5</td>
<td>Click the <em><strong>OK</strong></em> button on the pop-up
notification</td>
<td></td>
<td>The pop-up notification closes and the benefit is removed from the
list. </td>
</tr>
<tr class="odd">
<td>6</td>
<td>Tap the “<strong>Employee</strong>” tab.</td>
<td></td>
<td>The user is redirected to the  “<strong>Employee</strong>” tab.</td>
</tr>
<tr class="even">
<td>7</td>
<td>Go to the employee from the precondition and check the token
status</td>
<td></td>
<td>The status of the tokens has increased by the value of the deleted
benefit</td>
</tr>
</tbody>
</table>

<br /> 

## Test Case ID: TC5

Test Priority (Low/Medium/High): **Medium**

Test Modul: **Company Benefits**

Test Title: **Verify the user can delete only an empty Benefit Group**

Description: **The User can delete the Benefits Group after deleting all
benefits belongings to this group.**


Test Designed by: **Aleksandra Karić**

Test Designed date: 12.6.2024

Test Executed by: **Aleksandra Karić**

Test Executed date: 12.6.2024.

Precondition:

1\. The user is logged in as an HR <br /> 
2\. There is a created Benefit Group with 1 benefit within.

<table>
<colgroup>
<col style="width: 5%" />
<col style="width: 29%" />
<col style="width: 9%" />
<col style="width: 55%" />
</colgroup>
<thead>
<tr class="header">
<th>No</th>
<th>Test Steps</th>
<th>Test Data</th>
<th>Expected Result</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>Click on the <strong>Company Benefits</strong> tab</td>
<td></td>
<td><p>The user is redirected to <strong>Company Benefits</strong>
page</p>
<p> </p></td>
</tr>
<tr class="even">
<td>1</td>
<td>Click the <em><strong>Delete</strong></em> icon/button for specific
Benefit Group</td>
<td></td>
<td>The <em><strong>alert message</strong></em> appears with the
instruction to delete all benefits from the group before deleting a
group.</td>
</tr>
<tr class="odd">
<td>2</td>
<td>Click the Benefit Group</td>
<td></td>
<td>The <em><strong>Benefit Group</strong></em> card expands.</td>
</tr>
<tr class="even">
<td>3</td>
<td>Click the <em><strong>Delete</strong></em> icon/button for
benefit</td>
<td></td>
<td>The <em><strong>pop-up notification</strong></em> appears</td>
</tr>
<tr class="odd">
<td>4</td>
<td>Click the <em><strong>OK</strong></em> button on the pop-up
notification</td>
<td></td>
<td>The pop-up notification closes and the benefit is removed from the
list. Below the name of the Benefit Group is 0 benefits</td>
</tr>
<tr class="even">
<td>5</td>
<td>Click the <em><strong>Delete</strong></em> icon/button for the
benefit group</td>
<td></td>
<td>The <em><strong>pop-up notification</strong></em> appears</td>
</tr>
<tr class="odd">
<td>6</td>
<td>Click the <em><strong>OK</strong></em> button on the pop-up
notification</td>
<td></td>
<td>The pop-up notification closes and the benefit group is removed from
the list. </td>
</tr>
</tbody>
</table>
