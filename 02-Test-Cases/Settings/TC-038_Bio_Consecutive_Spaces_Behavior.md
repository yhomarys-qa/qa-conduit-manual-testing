# TC-038 - Bio field handles consecutive spaces correctly

## Steps
1. Log in to the application with valid credentials
2. Navigate to the Settings page
3. Enter a text with multiple consecutive spaces in the "Bio" field (e.g., "texto   com   espaços")
4. Click on "Update Settings"

## Expected Result
The system handles consecutive spaces according to its specification:
- Either preserves the spaces exactly as entered
- Or normalizes them into a single space per separation
