# Login Page - Manual Test Cases

## Project Objective
To verify that the login page works correctly for valid and invalid inputs.

## Test Case 1: Valid Login
- **Test Case ID:** TC_LOGIN_001
- **Scenario:** Login with valid credentials
- **Precondition:** A registered user exists.
- **Steps:**
  1. Open the login page.
  2. Enter a valid username.
  3. Enter a valid password.
  4. Click Login.
- **Expected Result:** The user should log in successfully.

## Test Case 2: Invalid Password
- **Test Case ID:** TC_LOGIN_002
- **Scenario:** Login with an incorrect password
- **Steps:**
  1. Open the login page.
  2. Enter a valid username.
  3. Enter an incorrect password.
  4. Click Login.
- **Expected Result:** Login should be denied and an appropriate error message should appear.

## Test Case 3: Empty Username
- **Test Case ID:** TC_LOGIN_003
- **Scenario:** Submit the login form without a username
- **Steps:**
  1. Open the login page.
  2. Leave the username empty.
  3. Enter a password.
  4. Click Login.
- **Expected Result:** The application should display an appropriate validation message.