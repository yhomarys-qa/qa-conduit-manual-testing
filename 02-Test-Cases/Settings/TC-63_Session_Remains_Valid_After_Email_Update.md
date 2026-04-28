# TC-63 - User session remains active after updating email address

## Steps
1. Log in to the application with valid credentials
2. Navigate to the Settings page
3. Update the "Email" field with a valid new email address
4. Click on "Update Settings"
5. Continue using the application without re-authentication
6. Attempt to access authenticated areas (e.g., profile or settings page)

## Expected Result
The user remains authenticated after updating the email
