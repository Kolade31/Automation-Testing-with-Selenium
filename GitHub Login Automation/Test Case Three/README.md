# Test Case: Session Persistence Test
## Test Case ID
TC-003
## Description
This test case verifies that a user remains logged into their GitHub account after closing and reopening the browser. The goal is to ensure that the session is properly persisted and that the user does not need to log in again immediately after a browser restart.
## Preconditions
- The user has a valid GitHub account.
- The user is successfully logged into GitHub.
- The testing environment is set up with necessary dependencies (e.g., Selenium WebDriver).
## Input
- Username: valid_username
- Password: valid_password 
## Steps
- Open the Browser:
1. Launch the web browser using Selenium WebDriver.
- Navigate to GitHub Login Page:
1. Use the WebDriver to open the URL: [GitHub](https://github.com/login).
- Enter Username:
1. Locate the username input field and enter the valid username.
- Enter Password:
1. Locate the password input field and enter the valid password.
- Click Login Button:
1. Locate and click the login button to submit the login form.
- Verify Successful Login:
1. Check for a specific element that indicates a successful login.
2. Assert that the element is visible or contains the expected username.
- Close the Browser:
1. Close the browser window.
- Reopen the Browser:
1. Launch the browser again without logging in.
- Navigate to GitHub Homepage:
1. Use the WebDriver to open the GitHub homepage: [GitHub](https://github.com/login).
- Verify Session Persistence:
1. Check for the presence of the user profile icon or username on the homepage.
2. Assert that the user is still logged in and does not need to re-enter credentials.
## Expected Outcome
- The user should be successfully logged into GitHub initially.
- After closing and reopening the browser, the user should still be logged in, with their profile icon or username visible on the homepage.
- No login prompt should appear, indicating session persistence.
## Postconditions
- The user remains logged in for further actions or tests.
- The session should be properly closed after the test to prevent data leakage.
## Notes
- Ensure that the credentials used are valid and belong to an existing GitHub account.
- The test should be run in a clean environment to ensure no previous sessions interfere with the results.
- Consider any browser settings that may affect session persistence, such as incognito mode or clearing cookies on exit.
## Actual Results

Status
FAIL
