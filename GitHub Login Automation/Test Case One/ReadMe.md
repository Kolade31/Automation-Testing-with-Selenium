## Test Case 
Valid Login Test
## Test Case ID
TC-GL-001
## Description
This test case verifies that a user can successfully log into GitHub using valid credentials. The goal is to ensure that the login functionality works as expected for legitimate users.
## Preconditions
- The user has a valid GitHub account with an active username and password.
- The GitHub login page is accessible.
- The testing environment is set up with necessary dependencies (e.g., Selenium WebDriver).
## Input
- Username: valid_username
- Password: valid_password 
## Steps
1. Open the Browser:
- Launch the web browser using Selenium WebDriver.
2. Navigate to GitHub Login Page:
- Use the WebDriver to open the URL: [Github](https://github.com/login).
3. Enter Username:
- Locate the username input field using its HTML identifier
- Use the WebDriver to input the valid username.
4. Enter Password:
- Locate the password input field using its HTML identifier.
- Use the WebDriver to input the valid password.
5. Click Login Button:
- Locate the login button using its HTML identifier.
- Use the WebDriver to click the button to submit the login form.
6. Wait for Navigation:
- Implement a wait to ensure the page loads and navigates to the user’s GitHub homepage.
7. Verify Successful Login:
- Check for a specific element that indicates a successful login
- Use assertions to confirm that the element is visible or contains the expected username.
## Expected Outcome
- The user should be successfully logged into GitHub.
- The homepage should display the user’s profile icon or username.
- No error messages should appear during the login process.
## Postconditions
- The user remains logged in for further actions or tests.
- The session should be properly closed after the test to prevent data leakage.
## Notes
- Ensure that the credentials used are valid and belong to an existing GitHub account.
- The test should be run in a clean environment to ensure no previous sessions interfere with the results.
## Actual Results
User was successfully logged in, hompage displayed and no error message appeared during login process.
## Status
PASS
