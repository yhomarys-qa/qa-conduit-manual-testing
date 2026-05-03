# Login Requirements

## Authentication Access
- The system must allow users to log in using Email or Username
- Email input must be case-insensitive
- Username must be accepted when valid

## Input Validation
- Email/Username field must accept valid formats only
- Password field is required
- System must validate credentials before login

## UI Requirements
- The field must display a placeholder indicating "Email or Username"
- "Forgot your password?" link must be visible on login page
- "Send temporary password" option must be available when login fails

## Error Handling
- Invalid credentials must show a consistent error message
- System must not allow access with incorrect password

## Session Management
- Authenticated users must be redirected away from login page
- Login page must not be accessible when user is already authenticated
