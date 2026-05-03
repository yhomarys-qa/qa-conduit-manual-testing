# 🐞 BUG-08 - Password Does Not Enforce Number and Special Character Requirements

## 📌 Summary
The system does not properly validate password complexity rules, allowing registration even when the password does not include required numbers and/or special characters.

---

## 🧪 Preconditions
- Registration page is accessible in the browser  
- User is not authenticated  

---

## 🔁 Steps to Reproduce
1. Access the registration page  

2. Test the following password scenarios:

   - Password without numbers: `Ventanas#`  
   - Password without special characters: `Ventanas12`  
   - Password without numbers and special characters: `Ventanass`  

3. Fill in all other required fields with valid data  
4. Click the "Register" button  

---

## ❌ Actual Result
The system allows registration even when the password does not meet complexity requirements (missing numbers and/or special characters), without displaying any validation error message.

---

## ✅ Expected Result
The system should enforce password complexity rules and display an error message when the password does not contain at least one number and one special character.

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
Video attached showing that the system allows registration with passwords that do not meet complexity requirements.

Test password used: `Qaaanalistas`

https://1drv.ms/v/c/908f21af6642c0ae/IQC5WscedqJzQ6tkJq8eqB6tAZk-QdQghxn0bDmC6jupWus?e=Hm08Kj
