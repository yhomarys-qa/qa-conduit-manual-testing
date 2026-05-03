# 🐞 BUG-01 - Username Validation Message is Duplicated and Inconsistent

## 📌 Summary
The validation message for the "Username" field appears duplicated and contains inconsistent rules, causing confusion for the user during registration.

---

## 🧪 Preconditions
- User accesses the registration page (Sign up)
- Application is available in the test environment
- Browser is open

---

## 🔁 Steps to Reproduce
1. Access the registration page  
2. In the Username field, enter a value starting with a number (e.g., 123yhoma)  
3. Fill in the other required fields  
4. Click the "Sign up" button  

---

## ❌ Actual Result
The system displays duplicated and inconsistent validation messages:

- "Username must start with a letter, have no spaces, and be at less than 40 characters."
- "Username must start with a letter, have no spaces, and be 2 - 40 characters."

Issues observed:
- Repeated text
- Conflicting rule definition ("less than 40" vs "2–40 characters")

---

## ✅ Expected Result
The system should display a single clear and consistent validation message:

> "Username must start with a letter, have no spaces, and be 2–40 characters long."

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
Screenshot attached showing duplicated validation messages.

![BUG-01 Evidence](<img width="1912" height="1145" alt="image-20260228-171507" src="https://github.com/user-attachments/assets/71d0266a-c065-46f1-b536-5f37ba5a6084" />
)


