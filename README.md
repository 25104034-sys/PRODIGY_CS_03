# PRODIGY_CS_03 - Password Complexity Checker

## Overview

The **Password Complexity Checker** is a Python-based project that evaluates the strength of a password using common security standards. It checks whether the password meets essential requirements such as minimum length, uppercase letters, lowercase letters, numbers, and special characters, then provides an appropriate strength rating.

## Features

- Checks the minimum password length
- Detects uppercase letters (A-Z)
- Detects lowercase letters (a-z)
- Detects numeric digits (0-9)
- Detects special characters
- Displays password strength feedback
- Simple and easy-to-use interface

## Technologies Used

- Python 3
- Regular Expressions (`re` module)

## How It Works

The program evaluates the password based on the following criteria:

- Minimum length of **8 characters**
- Contains at least one uppercase letter
- Contains at least one lowercase letter
- Contains at least one numeric digit
- Contains at least one special character

Based on these checks, the password is classified as:

- Weak Password
- Medium Password
- Strong Password
- Very Strong Password

## Usage

1. Clone or download this repository.
2. Run the Python script.
3. Enter a password when prompted.
4. View the password strength displayed by the program.

## Example Outputs

### Example 1

**Input**
```
pass
```

**Output**
```
Password Strength: Weak Password
```

### Example 2

**Input**
```
python123
```

**Output**
```
Password Strength: Medium Password
```

### Example 3

**Input**
```
Welcome12
```

**Output**
```
Password Strength: Strong Password
```

## Learning Outcomes

- Understand password security principles
- Practice Python programming
- Learn Regular Expressions (`re` module)
- Implement input validation and conditional logic

