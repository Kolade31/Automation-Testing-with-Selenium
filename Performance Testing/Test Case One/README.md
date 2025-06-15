## Test Case One: 
Valid Load Time Test
## Test Case ID
TC-PT-001
## Description
This test case measures the load time of a valid webpage to ensure that it meets performance criteria.
## Preconditions
- The performance testing script is set up and ready to run.
- The URL to be tested is known to be valid and accessible.
- Internet connection is stable.
## Input
URL: [Zikoko](https://www.zikoko.com) 
## Steps
- Start the performance testing script.
- Input the valid URL into the script.
- Execute the test.
- Record the start time just before the page begins to load.
- Wait until the page fully loads (all resources are downloaded).
- Record the end time once the page has fully loaded.
- Calculate the total load time by subtracting the start time from the end time.
- Log the load time result.
## Expected Outcome
The recorded load time should be: Less than 3 seconds for optimal performance.
## Postconditions
- The load time result is saved in the results log for further analysis.
- The script should handle any errors or exceptions gracefully, providing a meaningful message if the page fails to load.
## Notes
- Ensure that the page is not cached to get an accurate measurement.
- Run the test multiple times (e.g., 3 times) to obtain an average load time for better accuracy.
- Consider using different browsers or network conditions to validate consistency.
## Actual Results
Average recorded load time of 12 seconds
## Status 
FAIL
