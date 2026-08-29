# Manual Testing – Test Cases

## Project
Login and Registration Module

## Objective
To verify that the Login and Registration functionality works correctly
for valid and invalid user inputs.

## Test Cases

| Test Case ID | Test Scenario | Test Steps | Expected Result | 
|---|---|---|---|
| TC_001 | Valid Login | Enter valid username and password and click Login | User should be logged in successfully |
| TC_002 | Invalid Password | Enter valid username and wrong password | Error message should be displayed |
| TC_003 | Invalid Username | Enter invalid username and valid password | Error message should be displayed |
| TC_004 | Empty Username | Leave username blank and enter password | Username validation message should appear |
| TC_005 | Empty Password | Enter username and leave password blank | Password validation message should appear |
| TC_006 | Both Fields Empty | Leave username and password blank | Required field messages should appear |
| TC_007 | Password Masking | Enter password in the password field | Password should be masked |
| TC_008 | Registration with Valid Data | Enter all valid registration details | Account should be created successfully |
| TC_009 | Invalid Email | Enter an invalid email format during registration | Email validation message should appear |
| TC_010 | Duplicate Email | Register using an already registered email | Appropriate error message should appear |

## Testing Types Covered

- Functional Testing
- Negative Testing
- Validation Testing
- UI Testing
- Smoke Testing
- Regression Testing

## Tools
- JIRA
- Postman
- SQL
- Selenium WebDriver
