# New Article Requirements

## Article Creation Access
- Authenticated users must be able to create new articles
- The system must restrict article creation to logged-in users only

## Required Fields
- Title is required
- Description is required
- Body is required

## Validation Rules
- Title must be between 2–40 characters
- Title must not be empty
- System must validate all required fields before submission
- Invalid or missing fields must prevent article creation

## Tags
- Tags are optional
- Users must be able to add multiple tags
- Duplicate tags must not be allowed

## System Behavior
- Article must be successfully published after submission
- After creation, the article must appear in Home feed
- System must not create incomplete articles

## Navigation
- After successful creation, user must be redirected to the article page or Home feed
