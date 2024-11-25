# Password Generator Script

## Overview
This script generates a secure, random password of a user-defined length. It utilizes Python's random module and includes a mix of uppercase letters, lowercase letters, digits, and special characters.

## Features
Random Password Generation: Generates a password with cryptographically secure randomness.

Customizable Length: Allows users to specify the desired password length.

Character Diversity: Includes uppercase letters, lowercase letters, numbers, and special characters for strong passwords.

## How to Use
Ensure Python 3.x is installed on your system.

Save the script as password_generator.py.

Run the script using the command "python password_generator.py"

Enter the desired password length when prompted.

The script will output a randomly generated password.

## Code Structure
### Function:
generate_password(length: int): Generates a random password of the specified length using a mix of characters from:

Uppercase (A-Z)

Lowercase (a-z)

Digits (0-9)

Special characters (e.g., !@#$%^&*).

### Example Usage:
Prompts the user to input the desired password length. Calls generate_password and displays the generated password.
