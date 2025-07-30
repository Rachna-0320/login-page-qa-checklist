# login-page-qa-checklist
QA test planning document for a basic login page.

# QA Test Checklist for Login Page — Phase 1


## Introduction

This document is a test checklist for a basic login page. It is part of the QA planning process that happens before any code is written. The goal is to make sure everything important for quality is considered and tested from the very beginning.


## Test Checklist for Login Page

- The username field should be clearly visible on the screen.
  This is important because users need to know where to type their username when logging in.

- The password field must be visible and placed near the username field.
  Users should be able to see both fields easily so they know where to enter their login information.

- The password should be hidden or masked while typing.
  This prevents others from seeing the password and helps keep it secure.

- The login button should be clickable.
  It should respond when clicked so the user can try to log in.

- If the login fails, an error message should appear.
  This helps the user understand that something went wrong, like incorrect username or password.

- A loading message or spinner should be shown while the login is processing.
  This lets the user know that the system is working and they should wait.

- If the login fails, the password field should be cleared automatically.
  This protects the user's password and makes it easier to re-enter it correctly.

- If the correct username and password are entered, the user should be logged in successfully.
  After logging in, they should be taken to the homepage or their account dashboard.

- The password field should always stay hidden and never display the password in plain text.
  This adds an extra layer of security, especially when others are nearby.

- There should be a “Forgot Password?” link on the page.
  When clicked, it should allow the user to reset their password by verifying their identity using email or phone, and then entering a new password after confirmation.


## Functional Rules (Basic Behavior)

Functional rules describe how the login page should behave when someone uses it. These rules help make sure that all the basic features, like entering details and clicking the login button, work properly before the page is actually built.

- The login page must have a username field and a password field.

- Both input fields should accept user input through the keyboard.

- The login button should only be clickable when both fields are filled.

- When the login button is clicked, the system should check the entered credentials.

- If the credentials are correct, the user should be redirected to their dashboard or homepage.

- If the credentials are incorrect, an error message must be shown.

- The password must be hidden (masked) as the user types.

- A “Forgot Password?” link must be available and should start the password reset process.

- If the login fails, the password field should be cleared.

- The login process should show a loading spinner or message while verifying the credentials.


## UI/UX and Security Rules

These rules focus on the appearance, usability, and security of the login page. They help make sure the page is easy to use and that users' personal information is protected.


## UI/UX Rules (Appearance & Usability)

- The username and password fields should have clear labels so users know where to enter their information.

- The layout of the login page should be clean and simple, without too much clutter.

- The login button should be easy to find and placed where users naturally expect it.

- Fonts and colors should be easy to read and accessible for all users, including those with visual challenges.

- The login page should work properly on both desktop and mobile screens.



## Security Rules

- The password field should always hide the characters by showing dots or asterisks instead of plain text.

- The browser should not automatically save or store passwords unless the user chooses to.

- If the login fails, the error message should be general (e.g., “Login failed”) and not give away whether the username or password was wrong.

- After too many failed login attempts, the system should either temporarily lock the account or require a CAPTCHA to prevent abuse.

- The login page must use HTTPS so that all user data is encrypted and secure during transmission.


## Summary

This test planning document covers all the key points needed to check the quality of a basic login page before it's built. It includes: 

- A checklist of things to test,
- Functional rules for how the page should behave,
- Additional rules for user experience and security.
By planning these details ahead of time, we can make sure the login page works properly, is easy to use, and keeps user information safe. This preparation helps avoid problems later and supports developers in building a better, more reliable product.

