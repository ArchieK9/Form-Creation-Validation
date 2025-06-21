# Form-Creation-Validation

A simple client-side form validation project built with basic JavaScript. This project demonstrates how to validate user input for a registration form using fundamental string methods and conditional logic. It ensures users enter valid username, email, and password values before submission.

---

## Features

- Validates **Username**: must be at least 3 characters long.
- Validates **Email**: must include both `@` and `.` characters.
- Validates **Password**: must be at least 8 characters long.
- Displays clear error messages for invalid input.
- Shows success message upon valid submission.
- Prevents form submission if validations fail.
- All validation logic runs client-side using vanilla JavaScript.
- Feedback is displayed dynamically in a dedicated feedback section.

---

## Usage

1. Open the `index.html` file in a modern web browser.
2. Fill in the registration form fields (username, email, password).
3. Submit the form.
4. See instant feedback below the form about validation success or errors.

---

## Code Overview

- **DOMContentLoaded event** ensures the script runs only after the DOM is fully loaded.
- Uses `document.getElementById` to retrieve form and input elements.
- Applies `.trim()` to remove leading/trailing whitespace from input values.
- Uses a boolean flag `isValid` to track overall validation status.
- Collects error messages in an array `messages`.
- Checks input criteria and updates `isValid` and `messages` accordingly.
- Displays feedback messages dynamically in the feedback div.
- Prevents actual form submission for client-side validation demonstration.
