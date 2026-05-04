# 🐞 BUG-015 - Incorrect Error Message Displayed for Invalid Login Credentials

## 📌 Summary
The system displays a generic error message instead of the expected specific message when invalid login credentials are entered.

---

## 🧪 Preconditions
- Login page is accessible in the browser  
- User is registered in the system  

---

## 🔁 Steps to Reproduce
1. Go to the login page  
2. In the "Email" field, enter a valid registered email  
3. In the "Password" field, enter an invalid password  
4. Click the "Sign In" button  

---

## ❌ Actual Result
The system displays the message:
> "Email or password is invalid."

---

## ✅ Expected Result
The system should display the message:
> "User with this email or username not registered"

when the credentials do not match any registered user.

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
Screenshot showing the generic error message displayed after invalid login attempt.

<img width="1918" height="1148" alt="image-20260305-174224" src="https://github.com/user-attachments/assets/ea1dba35-d8c7-42b5-b23b-468986ee4e61" />
