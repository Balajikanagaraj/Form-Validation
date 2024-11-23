# Form Validation Project

This **Form Validation Project** demonstrates a simple yet effective approach to validating user inputs in a web form. The project uses **HTML**, **CSS**, and **jQuery** to create a functional and interactive form with validation features. 

## Code Explanation

### Structure
- **HTML**: Defines the structure of the form with fields for Email, Password, Confirm Password, and Phone Number. A "Submit" button is included to trigger validation.
- **CSS**: Provides styling for input fields, error messages, and the overall layout. Input fields are highlighted when focused, and feedback messages are styled for clarity.
- **JavaScript**: Handles the validation logic, feedback, and page behavior using **jQuery**.

### Functionality
1. **Field Validation**:
   - Email: Validates that the input follows a standard email format.
   - Password: Ensures the password and confirm password fields match.
   - Phone Number: Checks that the input contains exactly 10 digits.

2. **User Feedback**:
   - Displays error messages if any validation criteria are not met.
   - Shows a success message when the form is completed correctly.
   - Highlights input fields with a black border and changes text color when focused.

3. **Form Submission**:
   - If validation fails, error messages are displayed, and the form remains unsubmitted.
   - If validation succeeds, a success message is displayed, and the page refreshes after 2 seconds.

4. **Interactive Behavior**:
   - Input fields dynamically change appearance when focused or blurred.
   - Error messages update in real-time to guide the user.

### Usage
- Fill in all fields with valid data:
  - Example: Email should follow `user@example.com`, Phone Number should be 10 digits, and Password fields must match.
- Click the "Submit" button to validate inputs.
- Observe real-time feedback and correction messages.

This project demonstrates how to handle form validation effectively, providing a smooth and user-friendly experience.
