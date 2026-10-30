Project Overview

Password Security Checker is a Python-based tool that evaluates the strength of a password based on several security criteria.

The program analyses a password entered by the user and checks its length, character composition, use of common passwords, and repeated characters.

It uses a scoring system to classify passwords into three categories: WEAK, MEDIUM, or STRONG.

The project was developed to practise Python programming while exploring fundamental cybersecurity concepts related to password security and authentication.

Features

Password Length Check: Checks whether the password meets the minimum length requirement of 8 characters.

Uppercase Detection: Checks whether the password contains uppercase letters.

Lowercase Detection: Checks whether the password contains lowercase letters.

Number Detection: Identifies whether the password contains numerical digits.

Special Character Detection: Checks for symbols such as !, @, #, $, %, and &.

Common Password Detection: Compares the entered password against a predefined list of commonly used passwords.

Repeated Character Detection: Identifies three or more consecutive identical characters.

Password Scoring: Assigns points based on the password's security characteristics.

Strength Classification: Categorises the password as WEAK, MEDIUM, or STRONG.

Technologies Used

Python 3 – Main programming language.

Built-in Python Functions – Used for string analysis and password validation.

How It Works

The program follows these steps:

Prompts the user to enter a password.

Calculates the password length.

Checks for uppercase and lowercase letters.

Checks for numerical digits.

Identifies special characters.

Compares the password against a predefined list of common passwords.

Checks for three consecutive repeated characters.

Calculates a security score based on the results.

Assigns a password strength rating.
