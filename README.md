# Php7-user-registration
Latest PHP 7+ example for creating user registration and login with sessions 

# Example code for user registration in PHP
In this example, I have created user registration in PHP with the login script.

On a landing page, it shows a login form with a signup link. The registered user can enter their login details with the login form. Once done, he can get into the dashboard after authentication.

If the user does not have an account, then he can click the signup option to create a new account.

The user registration form requests username, email, password from the user. On submission, PHP code allows registration if the email does not already exist.

This example code has client-side validation for validating the entered user details. And also, it includes contains the server-side uniqueness test. The user email is the base to check uniqueness before adding the users to the MySQL database.


#Create user registration and login form

I have created three HTML view login form, registration form and the dashboard for this code.

Below HMTL code is for displaying the login form to the user. In this form, it has two inputs to allow the user to enter their username and password.

Without these details, a validation code will not allow the login to proceed. The login form tag’s on-click attribute is with loginValidation(). This function contains the login form validation script.

On submitting this login form, the PHP code will validate the user. If the users clear the authentication, then it will redirect him to the dashboard.

If the user attempts to log in with the wrong data, then the code will display a login error message in the login form. If you want to limit the failed login attempts, the linked article has an example of that.

#Get in touch with me for more details
akmashish15@gmail.com
http://ashishk.me 