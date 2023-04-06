# Form Validation App
This is a form validation app that uses a validation library to check if input fields meet certain criteria. The validation library is imported from dmc-validation-lib and contains functions for validating different types of data such as email addresses, phone numbers, passwords, credit card numbers, and empty fields. The app also includes a range validation function to check if a number falls within a specified range.

## Getting Started
To get started with this app, simply clone this repository to your local machine and open the index.html file in your browser.

## How to Use
The app includes several input fields that need to be validated. Each input field has two corresponding status elements that indicate whether the input is valid or not. The status elements are hidden by default and will only be displayed if the input is invalid.

To validate an input field, simply type in the desired value and the validation function will be triggered automatically. If the input is valid, the green checkmark status element will be displayed. If the input is invalid, the red cross status element will be displayed instead.

## Validation Functions
The following validation functions are included in this app:

**notEmptyValidation**: checks if an input field is empty.
**isComplexPassword**: checks if a password meets complexity requirements (at least 8 characters, includes uppercase and lowercase letters, and includes at least one number and one special character).
**isValidPhoneNumber**: checks if a phone number is valid (must be in the format XXX-XXX-XXXX).
**isValidEmail**: checks if an email address is valid (must be in the format example@example.com).
**isValidCreditCard**: checks if a credit card number is valid (must be a valid Visa, Mastercard, or American Express card number).
**isInRange**: checks if a number falls within a specified range.

## Range Validation
The range validation function allows you to check if a number falls within a specified range. To use this function, simply enter the minimum and maximum values of the range in the corresponding input fields. Then, enter the number you want to check in the "Value to Check" input field. The status elements will display whether the value falls within the range or not.

## Technologies Used
HTML
CSS
JavaScript
dmc-validation-lib

## Contributing
Contributions to this project are welcome. To contribute, simply fork this repository, make your changes, and submit a pull request.