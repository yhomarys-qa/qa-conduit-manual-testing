# 🐞 BUG-021 – New Password Allows Submission Without Uppercase Letter

### 📝 Summary
The system allows users to set a new password without at least one uppercase letter, violating password complexity requirements and compromising security rules.

---

### ⚙️ Preconditions
- User is authenticated  
- Settings page is accessible  

---

### 🔁 Steps to Reproduce
1. Navigate to **Settings** page  
2. Enter a new password without uppercase letters (e.g., `testing#03`)  
3. Fill in all other required fields with valid data  
4. Click on **“Update Settings”**

---

### ❌ Actual Result
The system accepts the update with a password that does not contain any uppercase letters, without displaying any validation error.

---

### ✅ Expected Result
The system should reject the update and display a validation error indicating that the new password must contain at least one uppercase letter.

---

### 🔥 Severity
**High**

---

### 🌐 Environment
- **OS:** Windows 10  
- **Browser:** Chrome 145.0.7632.76 (64-bit)  
- **Application Version:** Demo  

---

### 📎 Evidence
Attached video shows a successful update using a password without uppercase letters.

**Test Password Used:** `testing#03`

https://1drv.ms/v/c/908f21af6642c0ae/IQBCvNftwtjYT7WwEWHhMnSYASBGE2YY0t8NOLRWtNws8Xk?e=G6oago

---
