# Test Case: Invalid Search Test
## Test Case ID
TC-YS-003
## Description
This test case verifies that when a user performs a search with an invalid query on YouTube, the appropriate response is returned. The goal is to ensure that the system handles invalid search queries gracefully and informs the user that no results were found.
## Preconditions
- The testing environment is set up with necessary dependencies (e.g., Selenium WebDriver).
- The web browser is installed and configured to run the automation script.
## Input
Search Query: "asdfghjkl0987654321"
## Steps
1. Open the Browser:
- Launch the web browser using Selenium WebDriver.
2. Navigate to YouTube:
- Use the WebDriver to open the URL: [Youtube](https://www.youtube.com).
3. Locate the Search Bar:
- Wait for the search bar element to be present on the page.
4. Enter Invalid Search Query:
- Input the invalid search query into the search bar.
5. Submit the Search:
- Locate and click the search button to perform the search.
6. Wait for Search Results:
- Wait for the search results page to load completely.
7. Verify No Results Message:
- Check if a message indicating no results were found is displayed.
- Assert that the results do not contain any valid video suggestions.
8. Close the Browser:
- Close the browser window after the test execution.
## Expected Outcome
- The user should be able to navigate to YouTube and submit an invalid search query successfully.
- An appropriate message should be displayed, indicating that no results were found for the given query.
- The results should not show any valid video suggestions.
## Postconditions
The browser session should be closed, and no residual data should remain.
## Notes
- Ensure that the test is run in a clean environment to avoid interference from previous sessions.
- Consider any potential network issues that may affect loading times.
## Actual Results
The user was able to navigate to Youtube and submit an invalid search query successfully, but the appropriate message was not displayed indicating that no results were found for the given query. Although the results sis not show any valid video suggestions
## Status
FAIL
