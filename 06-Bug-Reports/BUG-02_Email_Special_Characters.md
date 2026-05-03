# 🐞 BUG-02 - Email Field Allows Invalid Special Characters in Local Part

## 📌 Summary
The system allows registration with an email containing special characters that are not valid in the local part of the email address.

---

## 🧪 Preconditions
- Registration page accessible in browser  
- User not authenticated  

---

## 🔁 Steps to Reproduce
1. Access the registration page  
2. In the "Email" field, enter: `pase#casa@gmail.com`  
3. Fill in other required fields with valid data  
4. Click the "Register" button  

---

## ❌ Actual Result
The system allows registration with an email containing invalid special characters (e.g., `#`) in the local part, without showing any validation error.

---

## ✅ Expected Result
The system should block registration and display an error message when the email contains invalid special characters in the local part.

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
Screenshot showing registration accepted with invalid email format.

<img width="1908" height="1087" alt="image-20260302-140905" src="https://github.com/user-attachments/assets/a7534d34-a820-47de-ad66-027a0b94936c" />
