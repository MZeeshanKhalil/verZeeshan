B. Update the Customer Registration Form
Update the existing customer sign-up form to include the following two fields:
Field
Input Type
Required
Format
Date of Birth (DOB)
Date or appropriately formatted text input
Yes
DD-MM-YYYY
Phone Number
Text input
Yes
(999) 999-9999
The fields must be clearly labelled and displayed on the registration page.
Example inputs:
● DOB: 28-10-2026
● Phone Number: (123) 456-7890
The frontend must provide appropriate validation messages when the user leaves a field empty or enters an invalid value.
C. Date of Birth Validation
Implement the following validations:
1. DOB is a required field.
2. The accepted display and input format must be DD-MM-YYYY.
3. Validate that the entered date is a real calendar date. For example, 31-02-2026 must be rejected.
4. Ensure the submitted DOB is converted to the appropriate date representation before saving it to the customer profile.
D. Phone Number Validation
Implement the following validations:
1. Phone Number is a required field.
2. The accepted format must be (999) 999-9999.
3. Validate the complete phone number, not just its length.
4. Reject invalid inputs such as:
○ 1234567890
○ (123)456-7890
○ (123) 456-789
○ (ABC) 456-7890