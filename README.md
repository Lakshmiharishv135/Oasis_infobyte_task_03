# Password Generator

## Overview
This is a Python-based **Password Generator** that creates secure and random passwords of a specified length. The password includes at least one uppercase letter, one lowercase letter, one digit, and one special character to ensure strong security. It’s a simple yet effective tool for generating robust passwords.

## Features
- **Secure Password Generation**: Ensures that each password includes:
  - At least one uppercase letter.
  - At least one lowercase letter.
  - At least one special character.
  - At least one digit.
- **Randomized**: Password characters are randomly selected and shuffled for added security.
- **Validation**: Ensures that the password length is at least 4 characters.
  
## Requirements
- Python 3.x

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/password-generator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd password-generator
   ```
3. Run the Python script:
   ```bash
   python password_generator.py
   ```

## Usage
1. The program will prompt you to enter the desired password length.
2. Input the length (minimum 4 characters).
3. The program will generate and display a secure random password.

## Example
```bash
Enter the password length: 8
Suggested password is: G&k6@B2p
```

## Code Explanation
- **Libraries**:
  - `random`: Used to randomly select characters.
  - `sys`: Used to exit the program if the length is less than 4.
  - `string`: Provides a list of characters like uppercase, lowercase, digits, and punctuation.
  
- **Function**: 
  - `gen_password(length)`: Generates a random password based on the given length.
    - Ensures at least one character from uppercase, lowercase, special characters, and digits.
    - Additional characters are randomly selected from all available character sets.
    - Shuffles the password to randomize the character order.
