# Test Case: Empty Search Test
## Test Case ID
TC-YS-002
## Description
This test case verifies that when a user performs a search with an empty query on YouTube, the appropriate response is returned. The goal is to ensure that the system handles empty search queries gracefully.
## Preconditions
- The testing environment is set up with necessary dependencies.
- The web browser is installed and configured to run the automation script.
## Input
- Search Query: "" 
## Steps
1. Open the Browser:
- Launch the web browser using Selenium WebDriver.
2. Navigate to YouTube:
- Use the WebDriver to open the URL: [Youtube](https://www.youtube.com).
3. Locate the Search Bar:
- Wait for the search bar element to be present on the page.
4. Submit Empty Search:
- Submit the search without entering any text in the search bar.
5. Wait for Search Results:
- Wait for the search results page to load completely.
6. Verify Search Results:
- Check if a message indicating no results or a prompt to enter a search query is displayed.
- Assert that the results do not contain any video suggestions.
7. Close the Browser:
- Close the browser window after the test execution.
## Expected Outcome
- The user should be able to navigate to YouTube and submit an empty search query.
- An appropriate message should be displayed, indicating that no results were found or prompting the user to enter a search term.
- The results should not show any video suggestions.
## Postconditions
The browser session should be closed, and no residual data should remain.
## Notes
- Ensure that the test is run in a clean environment to ensure no previous sessions interfere with the results.
- Consider any potential network issues that may affect loading times.
## Actual Results
A timeout exception error occured
## Status
FAIL
