# My Account Test Cases

Module: My Account  
Application: The Premium Basket  
Tested By: Sakshi Vaity  


| TS_02 | Verify registered user can login with valid credentials | User should login successfully | Functional | High |
| TS_03 | Verify error message for invalid login credentials | Proper error message should display | Negative | High |
| TS_04 | Verify validation messages for empty login fields | Required field validation should appear | Validation | High |
| TS_05 | Verify user can create account with valid details | New account should be created successfully | Functional | High |
| TS_06 | Verify validation for mandatory registration fields | Validation messages should display | Validation | High |
| TS_07 | Verify First Name and Last Name field doesn't accept any special characters and numbers | Error message should display | Validation | Medium |
| TS_08 | Verify email field accepts valid email format only | Invalid email formats should not be accepted and error message should be displayed | Validation | Medium |
| TS_09 | Verify password field is masked | Password should not be visible | UI | Medium |
| TS_10 | Verify SHOW password and HIDE fucntionality | SHOW Password should make the password visible and HIDE password invisible | UI | Medium |
| TS_11 | Recover Password button should lead to lost password page | Recover Password button leads to lost password page | Functional | High |
| TS_12 | Verify Recover Password functionality | Password reset email should be received and success message should be displayed | Functional | High |
| TS_13 | Verify Remember Me functionality | User session should be remembered after browser restart | Functional | Medium |
| TS_14 | Verify browser back button behavior after logout | User should not access account page after logout | Security | Medium |
| TS_15 | Verify account creation with already registered email | Proper duplicate account error should display | Negative | Medium |
| TS_16 | Verify user cannot login with unregistered email | Login should fail with proper error message | Negative | High |
| TS_17 | Verify page responsiveness on mobile devices | Page layout should adjust properly message | Negative | High |
| TS_18 | Verify page loads without UI alignment issues | UI elements should display correctly | UI | Low |
| TS_19 | Verify page performance during loading | Page should load within acceptable time | Performance | Low |



# My Account Test Cases

**Module:** My Account  
**Website:** The Premium Basket  
**Module URL:** https://thepremiumbasket.com/my-account/  
**Tested By:** Sakshi Vaity  

---

## 🔹 TS_02 – Verify Login Functionality

| TEST SCENARIO ID | TEST SCENARIO | TEST CASE ID | TEST CASE DESCRIPTION |
|---|---|---|---|
| TS_02 | Verify Login Functionality | TC_002 | Verify login with valid credentials |
| TS_02 | Verify Login Functionality | TC_003 | Verify login with invalid password |
| TS_02 | Verify Login Functionality | TC_004 | Verify validation for empty login fields |
| TS_02 | Verify Login Functionality | TC_005 | Verify login with unregistered email |
| TS_02 | Verify Login Functionality | TC_006 | Verify Remember Me functionality |

---

## 🔹 TS_03 – Verify Registration Functionality

| TEST SCENARIO ID | TEST SCENARIO | TEST CASE ID | TEST CASE DESCRIPTION |
|---|---|---|---|
| TS_03 | Verify Registration Functionality | TC_007 | Verify user registration with valid details |
| TS_03 | Verify Registration Functionality | TC_008 | Verify validation for mandatory registration fields |
| TS_03 | Verify Registration Functionality | TC_009 | Verify registration with already registered email |
| TS_03 | Verify Registration Functionality | TC_010 | Verify First Name and Last Name field validation |
| TS_03 | Verify Registration Functionality | TC_011 | Verify email field validation |

---

## 🔹 TS_04 – Verify Password & Recovery Functionality

| TEST SCENARIO ID | TEST SCENARIO | TEST CASE ID | TEST CASE DESCRIPTION |
|---|---|---|---|
| TS_04 | Verify Password & Recovery Functionality | TC_012 | Verify password masking functionality |
| TS_04 | Verify Password & Recovery Functionality | TC_013 | Verify SHOW and HIDE password functionality |
| TS_04 | Verify Password & Recovery Functionality | TC_014 | Verify Recover Password navigation |
| TS_04 | Verify Password & Recovery Functionality | TC_015 | Verify Recover Password functionality |

---

## 🔹 TS_05 – Verify Security Behavior

| TEST SCENARIO ID | TEST SCENARIO | TEST CASE ID | TEST CASE DESCRIPTION |
|---|---|---|---|
| TS_05 | Verify Security Behavior | TC_016 | Verify browser back button behavior after logout |

---

## 🔹 TS_06 – Verify UI & Responsiveness

| TEST SCENARIO ID | TEST SCENARIO | TEST CASE ID | TEST CASE DESCRIPTION |
|---|---|---|---|
| TS_06 | Verify UI & Responsiveness | TC_017 | Verify My Account page responsiveness |
| TS_06 | Verify UI & Responsiveness | TC_018 | Verify UI alignment on My Account page |

---

## 🔹 TS_07 – Verify Performance

| TEST SCENARIO ID | TEST SCENARIO | TEST CASE ID | TEST CASE DESCRIPTION |
|---|---|---|---|
| TS_07 | Verify Performance | TC_019 | Verify My Account page loading performance |
