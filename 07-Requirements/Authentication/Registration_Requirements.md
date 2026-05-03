# Registration Requirements

## Username
- Must start with a letter
- Must be between 2–40 characters
- Must not contain spaces
- Must not allow inconsistent validation messages

## Email
- Must be valid format
- Must not accept invalid special characters
- Must be unique in the system
- Must accept uppercase and lowercase letters

## Password
- Must be between 8–30 characters
- Must contain:
  - At least one uppercase letter
  - At least one number
  - At least one special character
- Must reject weak passwords

## Confirm Password
- Must exist in the registration form
- Must match password field

## System Behavior
- Successful registration must redirect to Home page
- System must send verification email after registration
- System must redirect to “Finish Registration” flow (code verification step)
- System must not bypass verification step
