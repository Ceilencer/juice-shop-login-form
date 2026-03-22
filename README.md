# Juice Shop Login Form

A basic HTML/JavaScript login form created for a web security assignment.

## How to Run

1. Download or clone the repository
2. Open `login.html` in any web browser
3. No server or install required

## Features

- Email and password input fields
- Blocks submission if either field is empty
- Validates email contains "@"
- Validates password is at least 8 characters
- Displays red error messages for failed checks

## Files

- `login.html` — the login form with all HTML, JS, and validation

## Security Notes

- Client-side validation is for user experience only
- A real server would re-validate all inputs server-side
- Passwords should be hashed with bcrypt before storage
- Database queries should use parameterized statements to prevent SQL injection
