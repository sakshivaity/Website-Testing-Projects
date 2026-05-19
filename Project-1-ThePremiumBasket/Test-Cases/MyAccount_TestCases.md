# My Account Test Cases

Module: My Account  
Application: The Premium Basket  
Tested By: Sakshi Vaity  


| TS ID | Test Scenario | Expected Result | Test Type | Priority |
|---|---|---|---|---|
| TS_01 | Verify My Account page opens successfully | My Account page should load properly | Functional | High |
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


| TEST SCENARIO ID | TEST SCENARIO | TEST CASE ID | TEST CASE DESCRIPTION | STEPS TO REPRODUCE | TEST / INPUT DATA | EXPECTED RESULT | ACTUAL RESULT | PRIORITY | STATUS |
|---|---|---|---|---|---|---|---|---|---|
| TS_01 | Verify My Account page opens successfully | TC_001 | Verify My Account page loads successfully | 1. Open browser <br> 2. Enter My Account page URL <br> 3. Press Enter | https://thepremiumbasket.com/my-account/ | My Account page should load properly without errors | NA | High | Not Executed |
