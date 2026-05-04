# 🐞 BUG-012 - Login Field Does Not Accept Username (Only Email Format Allowed)

## 📌 Summary
The login field labeled "Email or Username" incorrectly restricts input to email format only, preventing users from logging in using a username.

---

## 🧪 Preconditions
- Login page is accessible in the browser  
- User is registered in the system with a valid username and password  

---

## 🔁 Steps to Reproduce
1. Go to the login page  
2. In the "Email or Username" field, enter a valid username (e.g., `userr123`)  
3. In the "Password" field, enter a valid password  
4. Click the "Log In" button  

---

## ❌ Actual Result
The system does not accept usernames and forces the input to match an email format.

---

## ✅ Expected Result
The system should allow authentication using either email or username in the "Email or Username" field.

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
Screenshot showing that the field rejects username input and requires email format instead.

<img width="1917" height="1152" alt="image-20260305-163510" src="https://github.com/user-attachments/assets/bd58d338-7b09-4343-957f-4b0e6aedbe30" />
