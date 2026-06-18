# Authentication Web App

A simple, responsive web application for user authentication tasks, including logging in, registering new accounts, and resetting forgotten passwords.

## Project Objective

The objective of this project is to provide a clean and functional starter template for a user authentication system. It demonstrates basic HTML5 form structures, CSS3 styling for layouts and interactions, and inter-page navigation.

## Features

- **Home Page:** Navigation hub for all authentication actions.
- **Login:** Simple form for user authentication.
- **Registration:** form for new user account creation.
- **Forgot Password:** Interface for initiating password recovery via email.
- **Responsive Design:** Styled with CSS for a clean look across devices.

## Tech Stack

- **HTML5:** For structural markup.
- **CSS3:** For styling and layout.

## Steps to Recreate

Follow these steps to build this project from scratch:

1.  **Initialize the Project:**
    Create a new directory for your project and navigate into it.
    ```bash
    mkdir auth-webapp
    cd auth-webapp
    ```

2.  **Create the Home Page (`index.html`):**
    This page serves as the entry point with links to Login, Register, and Forgot Password.
    - Add a title and link the `styles.css` file.
    - Create a navigation list with links to `login.html`, `register.html`, and `forgot-password.html`.

3.  **Create the Login Page (`login.html`):**
    - Create a form with `email` and `password` inputs.
    - Add a "Login" button.
    - Include links to the "Forgot Password" and "Register" pages.

4.  **Create the Registration Page (`register.html`):**
    - Create a form with `Full Name` (text), `Email`, and `Password` inputs.
    - Add a "Register" button.
    - Include a link back to the "Login" page.

5.  **Create the Forgot Password Page (`forgot-password.html`):**
    - Create a form with an `Email` input.
    - Add a "Reset Password" button.
    - Include a link back to the "Login" page.

6.  **Apply Styling (`styles.css`):**
    - Define base styles for the `body` (font-family, background color, alignment).
    - Style the `form` containers (background, padding, border-radius, box-shadow).
    - Style `input` and `button` elements for consistent sizing and spacing.
    - Add hover effects for the buttons to improve user interaction.

7.  **Testing:**
    Open `index.html` in a web browser to verify navigation and form layouts.

## File Structure

```text
auth-webapp/
├── index.html
├── login.html
├── register.html
├── forgot-password.html
└── styles.css
```
