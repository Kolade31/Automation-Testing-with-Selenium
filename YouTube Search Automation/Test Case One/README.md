# Test Case: Valid Search Test
## Test Case ID
TC-YS-001
## Description
This test case verifies that a user can successfully perform a search on YouTube and that the search results are relevant to the query. The goal is to ensure that the search functionality works as intended.
## Preconditions
- The testing environment is set up with necessary dependencies.
- The web browser is installed and configured to run the automation script.
## Input
Search Query: "Automation using Selenium on Python" 
## Steps
- Open the Browser:
1. Launch the web browser using Selenium WebDriver.
- Navigate to YouTube:
1. Use the WebDriver to open the URL:[Youtube](https://www.youtube.com).
- Locate the Search Bar:
1. Wait for the search bar element to be present on the page.
- Enter Search Query:
1. Input the search query into the search bar.
- Submit the Search:
1. Locate and click the search button to perform the search.
- Wait for Search Results:
1. Wait for the search results page to load completely.
- Verify Search Results:
1. Check that the search results are displayed.
2. Assert that the results contain relevant content related to the search query.
- Check for No Results:
1. If no results are found, assert that a message indicating no results is displayed.
- Close the Browser:
1. Close the browser window after the test execution.
## Expected Outcome
- The user should be able to navigate to YouTube and enter a search query successfully.
- The search results should be displayed with relevant titles or descriptions related to the query.
- If the search yields no results, an appropriate message should be shown.
## Postconditions
The browser session should be closed, and no residual data should remain.
## Notes
- Ensure that the search query used is relevant and likely to yield results.
- The test should be run in a clean environment to ensure no previous sessions interfere with the results.
- Consider any potential network issues that may affect loading times.
## Actual Results
The user was able to navigate to Youtube and entered a search query successfully. Also, the search result was related to the query.
## Status
PASS
