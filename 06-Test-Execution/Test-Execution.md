# Test Execution Report

## Test Execution Summary

| Metric                    | Result |
| ------------------------- | -----: |
| Total Test Cases Executed |     23 |
| Passed                    |     22 |
| Failed                    |      1 |
| Blocked                   |      0 |
| Not Executed              |      0 |
| Defects Found             |      1 |

---

## Test Execution Results

| Test Case ID    | Test Scenario                      | Status | Actual Result                                                                                    | Defect ID |
| --------------- | ---------------------------------- | ------ | ------------------------------------------------------------------------------------------------ | --------- |
| TC-LOGIN-001    | Valid Login                        | PASS   | User was successfully logged in and redirected to the Products page.                             | N/A       |
| TC-LOGIN-002    | Invalid Username                   | PASS   | Appropriate error message was displayed and login was prevented.                                 | N/A       |
| TC-LOGIN-003    | Invalid Password                   | PASS   | Appropriate error message was displayed and login was prevented.                                 | N/A       |
| TC-LOGIN-004    | Empty Username                     | PASS   | "Epic sadface: Username is required" was displayed.                                              | N/A       |
| TC-LOGIN-005    | Empty Password                     | PASS   | "Epic sadface: Password is required" was displayed.                                              | N/A       |
| TC-INV-001      | Products Displayed                 | PASS   | All products, names, images, prices, and Add to Cart buttons were displayed.                     | N/A       |
| TC-INV-002      | Product Information                | PASS   | Product names, images, descriptions, prices, and Add to Cart buttons were displayed correctly.   | N/A       |
| TC-INV-003      | Product Details                    | PASS   | Product details page displayed the expected product information and controls.                    | N/A       |
| TC-INV-004      | Add Product to Cart                | PASS   | Product was added successfully and correct cart information was displayed.                       | N/A       |
| TC-SORT-001     | Product Sorting                    | PASS   | All four sorting options worked correctly.                                                       | N/A       |
| TC-CART-001     | Cart Count After One Product       | PASS   | Cart badge displayed `1` after adding one product.                                               | N/A       |
| TC-CART-002     | Cart Count After Multiple Products | PASS   | Cart badge displayed the correct count for multiple products.                                    | N/A       |
| TC-CART-003     | Remove Product from Cart           | PASS   | Selected product was removed and cart count was updated correctly.                               | N/A       |
| TC-CART-004     | Cart Product Information           | FAIL   | Product information was displayed, but the product image was not displayed in the Cart.          | BUG-001   |
| TC-CHECKOUT-001 | Proceed to Checkout                | PASS   | User was redirected to the Checkout Information page.                                            | N/A       |
| TC-CHECKOUT-002 | Checkout Validation                | PASS   | "First Name is required" validation message was displayed when required information was missing. | N/A       |
| TC-CHECKOUT-003 | Valid Checkout Information         | PASS   | Valid checkout information was accepted and user proceeded to Checkout Overview.                 | N/A       |
| TC-ORDER-001    | Complete Order                     | PASS   | Order was successfully completed after clicking Finish.                                          | N/A       |
| TC-ORDER-002    | Order Confirmation                 | PASS   | Thank You confirmation message and action buttons were displayed.                                | N/A       |
| TC-LOGOUT-001   | Logout                             | PASS   | User was successfully logged out and redirected to the Login page.                               | N/A       |
| TC-FOOTER-001   | Facebook Link                      | PASS   | Facebook link opened successfully.                                                               | N/A       |
| TC-FOOTER-002   | X/Twitter Link                     | PASS   | X/Twitter link opened successfully.                                                              | N/A       |
| TC-FOOTER-003   | LinkedIn Link                      | PASS   | LinkedIn link opened successfully.                                                               | N/A       |

---

## Defect Summary

| Defect ID | Summary                                         | Severity | Priority | Status |
| --------- | ----------------------------------------------- | -------- | -------- | ------ |
| BUG-001   | Product image is not displayed on the Cart page | Medium   | Medium   | New    |

---

## Execution Conclusion

A total of 23 test cases were executed during the test cycle. 22 test cases passed and 1 test case failed.

One defect was identified during testing: the product image was not displayed on the Cart page.

Further retesting is required after the defect is fixed.
