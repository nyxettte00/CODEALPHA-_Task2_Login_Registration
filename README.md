# Task 2: Login and Registration System (C++)

## Description
A console-based Login & Registration system that:
- Allows users to register with username and password
- Validates username (min 3 chars, alphanumeric + underscore)
- Validates password (min 4 characters)
- Checks for duplicate usernames
- Stores credentials in `users.txt` file
- Provides login verification with success/error messages

## How to Compile & Run
```bash
g++ login_system.cpp -o login
./login
```

## Features
- Registration with input validation
- Duplicate username detection
- Credentials stored in file (`users.txt`)
- Login authentication
- Clear success and error messages
- Menu-driven interface

## Note
Passwords are stored in plain text for educational purposes.
In real applications, always use proper password hashing.
