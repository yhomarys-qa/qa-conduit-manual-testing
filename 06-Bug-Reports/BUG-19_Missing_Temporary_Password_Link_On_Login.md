# 🐞 BUG-19 - “Send Temporary Password” Link Not Displayed After Invalid Login Attempt

## 📌 Summary
The system does not display the "Send temporary password" link after an invalid login attempt, preventing users from accessing the password recovery option directly from the login error state.

---

## 🧪 Preconditions
- Login page is accessible in the browser  
- User is registered in the system with valid credentials  

---

## 🔁 Steps to Reproduce
1. Access the login page  
2. Enter a valid username or email  
3. Enter an invalid password  
4. Click the "Sign In" button  
5. Observe the error message area  

---

## ❌ Actual Result
The system displays only the error message and does not show the "Send temporary password" link.

---

## ✅ Expected Result
The system should display the "Send temporary password" link when login fails due to an incorrect password, allowing the user to initiate password recovery.

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
Screenshot showing absence of the "Send temporary password" link after invalid login attempt.

<img width="1918" height="1147" alt="image-20260305-192201" src="https://github.com/user-attachments/assets/0844fd01-4e58-4e8f-a3a5-d1d80bcd4fe3" />
