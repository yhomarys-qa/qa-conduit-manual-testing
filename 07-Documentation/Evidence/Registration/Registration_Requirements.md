# Registration Requirements

## Username
- Must start with a letter
- Must be between 2–40 characters
- Must not contain spaces
- Must be unique
- Must not allow invalid special characters in structured rules
- Error messages must be clear and consistent (no duplicates)

## Email
- Must follow valid email format
- Must be case-insensitive
- Must not contain invalid special characters in local part
- Must be unique in the system

## Password
- Must be between 8–30 characters
- Must contain at least:
  - 1 uppercase letter
  - 1 number
  - 1 special character
- Must reject weak passwords
- Must validate min/max length correctly

## Confirm Password
- Must match Password field
- Field must be present in registration form

## System Behavior
- Successful registration redirects to Home
- Verification email must be sent after registration
- System must not skip email verification flow
