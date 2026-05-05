# 🔥 Smoke Test Execution Report – Conduit (RealWorld App)

## 📌 Project Overview
This document contains the execution results of the Smoke Test Suite.  
The objective is to validate critical system functionality after test execution.

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
| SMK-001 | Access Login Page | PASS | - |
| SMK-002 | Login with valid credentials | PASS | - |
| SMK-003 | Registration with valid data | FAIL | BUG-10, BUG-11 |
| SMK-004 | Basic login validation | PASS | - |

---

# 🏠 Home Module – Critical Flow

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| SMK-005 | Home page loads successfully | PASS | - |
| SMK-006 | Feed is displayed | PASS | - |
| SMK-007 | Basic navigation works | PASS | - |

---

# ⚙️ Settings Module – Critical Flow

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| SMK-008 | Access Settings page | PASS | - |
| SMK-009 | Update profile basic info | PASS | - |

---

# 📝 Articles – Critical Flow

| TC ID | Test Case | Status | Bug Reference |
|------|-----------|--------|---------------|
| SMK-010 | Basic article access | PASS | - |

---

## 📊 Smoke Execution Summary

| Status | Total |
|--------|------|
| PASS | 8 |
| FAIL | 2 |

---

## 🐞 Critical Defects Identified

| Bug ID | Description |
|--------|-------------|
| BUG-010 | Email verification not sent after registration |
| BUG-011 | Registration bypasses verification and redirects to Home |

---

## 📌 Final Conclusion

The system is partially stable.  
Core navigation, login, and home modules are functional.

However, the registration flow is broken due to missing email verification and incorrect redirection.
