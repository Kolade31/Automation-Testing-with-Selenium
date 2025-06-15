## Test Case 
Multiple URL Test
## Test Case ID
TC-003
## Description
This test case measures the load times of multiple valid webpages to ensure that the performance testing script can handle batch processing of URLs and accurately record their load times.
## Preconditions
- The performance testing script is set up and ready to run.
- All URLs to be tested are valid and accessible.
- Internet connection is stable.
## Input
URLs:
- [Zikoko](https://www.zikoko.com)
- [ThisIsAnfield](https://www.thisisanfield.com)
- [Nairaland](https://www.nairaland.com)
## Steps
- Start the performance testing script.
- Input the list of URLs into the script.
- Execute the test.
- Log the load time for each URL in a summary format.
## Expected Outcome
- The script should successfully load each URL without errors.
- Load times for all URLs should be recorded and displayed.
## Postconditions
- All load times are saved in a summary log for analysis.
- The script should handle any failures gracefully, providing error messages for any URLs that fail to load.
## Notes
- Ensure that the URLs are varied in terms of expected load times to test different scenarios.
- Consider running the test multiple times to gather average load times for reliability.
## Actual Results
The script successfully loaded each URL without errors. Also the load times for all URLs was recorded and displayed appropriately.
## Status
PASS
