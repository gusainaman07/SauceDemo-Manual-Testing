# Bug Reports

## Bug Reporting Guidelines

Every confirmed defect should contain:

* Bug ID
* Summary
* Module
* Environment
* Preconditions
* Steps to Reproduce
* Expected Result
* Actual Result
* Severity
* Priority
* Status
* Screenshot/Evidence

---

## BUG-001

**Summary:** Product image is not displayed on the Cart page

**Module:** Cart

**Environment:** Google Chrome on Windows

**Preconditions:**

* User is logged in with valid credentials.
* User is on the Products page.

**Steps to Reproduce:**

1. Log in using valid credentials.
2. Select any product.
3. Click **Add to Cart**.
4. Open the **Cart** page.
5. Observe the selected product.

**Expected Result:**

The selected product's image should be displayed correctly on the Cart page along with its name, description, price, quantity, and Remove button.

**Actual Result:**

The selected product's image is not displayed on the Cart page. Other product information is displayed correctly.

**Severity:** Medium

**Priority:** Medium

**Status:** New

**Related Test Case:** `TC-CART-004`

**Evidence:**

`10-Screenshots/bugs/BUG-001-cart-product-image.png`

> **Note:** The screenshot should be added to the specified location after capturing the defect.
