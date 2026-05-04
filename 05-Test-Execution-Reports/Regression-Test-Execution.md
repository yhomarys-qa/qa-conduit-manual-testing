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

# 🔐 Authentication – Login

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| TC-001 | Access Login Page | PASS | - |
| TC-003 | Login with valid email | PASS | - |
| TC-004 | Login with username | FAIL | BUG-12 |
| TC-005 | Empty email validation | PASS | - |
| TC-014 | Invalid password validation | FAIL | BUG-17 |
| TC-016 | Forgot password link visible | FAIL | BUG-19 |
| TC-017 | Forgot password redirect | FAIL | BUG-18 |
| TC-018 | Login button displayed | PASS | - |
| TC-020 | Login using Enter key | PASS | - |

---

# 🧾 Authentication – Registration

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| TC-001 | Access Registration Page | PASS | - |
| TC-002 | SignUp link visibility | PASS | - |
| TC-003 | Username validation rules | FAIL | BUG-01 |
| TC-008 | Username required field | PASS | - |
| TC-009 | Username uniqueness | PASS | - |
| TC-010 | Username min length | FAIL | BUG-03 |
| TC-018 | Email required field | PASS | - |
| TC-019 | Email format validation | FAIL | BUG-02 |
| TC-025 | Password min length | FAIL | BUG-05 |
| TC-026 | Password max length | FAIL | BUG-06 |
| TC-027 | Password uppercase rule | FAIL | BUG-07 |
| TC-029 | Password complexity rules | FAIL | BUG-08 |
| TC-030 | Confirm password field | FAIL | BUG-09 |
| TC-037 | Successful registration | FAIL | BUG-11 |
| TC-038 | Email verification sent | FAIL | BUG-10 |

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
| TC-01 | Access Settings page | PASS | - |
| TC-02 | Edit profile | PASS | - |
| TC-03 | Save profile changes | PASS | - |
| TC-11 | Username mandatory | PASS | - |
| TC-20 | Email mandatory | PASS | - |
| TC-41 | Password min length | FAIL | BUG-05 |
| TC-44 | Password uppercase rule | FAIL | BUG-07 |
| TC-50 | Update settings valid data | PASS | - |
| TC-71 | Logout redirects home | PASS | - |
| TC-72 | Session termination | PASS | - |

---

## 📊 Execution Summary

| Status | Total |
|--------|------|
| PASS | 34 |
| FAIL | 12 |

---

## 🐞 Defect Traceability

| Bug ID | Description |
|--------|-------------|
| BUG-01 | Username validation duplicated/inconsistent rules |
| BUG-02 | Email allows invalid special characters |
| BUG-03 | Username min length not enforced |
| BUG-05 | Password min length not enforced |
| BUG-06 | Password max length not enforced |
| BUG-07 | Password uppercase rule missing |
| BUG-08 | Password complexity not enforced |
| BUG-09 | Confirm password field missing |
| BUG-10 | Email verification not sent |
| BUG-11 | Registration flow bypasses verification |
| BUG-12 | Login does not accept username |
| BUG-17 | Incorrect login error message |
| BUG-18 | Incorrect login error message |
| BUG-19 | Forgot password link missing |

---

## 📌 Final Conclusion

All test cases from the Regression Test Suite were executed.  
The system shows critical failures in Authentication and Registration modules, mainly affecting user onboarding and login reliability.

Home, Articles, and Settings modules show stable behavior under tested conditions.
