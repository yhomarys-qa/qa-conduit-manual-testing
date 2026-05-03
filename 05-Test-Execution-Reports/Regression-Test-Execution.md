# 📊 Regression Test Execution Report – Conduit (RealWorld App)

## 📌 Project Overview
This document contains the execution results of the Regression Test Suite for the Conduit (RealWorld) application, including traceability to reported defects.

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
| TC-014 | Invalid password validation | FAIL | BUG-17 |
| TC-016 | Forgot password link visible | FAIL | BUG-19 |
| TC-017 | Forgot password redirect | FAIL | BUG-19 |
| TC-018 | Login button visible | PASS | - |

---

# 🧾 Authentication – Registration

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| TC-001 | Access Registration Page | PASS | - |
| TC-003 | Username validation rules | FAIL | BUG-01 |
| TC-010 | Username min length | FAIL | BUG-03 |
| TC-019 | Email format validation | FAIL | BUG-02 |
| TC-025 | Password min length | FAIL | BUG-05 |
| TC-026 | Password max length | FAIL | BUG-06 |
| TC-027 | Password uppercase rule | FAIL | BUG-07 |
| TC-029 | Password complexity rules | FAIL | BUG-08 |
| TC-030 | Confirm password field | FAIL | BUG-09 |
| TC-037 | Successful registration | FAIL | BUG-11 |
| TC-038 | Email verification sent | FAIL | BUG-10 |

---

# 📰 Articles – New Article

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| TC-001 | Access New Article page | NOT EXECUTED | - |
| TC-003 | Title required | NOT EXECUTED | - |
| TC-022 | Body required | NOT EXECUTED | - |
| TC-034 | Add tag | NOT EXECUTED | - |

---

# 🏠 Home Module

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| TC-001 | Home via logo | PASS | - |
| TC-004 | Feed tabs visible | PASS | - |
| TC-010 | Pagination | PASS | - |
| TC-025 | Like article | PASS | - |

---

# ⚙️ Settings Module

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| TC-01 | Access Settings page | PASS | - |
| TC-03 | Save profile changes | PASS | - |
| TC-41 | Password min length | FAIL | BUG-05 |
| TC-44 | Password uppercase rule | FAIL | BUG-07 |
| TC-71 | Logout redirect | PASS | - |
| TC-72 | Session termination | PASS | - |

---

# 📊 Execution Summary

| Status | Total |
|--------|------|
| PASS | 18 |
| FAIL | 12 |
| NOT EXECUTED | 20+ |

---

# 🐞 Defect Traceability

| Bug ID | Description |
|--------|-------------|
| BUG-01 | Username validation duplicated/inconsistent |
| BUG-02 | Email allows invalid special characters |
| BUG-03 | Username min length not enforced |
| BUG-05 | Password min length not enforced |
| BUG-06 | Password max length not enforced |
| BUG-07 | Password uppercase rule missing |
| BUG-08 | Password complexity not enforced |
| BUG-09 | Confirm password missing |
| BUG-10 | Email verification not sent |
| BUG-11 | Registration flow bypasses verification |
| BUG-12 | Login does not accept username |
| BUG-17 | Incorrect login error message |
| BUG-19 | Forgot password link missing |

---

# 📌 Conclusion

The system shows critical failures in authentication and registration modules, making it unstable for production use. Home and Settings modules show stable behavior within tested scope.
