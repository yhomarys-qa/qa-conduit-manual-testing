# 🐞 BUG-01 - Username Allows Registration with Only 2 Characters

## 📌 Summary
The system allows user registration with a username containing only 2 characters, violating the minimum length requirement.

---

## 🧪 Preconditions
- Registration page is accessible in the browser  
- User is not authenticated  

---

## 🔁 Steps to Reproduce
1. Access the registration page  
2. In the "Username" field, enter a 2-character value (e.g., `ac`)  
3. Fill in all other required fields with valid data  
4. Click the "Register" button  

---

## ❌ Actual Result
The system allows registration with a username containing only 2 characters, without displaying any validation error message.

---

## ✅ Expected Result
The system should block registration and display a validation error message when the username contains fewer than 3 characters.

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
Screenshot showing successful registration with a 2-character username.

<img width="1918" height="1143" alt="image" src="https://github.com/user-attachments/assets/151bb04a-8426-4188-a269-acf9fc261776" />

