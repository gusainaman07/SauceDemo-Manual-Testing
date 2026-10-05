# Test Cases

## Login Module

### TC-LOGIN-001

**Title:** Verify login with valid credentials

**Precondition:** User is on the login page.

**Test Data:**

* Username: `standard_user`
* Password: `secret_sauce`

**Steps:**

1. Enter valid username.
2. Enter valid password.
3. Click Login.

**Expected Result:**

User should successfully log in and reach the Products page.

**Priority:** High

---

### TC-LOGIN-002

**Title:** Verify login with invalid username

**Steps:**

1. Enter an invalid username.
2. Enter a valid password.
3. Click Login.

**Expected Result:**

Application should display an appropriate login error message and prevent the user from logging in.

**Priority:** High

---

### TC-LOGIN-003

**Title:** Verify login with invalid password

**Steps:**

1. Enter a valid username.
2. Enter an invalid password.
3. Click Login.

**Expected Result:**

Application should display an appropriate login error message and prevent the user from logging in.

**Priority:** High

---

### TC-LOGIN-004

**Title:** Verify login with empty username

**Steps:**

1. Leave username empty.
2. Enter a valid password.
3. Click Login.

**Expected Result:**

Application should display a username validation message and prevent login.

**Priority:** High

---

### TC-LOGIN-005

**Title:** Verify login with empty password

**Steps:**

1. Enter a valid username.
2. Leave password empty.
3. Click Login.

**Expected Result:**

Application should display a password validation message and prevent login.

**Priority:** High

---

## Inventory Module

### TC-INV-001

**Title:** Verify products are displayed on Products page

**Steps:**

1. Login with valid credentials.
2. Open the Products page.
3. Inspect the displayed products.

**Expected Result:**

All available products should be displayed with product names, images, prices, and Add to Cart buttons.

**Priority:** High

---

### TC-INV-002

**Title:** Verify product information

**Steps:**

1. Login.
2. Open the Products page.
3. Inspect the displayed products.

**Expected Result:**

Each product should display the product name, image, description, price, and Add to Cart button correctly.

**Priority:** Medium

---

### TC-INV-003

**Title:** Verify product details page

**Steps:**

1. Login.
2. Click a product name or image.
3. Observe the product details page.

**Expected Result:**

The selected product's details should be displayed correctly, including product name, image, description, price, Add to Cart button, and Back to Products button.

**Priority:** Medium

---

### TC-INV-004

**Title:** Verify Add to Cart functionality

**Steps:**

1. Login.
2. Select a product.
3. Click Add to Cart.
4. Open the Cart.

**Expected Result:**

The selected product should be added to the cart, the cart indicator should update correctly, and the selected product should be displayed in the Cart.

**Priority:** High

---

## Sorting Module

### TC-SORT-001

**Title:** Verify product sorting options

**Steps:**

1. Login.
2. Open the Products page.
3. Open the sorting dropdown.
4. Select Name (A to Z).
5. Select Name (Z to A).
6. Select Price (low to high).
7. Select Price (high to low).

**Expected Result:**

Products should be displayed in the correct order according to each selected sorting option.

**Priority:** Medium

---

## Cart Module

### TC-CART-001

**Title:** Verify cart count after adding one product

**Steps:**

1. Login.
2. Add one product to the cart.
3. Observe the cart indicator.

**Expected Result:**

Cart indicator should display `1`.

**Priority:** High

---

### TC-CART-002

**Title:** Verify cart count after adding multiple products

**Steps:**

1. Add one product.
2. Add another product.
3. Add a third product.
4. Observe the cart indicator after each addition.

**Expected Result:**

Cart indicator should display the correct number of products added.

**Priority:** High

---

### TC-CART-003

**Title:** Verify product can be removed from cart

**Steps:**

1. Add at least two products to the cart.
2. Open the Cart.
3. Remove one product.
4. Observe the cart.

**Expected Result:**

The selected product should be removed from the Cart and the cart indicator should update to show the remaining number of products.

**Priority:** High

---

### TC-CART-004

**Title:** Verify cart product information

**Steps:**

1. Add a product to the cart.
2. Open the Cart.
3. Compare the product information with the Products page.
4. Verify the product name, image, description, price, quantity, and Remove button.

**Expected Result:**

The Cart should display the selected product's name, image, description, price, quantity, and Remove button correctly.

**Priority:** Medium

**Observed Defect:** Product image was not displayed in the Cart.

**Defect ID:** BUG-001

---

## Checkout Module

### TC-CHECKOUT-001

**Title:** Verify user can proceed to checkout

**Steps:**

1. Add a product to the cart.
2. Open the Cart.
3. Click Checkout.

**Expected Result:**

User should be redirected to the Checkout Information page containing First Name, Last Name, and Postal Code fields.

**Priority:** High

---

### TC-CHECKOUT-002

**Title:** Verify checkout form validation

**Steps:**

1. Proceed to Checkout.
2. Leave required fields empty.
3. Click Continue.

**Expected Result:**

An appropriate validation message should be displayed for missing required information, and the user should not be allowed to continue.

**Priority:** High

---

### TC-CHECKOUT-003

**Title:** Verify checkout with valid information

**Steps:**

1. Add a product.
2. Open the Cart.
3. Click Checkout.
4. Enter valid checkout information.
5. Click Continue.

**Expected Result:**

Valid checkout information should be accepted and the user should proceed to the Checkout Overview page.

**Priority:** High

---

## Order Module

### TC-ORDER-001

**Title:** Verify order completion

**Steps:**

1. Complete the checkout information.
2. Review the order.
3. Click Finish.

**Expected Result:**

The order should be completed successfully.

**Priority:** Critical

---

### TC-ORDER-002

**Title:** Verify order confirmation

**Steps:**

1. Complete an order.
2. Observe the confirmation page.

**Expected Result:**

A successful order confirmation message should be displayed along with available post-order actions.

**Priority:** High

---

## Logout Module

### TC-LOGOUT-001

**Title:** Verify logout functionality

**Steps:**

1. Login.
2. Open the menu.
3. Click Logout.

**Expected Result:**

User should be logged out successfully and returned to the Login page.

**Priority:** High

---

## Footer Module

### TC-FOOTER-001

**Title:** Verify Facebook link

**Steps:**

1. Open the Products page.
2. Scroll to the footer.
3. Click the Facebook link.

**Expected Result:**

The Facebook link should open the intended destination successfully.

**Priority:** Low

---

### TC-FOOTER-002

**Title:** Verify X/Twitter link

**Steps:**

1. Open the Products page.
2. Scroll to the footer.
3. Click the X/Twitter link.

**Expected Result:**

The X/Twitter link should open the intended destination successfully.

**Priority:** Low

---

### TC-FOOTER-003

**Title:** Verify LinkedIn link

**Steps:**

1. Open the Products page.
2. Scroll to the footer.
3. Click the LinkedIn link.

**Expected Result:**

The LinkedIn link should open the intended destination successfully.

**Priority:** Low
