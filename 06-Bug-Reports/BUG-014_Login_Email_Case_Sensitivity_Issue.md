# 🐞 BUG-014 - Email Field Rejects Uppercase Email on Login

## 📌 Summary
The login system incorrectly rejects valid email addresses when they are entered in uppercase letters, treating them as invalid.

---

## 🧪 Preconditions
- Login page is accessible in the browser  
- User has a valid registered account  

---

## 🔁 Steps to Reproduce
1. Go to the login page  
2. In the "Email" field, enter a valid email in uppercase (e.g., `USUARIOS55@GMAIL.COM`)  
3. Enter a valid password  
4. Click the "Sign In" button  

---

## ❌ Actual Result
The system displays an "invalid email" error message when the email is entered in uppercase letters.

---

## ✅ Expected Result
The system should accept email addresses regardless of letter case (uppercase or lowercase).

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
Screenshot showing error message when uppercase email is used during login.

<img width="1913" height="1150" alt="image-20260305-172147" src="https://github.com/user-attachments/assets/478039b4-b97b-431d-94da-734dffc7ec83" />
