# OrangeHRM Manual Testing Project

## Overview
This project involves manual testing of the [OrangeHRM Demo Site](https://opensource-demo.orangehrmlive.com/). It focuses on testing the **Login** functionality and the **Apply Leave** functionality, including the creation of decision table, test scenarios, detailed test cases, and bug reporting.

## Features
- **Project Details**
  - Comprehensive manual testing of login and apply leave functionalities.
- **Decision Table**
  - Logical decision-making scenarios for login and leave application processes.
- **Test Case Documentation**
  - Well-structured and detailed test cases for the functionalities under test.
- **Bug Tracking and Reporting**
  - Identification of issues with proper reproduction steps and severity levels.

## Test Scenarios
The following scenarios are covered in this project:

### Login Module
1. Verify successful login with valid credentials.
2. Verify error messages for invalid credentials.
3. Verify error messages for blank credentials.

### Apply Leave Module
1. Verify applying for leave with valid dates.
2. Verify error messages when applying for leave with invalid or overlapping dates.
3. Verify applying for leave with blank dates.

## Decision Table
The decision table outlines possible conditions and corresponding actions for login and apply leave functionalities. For example:
| Condition                  | Action                   |
|----------------------------|--------------------------|
| Valid login credentials    | Login successfully       |
| Invalid login credentials  | Display error message    |
| Blank login credentials    | Display error message    |
| Valid leave dates          | Allow leave request      |
| Invalid leave dates        | Deny leave request       |
| Blank leave dates          | Deny leave request       |

## Test Scenario Documentation
Test Scenarios are documented in a structured format, including:
- SL No.
- Test Scenario ID
- Test Scenario Description
- Reference
- Total Number of Test Cases

## Test Case Documentation
Test cases are documented in a structured format, including:
- SL No.
- Test Scenario ID
- Test Case ID
- Test Case Description
- Pre-conditions
- Test Steps
- Test Data
- Actual Results
- Expected Results
- Status (Pass/Fail)
- Remarks

## Bug Reporting
Bugs identified during testing are documented with:
- SL No.
- Test Case ID
- Bug ID
- Module
- Summary
- Steps to Reproduce
- Actual Results
- Expected Results
- Severity
- Priority
- Environment
- Attachments

## Tools Used
- **Test Case Management:** Excel/Google Sheets
- **Bug Tracking:** Excel/Google Sheets

## Future Enhancements
- Expand test scenarios to cover additional modules.
- Automate high-priority test cases for faster regression testing.

## Contributing
Contributions to improve test case documentation or expand test coverage are welcome! Please share your feedback or suggestions.

---
Happy Testing! 🎉
