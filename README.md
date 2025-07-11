# Password Checker and Generator

This Python script helps you check whether a password is commonly used and evaluates its strength. It also suggests strong passwords if yours is weak.

---

## Features

✅ Checks if a password exists in a list of common passwords  
✅ Calculates password strength based on:
- Length (≥ 8 characters)
- Uppercase letters
- Lowercase letters
- Digits
- Special characters

✅ Provides feedback if your password is weak or moderate  
✅ Generates random strong passwords

---

## Requirements

- Python 3.x

The script uses only standard Python libraries:
- `re`
- `string`
- `random`

---

## Usage

1. **Create a file named** `common_passwords.txt`  
   - Put one common password per line.  
   - Example:
     ```
     password
     123456
     qwerty
     letmein
     ```

2. **Run the script**

```bash
python your_script_name.py
