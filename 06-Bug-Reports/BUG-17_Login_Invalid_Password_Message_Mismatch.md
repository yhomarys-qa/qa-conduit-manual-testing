# 🐞 BUG-17 - Incorrect Error Message Displayed for Invalid Password

## 📌 Summary
The system displays a generic error message instead of the expected specific error message when an invalid password is entered during login.

---

## 🧪 Preconditions
- Login page is accessible in the browser  
- User is registered in the system with valid credentials  

---

## 🔁 Steps to Reproduce
1. Access the login page  
2. Enter a valid email or username  
3. Enter an invalid password  
4. Click the "Sign In" button  

---

## ❌ Actual Result
The system displays the message:
> "Email or password is invalid"

---

## ✅ Expected Result
The system should display a more detailed message, such as:
> “Incorrect password! Check your keyboard layout or if Caps Lock is on. Send a temporary password to your email?”

---

## 📊 Severity
Low to Medium

---

## 📎 Environment
- Windows 10  
- Chrome 145.0.7632.76 (64-bit)  
- App version: Demo  

---

## 📎 Evidence
Screenshot showing generic error message displayed after entering an invalid password.

<img width="1918" height="1148" alt="image-20260305-190757 (1)" src="https://github.com/user-attachments/assets/19ed1591-9f04-474f-b667-2193fa1d00ff" />
