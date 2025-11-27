Description

This project is a Python program that evaluates the strength of a user-entered password and generates a strong, secure password. It helps users understand whether their password is weak, medium, or strong based on several security criteria.

Features

Password Strength Checker

Evaluates password based on length, uppercase letters, lowercase letters, digits, and special characters.

Categorizes password as Weak, Medium, or Strong.

Strong Password Generator

Generates a 12-character secure password using letters, digits, and punctuation.

Uses Python's random module for randomness.

Technologies Used

Python 3

string module

re (regular expressions)

random module

How It Works
Function: check_strength(password)

This function checks the password against five criteria:

Length of at least 8 characters

Contains uppercase letters

Contains lowercase letters

Contains digits

Contains special characters

A score is calculated, and the password is labeled as Weak, Medium, or Strong.

Function: generate_strong_password()


Future Improvements

Add a graphical interface

Add password entropy calculation

Display detailed feedback for each security rule

License

This project is open-source and free to use.
