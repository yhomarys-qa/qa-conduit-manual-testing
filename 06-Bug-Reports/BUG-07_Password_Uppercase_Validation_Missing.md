# 🐞 BUG-07 - Password Allows Registration Without Uppercase Letters

## 📌 Summary
The system allows user registration with a password that does not contain uppercase letters, indicating that the uppercase validation rule is not being enforced.

---

## 🧪 Preconditions
- Registration page is accessible in the browser  
- User is not authenticated  

---

## 🔁 Steps to Reproduce
1. Access the registration page  
2. Enter a password containing only lowercase letters (e.g., `passwordabc`)  
3. Fill in all other required fields with valid data  
4. Click the "Register" button  

---

## ❌ Actual Result
The system allows registration with a password that does not contain uppercase letters, without displaying any validation error message.

---

## ✅ Expected Result
The system should block registration and display an error message indicating that the password must contain at least one uppercase letter.

---

## 📊 Severity
High

---

## 📎 Environment
- Windows 10  
- Chrome 145.0.7632.76 (64-bit)  
- App version: Demo  

---

## 📎 Evidence
Video attached showing successful registration with a password without uppercase letters.

Test password used: `usuario20#`

https://1drv.ms/v/c/908f21af6642c0ae/IQC70EbQqUPKS5Bobe4a8YC3Ad8IcqbsMKqq9JGsGFW9YSw?e=R0Ht5w
