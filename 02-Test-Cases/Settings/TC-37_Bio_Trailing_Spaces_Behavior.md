# TC-37 - Bio field handles trailing spaces correctly

## Steps
1. Log in to the application with valid credentials
2. Navigate to the Settings page
3. Enter a text with trailing spaces in the "Bio" field (e.g., "texto ")
4. Click on "Update Settings"

## Expected Result
The system handles trailing spaces according to its specification:
- Either trims the trailing spaces before saving
- Or preserves them if explicitly allowed
