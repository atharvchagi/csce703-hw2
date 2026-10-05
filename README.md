# Juice Shop Mock Login Form

## Description
This is a basic HTML and JavaScript login form created for a web security assignment. It mimics the login page of the OWASP Juice Shop to demonstrate front-end validation and common web vulnerabilities.

## Features
- Client-side validation prevents empty submissions.
- Checks that the email contains an "@" symbol.
- Enforces a minimum password length of 8 characters.
- **Intentional Vulnerability:** The form contains a deliberate DOM-based Cross-Site Scripting (XSS) vulnerability for educational exploitation.

## How to Run
1. Download or clone this repository.
2. Open the `index.html` file directly in any modern web browser (Chrome, Firefox, Edge).
3. No server or backend setup is required.
