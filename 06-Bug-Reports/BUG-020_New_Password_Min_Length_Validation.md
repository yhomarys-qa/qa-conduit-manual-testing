# 🐞 BUG-020 – New Password Allows Less Than Minimum Length

### 📝 Summary
The system allows users to set a new password with fewer than 8 characters, violating the minimum password length requirement and compromising security rules.

---

### ⚙️ Preconditions
- User is authenticated  
- Settings page is accessible  

---

### 🔁 Steps to Reproduce
1. Navigate to **Settings** page  
2. Enter a new password with fewer than 8 characters (e.g., `Ab2`)  
3. Fill in all other required fields with valid data  
4. Click on **“Update Settings”**

---

### ❌ Actual Result
The system accepts the update with a password shorter than 8 characters without displaying any validation error.

---

### ✅ Expected Result
The system should reject the update and display a validation error message when the new password has fewer than 8 characters.

---

### 🔥 Severity
**Critical**

---

### 🌐 Environment
- **OS:** Windows 10  
- **Browser:** Chrome 145.0.7632.76 (64-bit)  
- **Application Version:** Demo  

---

### 📎 Evidence
The attached video demonstrates that the system accepts a password with only 3 characters without any validation error.

Test password used: Ab2

https://1drv.ms/v/c/908f21af6642c0ae/IQAIzduGEfP3SYJlHzk3RL2lAb7etRlQGm1kUSnF2Ny917g?e=vCbbGT

---
