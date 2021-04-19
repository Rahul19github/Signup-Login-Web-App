# Signup-Login-Web-App

A simple Sign up / Login web app created using Django Framework in Python.

Database used to store the details is MySQL

Bootstrap4 was used as the front-end component

Along with the basic functionality few custom validators are also used like

for username field set the below validations

- it is mandatory
- username should begin with alphabet
- it should contains at least one number
- it should not contain special character
- max length allowed is 15 characters
- if any of the above validation fails, show error message to user

for password set the below validation

- it is mandatory
- it should contains at least one number and one alphabet
- minimum length should be 8 characters
- max length allowed is 15 characters
- username and password should not be the same
- if any of the above validation fails, show error message to user
