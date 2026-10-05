# SauceDemo Manual Testing Project

A comprehensive manual testing project performed on the SauceDemo e-commerce web application. The project demonstrates the complete software testing workflow, including test planning, test case design, test execution, defect reporting, requirement traceability, and test summary reporting.

---

## Application Under Test

**Application:** SauceDemo

**Application Type:** E-commerce Web Application

**Testing Type:** Manual Testing

**Test Environment:** Windows + Google Chrome

---

## Project Objective

The objective of this project is to perform end-to-end manual testing of an e-commerce application and demonstrate practical knowledge of software testing processes.

The project covers:

* Functional testing
* Positive and negative testing
* Validation testing
* UI testing
* Test case design
* Test execution
* Defect identification
* Defect reporting
* Requirement traceability
* Test summary reporting

---

## Modules Tested

The following application modules were tested:

* Login
* Products / Inventory
* Product Details
* Product Sorting
* Shopping Cart
* Checkout
* Order Completion
* Logout
* Footer / Social Media Links

---

## Test Execution Summary

| Metric           | Result |
| ---------------- | -----: |
| Total Test Cases |     23 |
| Executed         |     23 |
| Passed           |     22 |
| Failed           |      1 |
| Blocked          |      0 |
| Not Executed     |      0 |
| Defects Found    |      1 |
| Pass Percentage  | 95.65% |

---

## Defect Found

### BUG-001 — Product Image Not Displayed in Cart

**Module:** Cart

**Severity:** Medium

**Priority:** Medium

**Status:** New

**Description:**

The selected product's image was not displayed on the Cart page, while other product information such as name, description, price, quantity, and Remove button was displayed correctly.

**Related Test Case:** `TC-CART-004`

---

## Project Structure

```text
SauceDemo-Manual-Testing/
│
├── 01-Requirements/
│   └── Requirements.md
│
├── 02-Test-Plan/
│   └── Test-Plan.md
│
├── 03-Test-Scenarios/
│   └── Test-Scenarios.md
│
├── 04-Test-Cases/
│   └── Test-Cases.md
│
├── 05-Test-Data/
│   └── Test-Data.md
│
├── 06-Test-Execution/
│   └── Test-Execution.md
│
├── 07-Bug-Reports/
│   └── Bug-Reports.md
│
├── 08-RTM/
│   └── RTM.md
│
├── 09-Test-Summary/
│   └── Test-Summary.md
│
├── 10-Screenshots/
│   ├── login/
│   ├── products/
│   ├── cart/
│   ├── checkout/
│   └── bugs/
│
└── README.md
```

---

## Testing Process

The project followed a structured manual testing workflow:

```text
Requirements
     ↓
Test Planning
     ↓
Test Scenarios
     ↓
Test Cases
     ↓
Test Data
     ↓
Test Execution
     ↓
Defect Identification
     ↓
Bug Reporting
     ↓
RTM
     ↓
Test Summary
```

---

## Test Documentation

| Document       | Description                                                    |
| -------------- | -------------------------------------------------------------- |
| Requirements   | Application requirements identified for testing                |
| Test Plan      | Testing scope, objectives, approach, environment, and criteria |
| Test Scenarios | High-level scenarios covering application functionality        |
| Test Cases     | Detailed test cases with steps and expected results            |
| Test Data      | Test credentials and sample checkout data                      |
| Test Execution | Actual test execution results                                  |
| Bug Reports    | Detailed documentation of identified defects                   |
| RTM            | Requirement-to-test-case traceability                          |
| Test Summary   | Final testing results and recommendations                      |

---

## Tools Used

* Manual Testing
* Google Chrome
* Windows
* VS Code
* Markdown
* Git
* GitHub

---

## Key QA Concepts Demonstrated

* SDLC
* STLC
* Functional Testing
* Positive Testing
* Negative Testing
* Test Case Design
* Test Scenario Design
* Defect Reporting
* Severity vs Priority
* Requirement Traceability Matrix
* Test Execution
* Test Summary Reporting
* Retesting
* Regression Testing

---

## Project Author

**Aman Singh**

B.Tech Computer Science and Engineering

Dehradun, Uttarakhand, India

---

## Future Improvements

The project can be extended with:

* API testing using Postman
* SQL/database testing
* Automation testing using Selenium
* Performance testing using JMeter
* Cross-browser testing
* Regression testing after defect fixes
* CI/CD integration

---

## Project Status

**Test Cycle:** Completed

**Overall Result:** PASS WITH DEFECTS

**Open Defects:** 1
