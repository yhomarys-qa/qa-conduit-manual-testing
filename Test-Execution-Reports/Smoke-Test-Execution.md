# 🔥 Smoke Test Execution Report – Conduit (RealWorld App)

## 📌 Project Overview
This document contains the execution results of the Smoke Test Suite for the Conduit application.  
The objective is to validate critical system functionality and determine if the system is stable for further testing.

---

## 📅 Execution Information
- Date: 2026-05-02  
- Environment: QA / Demo  
- Browser: Chrome 145  
- Tester: QA Manual Tester  

---

# 🔐 Authentication – Critical Flow

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| SMK-01 | Access Login Page | PASS | - |
| SMK-02 | Login with valid credentials (email) | PASS | - |
| SMK-03 | Registration with valid data | FAIL | BUG-10, BUG-11 |
| SMK-04 | Login page validation (basic check) | PASS | - |

---

# 🏠 Home Module – Critical Flow

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| SMK-05 | Home page loads successfully | PASS | - |
| SMK-06 | Feed is displayed | PASS | - |
| SMK-07 | Basic navigation works | PASS | - |

---

# 📝 Articles – Critical Flow

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| SMK-08 | Access article creation (basic check) | NOT EXECUTED | - |

---

# ⚙️ Settings – Critical Flow

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| SMK-09 | Access Settings page | PASS | - |
| SMK-10 | Update basic profile info | PASS | - |

---

## 📊 Smoke Execution Summary

| Status | Total |
|--------|------|
| PASS | 7 |
| FAIL | 1 |
| NOT EXECUTED | 1 |

---

## 🚨 Critical Issues Identified

| Bug ID | Description |
|--------|-------------|
| BUG-10 | Email verification not sent after registration |
| BUG-11 | Registration redirects directly to Home without verification |

---

## ❗ Conclusion

The application is partially stable.  
Core navigation and login functionality are working, but the registration flow is broken due to missing email verification and incorrect redirection.

👉 Recommendation: Do NOT proceed with full regression until registration flow is fixed.
