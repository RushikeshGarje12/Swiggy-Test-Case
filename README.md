# Swiggy Mobile App - Manual Testing

Manual test cases and execution results for the **Swiggy food delivery mobile app**, covering login, search, restaurant menu, cart, address, payment and order screens.

## Project Summary
| Item | Details |
|---|---|
| Application | Swiggy mobile app |
| Device / OS / App version | [OPPP F27/ Android 16/4.115.0 (1818)] |
| Test type | Manual: functional, positive, negative, UI |
| Total test cases | 50 |
| Result | 42 Pass, 8 Blocked, 0 Fail |

## Modules Covered
| Module | Test cases | Pass | Blocked |
|---|---:|---:|---:|
| Login | 7 | 7 | 0 |
| Registration | 7 | 3 | 4 |
| Search | 6 | 6 | 0 |
| Restaurant | 6 | 6 | 0 |
| Cart | 6 | 6 | 0 |
| Address | 6 | 6 | 0 |
| Payment | 6 | 5 | 1 |
| Order | 6 | 3 | 3 |
| **Total** | **50** | **42** | **8** |

## Blocked Test Cases
| Test case | Reason |
|---|---|
| TC_008 to TC_011 (first-time sign-up) | Needed a mobile number never used on Swiggy |
| TC_040 (invalid UPI ID) | The app lists installed UPI apps and has no field to type a UPI ID |
| TC_045, TC_046, TC_050 (order confirmation, tracking, cancel) | Needed a real live order; none was placed |

## Notes
- No defects were found in the tested scenarios.
- Several expected results were corrected after checking the real behavior, for example: Swiggy has no separate sign-up form (new users register through the same mobile + OTP login), the Save button stays disabled instead of showing error messages, and the header shows the delivery location instead of the user name.
- Payments and orders were not completed, to avoid real transactions.

## Files
- `Swiggy_Test_Cases.xlsx`: test cases in a standard template (Scenario ID, Test Case ID, Pre Condition, Steps, Expected Result, Actual Result, Status, Priority) with a Summary sheet.

## Tools and Skills
Microsoft Excel, Git, GitHub. Test case design, positive and negative testing, functional testing, UI testing, test documentation.

## Author
**Rushikesh Garje**, QA Analyst (fresher)
[LinkedIn](https://www.linkedin.com/in/rushikesh-garje-450a9239a) | 
