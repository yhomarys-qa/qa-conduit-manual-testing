# TC-019 - Username comparison is case-insensitive

## Steps
1. Log in to the application with valid credentials
2. Ensure an existing username is registered (e.g., "TestUser")
3. Navigate to the Settings page
4. Enter the same username using different letter casing (e.g., "testuser" or "TESTUSER")
5. Click on "Update Settings"

## Expected Result
The system treats the username as already existing regardless of letter case
A validation error message is displayed indicating that the username is already in use
