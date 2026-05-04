# 🐞 BUG-03 - Incomplete Error Message for Already Registered Email

## 📌 Summary
The system displays an incomplete error message when a user attempts to register with an email address that is already in use. The second part of the message is missing.

---

## 🧪 Preconditions
- Registration page is accessible in the browser  
- User is not authenticated  

---

## 🔁 Steps to Reproduce
1. Access the registration page  
2. Enter an email address that is already registered  
3. Fill in all other required fields with valid data  
4. Click the "Register" button  

---

## ❌ Actual Result
The system displays only:
> "This email address is already in use."

The second part of the expected message is missing:
> "Do you want to log in?"

---

## ✅ Expected Result
The system should display the full error message:
> "This email address is already in use. Do you want to log in?"

---

## 📊 Severity
Medium

---

## 📎 Environment
- Windows 10  
- Chrome 145.0.7632.76 (64-bit)  
- App version: Demo  

---

## 📎 Evidence
Screenshot showing incomplete error message displayed on registration page.

<img width="1917" height="1090" alt="image-20260302-155103" src="https://github.com/user-attachments/assets/f1ffcb1c-b939-44b6-b2ee-c43d2b04d982" />
