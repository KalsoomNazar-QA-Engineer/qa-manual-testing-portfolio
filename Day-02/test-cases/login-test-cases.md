# Login Test Cases

| Test Case ID | Test Scenario                                | Test Data                         | Expected Result                               |
| ------------ | -------------------------------------------- | --------------------------------- | --------------------------------------------- |
| TC-01        | Login with valid credentials                 | Valid username & password         | User should be logged in successfully         |
| TC-02        | Login with invalid password                  | Valid username + invalid password | Appropriate error message should be displayed |
| TC-03        | Login with empty fields                      | Username & password empty         | Validation message should be displayed        |
| TC-04        | Login with valid username and empty password | Valid username + empty password   | Password field validation should be displayed |
| TC-05        | Login with empty username and valid password | Empty username + valid password   | Username field validation should be displayed |

## Test Result

All test cases were reviewed based on the expected behavior of the login functionality.
