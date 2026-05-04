# 🐞 BUG-005 - Password Allows Registration with Less Than 8 Characters

## 📌 Summary
The system allows user registration with a password shorter than the required minimum length (8 characters), compromising password security rules.

---

## 🧪 Preconditions
- Registration page is accessible in the browser  
- User is not authenticated  

---

## 🔁 Steps to Reproduce
1. Access the registration page  
2. Enter a 1-character password in the "Password" field (e.g., `a`)  
3. Fill in all other required fields with valid data  
4. Click the "Register" button  

---

## ❌ Actual Result
The system allows registration with a password containing only 1 character, without displaying any validation error message.

---

## ✅ Expected Result
The system should block the registration and display a validation error message when the password is shorter than 8 characters.

---

## 📊 Severity
Critical

---

## 📎 Environment
- Windows 10  
- Chrome 145.0.7632.76 (64-bit)  
- App version: Demo  

---

## 📎 Evidence
Video attached showing that the system allows registration with a 1-character password without validation error.

https://1drv.ms/v/c/908f21af6642c0ae/IQCKWUsCMZpsRaHmJt98rwLKAWnl_DF8VGMdFshlHM5QNxg?e=5LQbd2
