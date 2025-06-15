## Test Case Two
Empty URL Test
## Test Case ID
TC-002
## Description
This test case verifies the behavior of the performance testing script when an empty URL is provided as input. The goal is to ensure that the script handles this scenario gracefully and provides an appropriate error message.
## Preconditions
- The performance testing script is set up and ready to run.
- The script should be able to accept and validate URL inputs.
## Input
URL: "" (empty string)
## Steps
- Start the performance testing script.
- Input the empty URL ("") into the script.
- Execute the test.
- Observe the script's response to the empty URL input.
## Expected Outcome
- The script should not attempt to load any page.
- An error message should be displayed indicating that the URL is required, such as:
## Postconditions
- The script exits without attempting to load a webpage.
- No performance metrics are recorded or logged since the test cannot proceed with an empty URL.
## Notes
- This test ensures that the script performs input validation correctly.
- Ensure that the error message is clear and informative for the user.
## Actual Results
The script did not attempt to load any page and an error message displayed indicating that the URL is required
## Status
PASS
