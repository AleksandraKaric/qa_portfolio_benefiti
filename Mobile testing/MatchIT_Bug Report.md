# MatchIT Bug Report

## MatchIT_Bug report is document that outlines defects identified during testing. For this task, a real phone device is used iPhone 8 (iOS 16.7.8) and emulator Samsung Galaxy S24 (Android 14) from Samsung Remote Test Lab.

### ID: bug_1  

**Summary:** User - “Nivo edukacije” screen  | User cannot add a degree level from the “Nivo edukacije” screen <br />
**Description:** The “Nivo edukacije” screen has no elements to choose from, and the user is disabled to select a degree level. The user can’t choose a degree level nighter from the user's profile settings, which is why this information is not displayed in the Education.

**Environment:**  iPhone 8, iOS 16.7.8

**Precondition:** The user has successfully fulfilled previous steps for registration and it is on “Edukacija” screen <br />
**Steps to reproduce:** 

1. Tap the the field “+ Dodaj edukaciju”
2. Tap the field “Nivo edukacije”

**Expected result:** The user can select a degree level from the dropdown menu. <br />
**Actual result:** No dropdown menu is displayed on the “Nivo edukacije” screen.

**Priority/Severity:** Medium/Medium 

Link to [attachment:](https://drive.google.com/drive/folders/1MAeEN1NqCo8exmpjoIZ1680h68aDA_yi)



### ID: bug_2  

**Summary:** User - Benefiti | Some benefits full-name are not displayed. <br />
**Description:** Some benefits name are not properly displayed as it showen on Android. For example “Privatno zdravstveno osiguranje” and “Privatno zdravstveno osiguranje za članove porodice” cannot be distinguished, “Fleksibilno radno…” etc.

**Environment:** iPhone 8, iOS 16.7.8

**Precondition:** The user donn't have an acoount

**Steps to reproduce:**

1. Open the app
2. With valid data register an email
3. Log in to app
4. With valid data fill all required steps and proced to Benefiti screen
5. Pay attention to the screen elements

**Expected result:** The user can see the full name of benefits and select/change it. <br />
**Actual result:** The name of some benefits are cut off.

**Priority/Severity:** Medium/Medium

Link to [attachment:](https://drive.google.com/drive/folders/1MAeEN1NqCo8exmpjoIZ1680h68aDA_yi)


### ID: bug_3  

**Summary:** Users’ profile | The “Veštine” and “Odjavi me” sections are overlapping. <br />
**Description:** The sections are overlapping and it is possible to tap on both, but only aiming at the very top of the “Veština” section, and the very bottom of the “Odjavi me” section.


**Environment:** emulator Samsung Galaxy S24 (Android 14) - Samsung Remote Test Lab

**Precondition:** User is logged in

**Steps to reproduce:** 

1. Open the app
2. Tap Profil screen


**Expected result:** The “Odjavi me” and “Obriši profil” sections are separate from the top sections at least by the size of one section. <br />
**Actual result:** The “Veštine” and “Odjavi me” sections are overlapping and it is hard to tap on it.

**Priority/Severity:** Medium/Medium

Link to [attachment:](https://drive.google.com/drive/folders/1MAeEN1NqCo8exmpjoIZ1680h68aDA_yi)


