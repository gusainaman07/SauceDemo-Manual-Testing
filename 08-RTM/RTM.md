# Requirement Traceability Matrix (RTM)

## Purpose

The Requirement Traceability Matrix maps application requirements to their corresponding test cases and execution results. It ensures that each requirement is covered by testing.

---

## RTM

| Requirement ID | Requirement                                                                   | Test Case ID                 | Test Result | Defect ID |
| -------------- | ----------------------------------------------------------------------------- | ---------------------------- | ----------- | --------- |
| RQ-001         | User should be able to log in with valid credentials.                         | TC-LOGIN-001                 | PASS        | N/A       |
| RQ-002         | System should display an error for invalid credentials.                       | TC-LOGIN-002, TC-LOGIN-003   | PASS        | N/A       |
| RQ-003         | Login fields should be validated when required data is missing.               | TC-LOGIN-004, TC-LOGIN-005   | PASS        | N/A       |
| RQ-004         | Products should be displayed to the user.                                     | TC-INV-001                   | PASS        | N/A       |
| RQ-005         | Product information should be displayed correctly.                            | TC-INV-002                   | PASS        | N/A       |
| RQ-006         | User should be able to view product details.                                  | TC-INV-003                   | PASS        | N/A       |
| RQ-007         | Product sorting options should be available.                                  | TC-SORT-001                  | PASS        | N/A       |
| RQ-008         | Products should be sorted correctly according to the selected option.         | TC-SORT-001                  | PASS        | N/A       |
| RQ-009         | User should be able to add products to the cart.                              | TC-INV-004                   | PASS        | N/A       |
| RQ-010         | Cart should display the correct number of selected products.                  | TC-CART-001, TC-CART-002     | PASS        | N/A       |
| RQ-011         | User should be able to view the cart.                                         | TC-CART-004                  | FAIL        | BUG-001   |
| RQ-012         | User should be able to remove products from the cart.                         | TC-CART-003                  | PASS        | N/A       |
| RQ-013         | Cart should display correct product information.                              | TC-CART-004                  | FAIL        | BUG-001   |
| RQ-014         | User should be able to proceed to checkout.                                   | TC-CHECKOUT-001              | PASS        | N/A       |
| RQ-015         | Checkout fields should be validated.                                          | TC-CHECKOUT-002              | PASS        | N/A       |
| RQ-016         | User should be able to enter valid checkout information and review the order. | TC-CHECKOUT-003              | PASS        | N/A       |
| RQ-017         | User should be able to complete an order.                                     | TC-ORDER-001                 | PASS        | N/A       |
| RQ-018         | System should display an order confirmation after successful checkout.        | TC-ORDER-002                 | PASS        | N/A       |
| RQ-019         | User should be able to log out.                                               | TC-LOGOUT-001                | PASS        | N/A       |
| RQ-020         | User should not be able to access authenticated areas after logout.           | TC-LOGOUT-001                | PASS        | N/A       |
| RQ-021         | Facebook footer link should work correctly.                                   | TC-FOOTER-001                | PASS        | N/A       |
| RQ-022         | X/Twitter and LinkedIn footer links should work correctly.                    | TC-FOOTER-002, TC-FOOTER-003 | PASS        | N/A       |

---

## Traceability Summary

| Metric                    | Result |
| ------------------------- | -----: |
| Total Requirements        |     22 |
| Requirements Covered      |     22 |
| Requirements Passed       |     20 |
| Requirements With Defects |      2 |
| Uncovered Requirements    |      0 |

---

## Defect Traceability

**BUG-001**

* Requirement: RQ-011 — View Cart
* Requirement: RQ-013 — Correct Cart Product Information
* Failed Test Case: TC-CART-004
* Defect: Product image is not displayed on the Cart page.
