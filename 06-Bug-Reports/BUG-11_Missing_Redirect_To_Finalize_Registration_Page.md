# 🐞 BUG-11 - System Does Not Redirect to “Finalize Registration” Page After Successful Registration

## 📌 Summary
After successful registration, the system incorrectly redirects the user directly to the Home page instead of the expected “Finalize Registration” page, skipping the email verification step.

---

## 🧪 Preconditions
- Registration page is accessible in the browser  
- User is not authenticated  
- Valid and accessible email address is available for verification  

---

## 🔁 Steps to Reproduce
1. Access the registration page  
2. Fill in all required fields with valid data  
3. Click the "Register" button or press Enter  
4. Observe the redirection behavior  
5. Check whether the user is redirected to the "Finalize Registration" page  
6. Verify if a 6-digit verification code input screen is displayed  

---

## ❌ Actual Result
The system redirects the user directly to the Home page with an active session, without requiring email verification or showing the “Finalize Registration” page.

---

## ✅ Expected Result
The system should redirect the user to the “Finalize Registration” page, where they must enter the 6-digit verification code sent to their email before gaining full access.

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
Screenshot showing user automatically logged into Home page immediately after registration without verification step.

<img width="1910" height="1147" alt="image-20260304-145503" src="https://github.com/user-attachments/assets/738b9440-f290-487e-8e94-cf4978b2bdff" />
