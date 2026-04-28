# TC-36 - Bio field handles leading spaces correctly

## Steps
1. Log in to the application with valid credentials
2. Navigate to the Settings page
3. Enter a text with leading spaces in the "Bio" field (e.g., " texto")
4. Click on "Update Settings"

## Expected Result
The system handles leading spaces according to its specification:
- Either trims the leading spaces and saves the cleaned text
- Or preserves the spaces if allowed by the system design
