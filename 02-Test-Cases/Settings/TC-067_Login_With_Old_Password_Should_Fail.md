# TC-067 - User cannot log in using the old password after password update

## Steps
1. Log in to the application with valid credentials
2. Navigate to the Settings page
3. Update the "New Password" field with a valid password that meets complexity rules
4. Click on "Update Settings"
5. Log out from the application
6. Attempt to log in using the same email and the old password

## Expected Result
Login is rejected when using the old password
