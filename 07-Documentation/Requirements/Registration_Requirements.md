# Registration Requirements

## Username
- Must start with a letter
- Must be between 2–40 characters
- Must not contain spaces
- Must be validated consistently (no duplicate/conflicting rules in messages)

## Email
- Must be valid format
- Must not accept invalid special characters
- Must be unique in the system
- Must be case-insensitive

## Password
- Must be between 8–30 characters
- Must contain:
  - At least one uppercase letter
  - At least one number
  - At least one special character
- Must reject weak passwords
- Must enforce both minimum and maximum length correctly

## Confirm Password
- Must exist in the form
- Must match the Password field

## System Behavior
- Successful registration must redirect to Home page
- System must send a verification email after registration
- System must not skip email verification step
