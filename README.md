## Test Cases Samples
Down below are some test cases samples that I wrote, while I'm working on previous project.

----------------

#### Test Case 1:
Happy Flow Login (pro.imobiliare.ro)

**Test Case ID:**
tcLogin_01

**Test Case Name:**
Verify successful login with valid credentials

**Description:**
This test case verifies that a user can successfully log in to pro.imobiliare.ro using valid credentials.

**Preconditions:**
1. The pro.imobiliare.ro website is accessible.
2. The user has valid login credentials (username and password).

**Test Steps:**
1. Navigate to pro.imobiliare.ro.
2. Locate the login section.
3. Enter the valid username into the email field.
4. Enter the valid password into the password field.
5. Click on the "Intra in cont" button.

**Expected Result:**
1. The user should be successfully logged into their account.
2. The user should be redirected to their dashboard, indicating a successful login.
3. The user's name should be displayed (in to the top, right section) to confirm the successful login.

**Postconditions:**
The user has access to their account and can proceed with further actions on the pro.imobiliare.ro.

**Test Data:**
1. User: Email
2. Password: Password

----------------

#### Test Case 2:
Other Flow Login (pro.imobiliare.ro)

**Test Case ID:**
tcLogin_02

**Test Case Name:**
Verify error message with invalid credentials

**Description:**
This test case verifies that appropriate error messages are displayed when a user attempts to log in to pro.imobiliare.ro with invalid credentials.

**Preconditions:**
1. The pro.imobiliare.ro website is accessible.
2. The user has invalid login credentials (username and/or password).

**Test Steps:**
1. Navigate to pro.imobiliare.ro.
2. Locate the login section.
3. Enter an invalid email into the email field.
4. Enter an invalid password into the password field.
5. Click on the "Intra in cont" button.

**Expected Result:**
1. An error message should be displayed indicating that the login credentials are invalid.
2. The error message should be descriptive, indicating whether the issue is with the username, password, or both.
3. The user should not be logged into the system.
4. The login form should remain accessible for the user to retry.

**Postconditions:**
The user can make corrections to their login credentials and attempt to log in again, or they can choose to reset their password if necessary.

**Test Data:**
1. User: incorrectEmail
2. Password: incorrectPassword

----------------

#### Test Case 3:
Negative Flow - Server Unavailable (pro.imobiliare.ro)

**Test Case ID:**
tcLogin_03

**Test Case Name:**
Verify user response to server unavailability during login

**Description:**
This test case verifies the user's response when the server is unavailable during a login attempt on pro.imobiliare.ro.

**Preconditions:**
The pro.imobiliare.ro website is accessible but the server is intentionally unavailable or experiencing downtime.

**Test Steps:**
1. Navigate to pro.imobiliare.ro.
2. Locate the login section.
3. Enter valid or invalid login credentials into the respective fields.
4. Click on the "Intra in cont" button.

**Expected Result:**
1. The website should display an error message indicating that the server is currently unavailable.
2. The error message should suggest trying again later and apologize for the inconvenience.
3. The user should not be able to proceed with the login process.
4. The user should not be redirected to any other page within the website.

**Postconditions:**
The user can either wait until the server becomes available again and retry the login process, or they can choose to perform other actions outside of logging in until the issue is resolved.

**Test Data:**
1. User: Email
2. Password: Password

----------------