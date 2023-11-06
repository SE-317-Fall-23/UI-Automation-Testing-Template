# UI Automation Testing with Playwright Assignment

## Objective

The primary objective of this assignment is to familiarize you with UI automation testing using Playwright, focusing on testing the user registration form and related functionality.

In this assignment, you will be writing Playwright tests for the user registration form and its associated UI components. You will copy the code for the backend and UI from the previous assignments.
- In the UI unit testing assginment, the code submitted the form to a mock server. You have to change that to call the Java backend.
- You have to write a second HTML page that displays the user information. You have to write a Playwright test to verify that the user information is displayed correctly.


## User Registration Form

The user registration form comprises the following fields:

1. **Username**: A unique username for the user (Validation required).
2. **First Name**: User's first name (Validation required).
3. **Last Name**: User's last name (Validation required).
4. **Address**: Consisting of:
    - **Street**: User's street address (Validation required).
    - **Street2**: Additional street information (optional).
    - **City**: User's city (Validation required).
    - **State**: User's state (Validation required).
    - **Zip Code**: User's zip code (Validation required).
5. **Email Address**: User's email address (Validation required and must be unique across users).
6. **Date of Birth**: User's date of birth (Validation required).


## Requirements

1. Write Playwright test scripts to automate the following aspects of the user registration form:
    a. Verify the correctness of UI components, including labels and input acceptance.
    b. Ensure input validation by testing various scenarios for each field, including username, first name, last name, email address, and address details.
    c. Automate tests for submitting the user registration form to the server.
    d. Handle various error scenarios from the server (e.g., invalid address, duplicate username) and verify that appropriate error messages are displayed to the user.
    e. Test form behavior with both valid and invalid data.

2. The tests should interact with the user registration form on the web page and validate the behavior. Ensure that validation and error handling are properly implemented.
3. You can refer to the provided code as a starting point for your tests and make necessary modifications.
4. Your test code should be well-organized and follow the arrange, act, assert pattern.

