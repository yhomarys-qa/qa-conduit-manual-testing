# 🔥 Smoke Test Suite – Conduit (RealWorld App)

## 📌 Objective

The purpose of this Smoke Test Suite is to quickly verify that the most critical functionalities of the application are working correctly before executing full regression testing.

---

## 🎯 Scope

This smoke suite covers the core system flows:

- Authentication
- Article Creation
- Home Page
- User Settings

---

## 🧪 Selected Smoke Test Cases

### 🔐 Authentication

- TC-003_Login_Valid_Email.md  
- TC-004_Login_Valid_Username.md  

---

### 📝 Registration

- TC-037_Successful_Registration_With_Valid_Data.md  

---

### 📰 Articles

- TC-002_Access_New_Article_Page_Without_Authentication.md *(expected redirect/block)*  
- (Login required) Create article with valid data *(from your New Article suite)*  

---

### 🏠 Home

- TC-004_Feed_Tabs_Visible_for_Logged_User.md  
- TC-008_Feed_Global_Shows_All_Articles.md  

---

### ⚙️ Settings

- TC-050_Update_Settings_With_Valid_Data.md  

---

## 🚪 Entry Criteria

- Application is accessible  
- User can access login/registration page  
- Test environment is stable  

---

## 🚪 Exit Criteria

- All smoke test cases executed  
- No critical functionality failures  
- Core system flows are working  

---

## 📌 Notes

Smoke testing focuses only on verifying that the application is stable enough for deeper testing (Regression Testing).

It does not include validations, edge cases, or negative scenarios.
