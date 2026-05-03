# 🐞 BUG-06 - Password Allows Registration with More Than 30 Characters

## 📌 Summary
The system allows user registration with a password exceeding the maximum allowed length (30 characters), indicating that the upper boundary validation is not enforced.

---

## 🧪 Preconditions
- Registration page is accessible in the browser  
- User is not authenticated  

---

## 🔁 Steps to Reproduce
1. Access the registration page  
2. Enter a 31-character password in the "Password" field (e.g., `Senhausuarionaalistapessoasentrada`)  
3. Fill in all other required fields with valid data  
4. Click the "Register" button  

---

## ❌ Actual Result
The system allows registration with a password longer than 30 characters without displaying any validation error message.

---

## ✅ Expected Result
The system should block the registration and display a validation error message when the password exceeds 30 characters.

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
Video attached showing successful registration with a password longer than 30 characters without validation error.

https://1drv.ms/v/c/908f21af6642c0ae/IQDqzXCx4jFGQqj2sNs2x6drAeHCoKD6bBctp0JwmytiheA?e=ZZGHwE
