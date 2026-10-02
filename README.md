# Manual Testing Project: Sauce Demo (Swag Labs)

Personal practice project to learn manual testing.
Application tested: https://www.saucedemo.com (public practice e-commerce website)
Browser: Google Chrome | Tool: Microsoft Excel

## What I did
- Wrote 10 test scenarios and 32 test cases (functional, negative, UI, security and performance)
- Executed all test cases manually and recorded the actual results
- Logged 4 defects with steps to reproduce, expected and actual result, severity, priority and screenshots
- Prepared a Requirement Traceability Matrix (RTM) and a test summary report

## Results
| Total test cases | Passed | Failed | Defects logged |
|---|---|---|---|
| 32 | 29 | 3 | 4 |

Modules covered: Login, Products, Cart, Checkout, Logout and Session

## Defects found
| Bug ID | Summary | Severity |
|---|---|---|
| BUG-001 | Login error message text is clipped inside the red error box | Low |
| BUG-002 | problem_user: all products show the same image | Medium |
| BUG-003 | problem_user: checkout form overwrites typed data, order cannot be completed | High |
| BUG-004 | performance_glitch_user: login takes about 6 seconds (limit 3 seconds) | Medium |

## Files
- Manual_Testing_Project_SauceDemo.xlsx: test scenarios, test cases, bug report, RTM and test summary
- Screenshots/: evidence for the defects
