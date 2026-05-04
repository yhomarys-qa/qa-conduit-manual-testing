# 📊 Regression Test Execution Report – Conduit (RealWorld App)

## 📌 Project Overview
This document contains the execution results of the full Regression Test Suite for the Conduit application.  
All test cases were executed, and results are based on actual observed behavior and reported defects.

---

## 📅 Execution Information
- Date: 2026-05-02  
- Environment: QA / Demo  
- Browser: Chrome 145  
- Tester: QA Manual Tester  

---

# 🧾 Authentication – Registration

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| TC-001 | Access Registration Page | PASS | - |
| TC-002 | SignUp link visibility | PASS | - |
| TC-008 | Username required field | PASS | - |
| TC-009 | The username must be unique | PASS | - |
| TC-010 | Username min length | FAIL | BUG-001 |
| TC-012 | The username must begin with a letter | FAIL | BUG-002 |
| TC-018 | Email required field | PASS | - |
| TC-020 | The email address must be unique | FAIL | BUG-003 |
| TC-021 | Email allows special characters | FAIL | BUG-004 |
| TC-025 | Password min length | FAIL | BUG-005 |
| TC-026 | Password max length | FAIL | BUG-006 |
| TC-027 | Password uppercase rule | FAIL | BUG-007 |
| TC-028 | The password must contain a number | FAIL | BUG-008 |
| TC-029 | The password must contain a special character | FAIL | BUG-008 |
| TC-030 | Confirm password field | FAIL | BUG-009 |
| TC-037 | Registration completed successfully | FAIL | BUG-010 |
| TC-038 | Redirect to "Complete Registration" | FAIL | BUG-011 |

---

# 🔐 Authentication – Login

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| TC-001 | Access Login Page | PASS | - |
| TC-003 | Login with valid email | PASS | - |
| TC-004 | Login with username | FAIL | BUG-012 |
| TC-005 | Empty email validation | PASS | - |
| TC-014 | Invalid password validation | FAIL | BUG-017 |
| TC-016 | Forgot your password link visible | FAIL | BUG-018 |
| TC-017 | Redirect to password recovery | FAIL | BUG-019 |
| TC-018 | Login button displayed | PASS | - |
| TC-020 | Login using Enter key | PASS | - |

---

# 📝 Articles – New Article

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| TC-001 | Access New Article page | PASS | - |
| TC-002 | Access without authentication | PASS | - |
| TC-003 | Title required validation | PASS | - |
| TC-005 | Title min length | PASS | - |
| TC-013 | Description required | PASS | - |
| TC-022 | Body required | PASS | - |
| TC-034 | Add valid tag | PASS | - |

---

# 🏠 Home Module

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| TC-001 | Home via logo | PASS | - |
| TC-004 | Feed tabs visible | PASS | - |
| TC-005 | Empty feed behavior | PASS | - |
| TC-010 | Pagination | PASS | - |
| TC-013 | Author display | PASS | - |
| TC-025 | Like article | PASS | - |
| TC-029 | Filter by tag | PASS | - |

---

# ⚙️ Settings Module

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| TC-001 | Access Settings page | PASS | - |
| TC-002 | Edit profile | PASS | - |
| TC-003 | Save profile changes | PASS | - |
| TC-011 | Username mandatory | PASS | - |
| TC-020 | Email mandatory | PASS | - |
| TC-041 | Password min length | FAIL | BUG-020 |
| TC-044 | Password uppercase rule | FAIL | BUG-021 |
| TC-050 | Update settings valid data | PASS | - |
| TC-071 | Logout redirects home | PASS | - |
| TC-072 | Session termination | PASS | - |

---

## 📊 Execution Summary

| Status | Total |
|--------|------|
| PASS | 32 |
| FAIL | 21 |

---

## 🐞 Defect Traceability

| Bug ID | Description |
|--------|-------------|
| BUG-001 | Username Allows Registration with Only 2 Characters |
| BUG-002 | Username Validation Message Inconsistent |
| BUG-003 | Incomplete Email Already Registered Message |
| BUG-004 | Email Accepts Invalid Special Characters |
| BUG-005 | Password Accepts Less Than 8 Characters |
| BUG-006 | Password Max Length Not Enforced |
| BUG-007 | Password Uppercase Requirement Not Enforced |
| BUG-008 | Password Number & Special Character Requirements Not Enforced |
| BUG-009 | Confirm Password Field Not Displayed |
| BUG-010 | Email verification not sent |
| BUG-011 | Registration flow bypasses verification |
| BUG-012 | Login does not accept username |
| BUG-017 | Incorrect login error message |
| BUG-018 | Temporary Password Link Not Displayed |
| BUG-019 | Forgot password link missing |

---

## 📌 Final Conclusion

All test cases from the Regression Test Suite were executed.  
The system shows critical failures in Authentication and Registration modules, mainly affecting user onboarding and login reliability.

Home, Articles, and Settings modules show stable behavior under tested conditions.
