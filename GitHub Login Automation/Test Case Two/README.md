## Test Case 
Retrieve Repository from Github After Logging In
## Test Case ID
TC-GL-002
## Description
This test case verifies that a logged-in user can successfully retrieve and display their repositories from GitHub. The goal is to ensure that the application correctly accesses and displays the user's repositories after a successful login.
## Preconditions
- The user has a valid GitHub account with at least one repository.
- The user is successfully logged into GitHub.
- The testing environment is set up with necessary dependencies (e.g., Selenium WebDriver).
## Input
- Username: valid_username
- Password: valid_password 
## Steps
1. Open the Browser:
- Launch the web browser using Selenium WebDriver.
2.Navigate to GitHub Login Page:
- Use the WebDriver to open the URL: [Github](https://github.com/login).
3. Enter Username:
- Locate the username input field using its HTML identifier.
- Use the WebDriver to input the valid username.
4. Enter Password:
- Locate the password input field using its HTML identifier.
- Use the WebDriver to input the valid password.
5. Click Login Button:
- Locate the login button using its HTML identifier.
- Use the WebDriver to click the button to submit the login form.
6. Wait for Navigation:
- Implement a wait to ensure the page loads and navigates to the user’s GitHub homepage.
7. Navigate to Repositories Page:
- Locate the "Repositories" tab or link on the homepage.
- Use the WebDriver to click on the "Repositories" link to navigate to the repositories list.
8. Retrieve Repository List:
- Locate the repository elements on the page.
- Use the WebDriver to extract the names and URLs of the repositories listed.
9. Verify Repository Retrieval:
- Assert that the repository list is displayed correctly.
- Confirm that at least one repository is retrieved and matches the expected details.
## Expected Outcome
- The user should be successfully logged into GitHub.
- The repositories page should display a list of the user's repositories.
- At least one repository should be retrieved successfully with correct details.
## Postconditions
- The user remains logged in for further actions or tests.
- The session should be properly closed after the test to prevent data leakage.
## Notes
- Ensure that the credentials used are valid and belong to an existing GitHub account with repositories.
- The test should be run in a clean environment to ensure no previous sessions interfere with the results.
## Actual Results
User successfully logged in and the list of the user's respositories was retrived.
## Status
PASS
