# TC-014 - Username Case Insensitive Validation

## Steps
1. Open the Conduit application
2. Navigate to the Sign up page
3. Register a new user with a valid Username (e.g., "TestUser"), Email, Password, and Confirm Password
4. Complete the registration successfully
5. Navigate again to the Sign up page
6. Attempt to register a new user using the same Username with different casing (e.g., "testuser" or "TESTUSER")
7. Click on the "Sign up" button

## Expected Result
The system should treat Username as case-insensitive.
A validation message should be displayed indicating that the Username is already in use.
The user should not be able to create a duplicate account with different letter casing.
