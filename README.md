# passward-complexity
🔐 Enhancing Security with PowerShell: Password Complexity Check 🔐 
# PowerShell Password Complexity Checker

## Overview
This PowerShell script, `Test-PasswordComplexity`, evaluates the complexity of a user-provided password based on key security criteria. It helps enforce strong password policies by ensuring passwords meet minimum requirements for length, case variation, numeric inclusion, and special characters.

## Features
- **Length Check**: Ensures password is at least 8 characters long.
- **Uppercase and Lowercase Check**: Verifies inclusion of both uppercase and lowercase letters.
- **Numeric Check**: Checks for the presence of numbers.
- **Special Characters**: Looks for special characters to increase complexity.

## Usage
The script uses a loop to continuously check passwords until the user types "exit" to quit. It returns a score based on password complexity, where higher scores indicate stronger passwords.

### Example
To test a password, enter:
```powershell
Test-PasswordComplexity -password "YourPassword123!"
hello1234
c0mpl3xp@ssw@rd#2024
N3v3rgu3ssm3

