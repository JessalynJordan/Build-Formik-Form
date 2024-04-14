
# Formik Login Form 

## Overview
This repository contains a simple login form built using React and Formik. The form includes input fields for email and password, along with validation for each field. This README provides instructions on how to set up and run the project.

## Getting Started
To run this project locally, follow these steps:

1. Clone this repository to your local machine.
    ` git clone <repository_url> `
2. Navigate to the project directory.
   ` cd <project_directory> `
3. Install dependencies.
   ` npm install `
4. Start the development server.
   ` npm start `
5. Open your browser and go to http://localhost:3000 to view the login form.
   
## Usage
The login form consists of two input fields (Email and Password) and a submit button. Here's how to use it:

  * Email Field: Enter your email address.
  * Password Field: Enter your password.
  * Submit Button: Click this button to submit the form.
    
## Validation
The form validates the input fields according to the following rules:

* Email Field:
    * Required: If the email field is empty, the error message "field required" is displayed.
    * Format: If the email format is invalid (not in the format of an email address), the error message "username should be an email" is displayed.

* Password Field:
    * Required: If the password field is empty, the error message "field required" is displayed.
      
## Implementation Details
The form is implemented using Formik, a library that simplifies form management in React. Here's a brief overview of the key components:

* useFormik Hook: Used to initialize Formik and define the form's initial values, submission handler, and validation function.
* Input Fields: Two input fields are provided for email and password, with corresponding ` id `, ` name `, ` onChange `, and ` value ` attributes.
* Error Messages: Error messages are displayed below each input field if validation fails. These messages are conditionally rendered based on the presence of errors and whether the field has been touched.
* Submit Button: Clicking the submit button triggers form submission, which in turn invokes the onSubmit function defined in the useFormik hook.
  
## Customization
Feel free to customize the form as needed for your specific use case. You can modify the input fields, validation rules, error messages, and styling to suit your requirements.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as needed.


