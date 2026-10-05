# Test Data

## 1. Valid Login Credentials

| Field    | Value           |
| -------- | --------------- |
| Username | `standard_user` |
| Password | `secret_sauce`  |

**Purpose:** Positive login testing.

---

## 2. Invalid Login Data

| Test Data                          | Purpose                   |
| ---------------------------------- | ------------------------- |
| `wrong_user` / `secret_sauce`      | Invalid username testing  |
| `standard_user` / `wrong_password` | Invalid password testing  |
| Empty username / `secret_sauce`    | Required field validation |
| `standard_user` / Empty password   | Required field validation |

---

## 3. Checkout Test Data

| Field       | Test Value |
| ----------- | ---------- |
| First Name  | Aman       |
| Last Name   | Tester     |
| Postal Code | 248001     |

**Purpose:** Validate checkout information and complete the order flow.

> **Note:** The checkout information above is fictional test data. Do not use real payment information or sensitive personal information during testing.
