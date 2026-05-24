# Scenario
You are testing the login functionality of a web application. The login page contains:
- Username field
- Password field  
- Login button
- An error message displayed for invalid login attempts
- A "Remember Me" checkbox
- A "Forgot Password" link

# Task
Write 5-10 test cases for the login functionality, covering both positive and negative scenarios.

Use the following template for each test case:

## Test Case Template
- **Test Case ID:** A unique identifier for the test case
- **Title:** A brief description of the test case
- **Pre-conditions:** Any setup required before running the test
- **Test Steps:** Step-by-step instructions to execute the test
- **Expected Result:** The expected outcome for the test
- **Actual Result:** Leave this blank (to be filled during actual execution)
- **Priority:** Assign a priority (High/Medium/Low)
- **Remarks:** Any additional comments

# Solution
TODO: Your solution goes below
### Test Case 1 

- **Test Case ID:** test-case-1
- **Title: Verify login with valid credentials
- **Pre-conditions: User account should be registered and active 
- **Test Steps:
  - 1. Open the login page
  - 2. Enter Valid user name
  - 3. Enter Valid password
  - 4. Click on login button

- **Expected Result:User Should successfully login and navigate to home/dashboard page
- **Actual Result: User has log in successfully
- **Priority: High
- **Remarks: Positive test sceanario

### Test Case 2 

- **Test Case ID:** test-case-2
- **Title: Verify login with Invalid password
- **Pre-conditions: Valid user account should exist
- **Test Steps:
  - 1. Open the login page
  - 2. Enter Valid user name
  - 3. Enter Invalid password
  - 4. Click on login button

- **Expected Result:Error message should be displayed for Invalid credentials
- **Actual Result: User has failed to log in.
- **Priority: High
- **Remarks: Negative test sceanario

### Test Case 3

- **Test Case ID:** test-case-3
- **Title: Verify login with Invalid Username
- **Pre-conditions: Login page should be accessible
- **Test Steps:
  - 1. Open the login page
  - 2. Enter Invalid user name
  - 3. Enter valid password
  - 4. Click on login button

- **Expected Result:User should not login and error message should appear
- **Actual Result: User has failed to log in.
- **Priority: High
- **Remarks: Negative test sceanario

### Test Case 4

- **Test Case ID:** test-case-4
- **Title: Verify login with empty Username and password
- **Pre-conditions: Login page should be accessible
- **Test Steps:
  - 1. Open the login page
  - 2. Leave user name field empty
  - 3. Leave password field empty
  - 4. Click on login button

- **Expected Result: validation message should appear for mandatory fields
- **Actual Result: User has failed to log in.
- **Priority: High
- **Remarks: Field validation test sceanario

### Test Case 5

- **Test Case ID:** test-case-5
- **Title: Verify login with empty password field
- **Pre-conditions: Login page should be accessible
- **Test Steps:
  - 1. Open the login page
  - 2. Enter valid user name
  - 3. Leave password field empty
  - 4. Click on login button

- **Expected Result: validation message should appear for password field
- **Actual Result: User has failed to log in.
- **Priority: Medium
- **Remarks: Negative test sceanario

### Test Case 6

- **Test Case ID:** test-case-6
- **Title: Verify "Rememeber me " checkbox functionality
- **Pre-conditions:valid user credentials should be available
- **Test Steps:
  - 1. Open the login page
  - 2. Enter valid user name and password
  - 3. Select "Rememeber Me" checkbox
  - 4. Click on login button
  - 5. Logout and reopen application

- **Expected Result: User credentials/session should be remembered as per functionality
- **Actual Result: User has failed to log in.
- **Priority: Medium
- **Remarks: Functional test sceanario
-->
