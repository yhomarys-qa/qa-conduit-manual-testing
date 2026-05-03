# 🐞 BUG-16 - Authenticated User Can Access Login Page Instead of Being Redirected

## 📌 Summary
The system allows an authenticated user to access the login page instead of automatically redirecting them to the home page or user dashboard.

---

## 🧪 Preconditions
- User is registered in the system  
- User is authenticated (logged in)  
- Active session is present in the browser  

---

## 🔁 Steps to Reproduce
1. Log in to the system with valid credentials  
2. Confirm successful authentication  
3. While still logged in, manually navigate to the login page URL  

---

## ❌ Actual Result
The system displays the login page even though the user is already authenticated.

---

## ✅ Expected Result
The system should automatically redirect authenticated users to the home page or their account dashboard when they attempt to access the login page.

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
Screenshot showing authenticated user still being able to access the login page.

<img width="1918" height="1145" alt="image-20260305-181002" src="https://github.com/user-attachments/assets/ffb58051-d463-4199-91cd-327afb426a7e" />
