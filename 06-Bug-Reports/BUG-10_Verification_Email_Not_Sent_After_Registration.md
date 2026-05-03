# 🐞 BUG-10 - Verification Email Is Not Sent After Successful Registration

## 📌 Summary
The system does not send a verification email after successful user registration, preventing email-based verification from being completed.

---

## 🧪 Preconditions
- Registration page is accessible in the browser  
- User is not authenticated  
- A valid and accessible email address is available  

---

## 🔁 Steps to Reproduce
1. Access the registration page  
2. Fill in all required fields with valid data  
3. Provide a valid and accessible email address  
4. Click the "Register" button or press Enter  
5. Wait for the registration process to complete  
6. Check the inbox, spam, and other folders of the provided email address  
7. Verify if a 6-digit verification email has been received  

---

## ❌ Actual Result
The registration completes successfully, but no verification email is sent to the provided email address.

---

## ✅ Expected Result
The system should send a verification email containing a 6-digit code immediately after successful registration.

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
Screenshot showing successful registration.

<img width="1917" height="1152" alt="image-20260304-140243" src="https://github.com/user-attachments/assets/2a86a25c-c591-4e88-9997-9b715fb404fa" />

Screenshot of the email inbox showing the absence of the verification message.

<img width="1901" height="1093" alt="image-20260304-140216" src="https://github.com/user-attachments/assets/55e151b2-498f-4eb7-83cc-60c0a6185faa" />
