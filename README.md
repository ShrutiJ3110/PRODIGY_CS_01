# Caesar Cipher Program

This program **encrypts** and **decrypts** text using the **Caesar Cipher algorithm**, a simple substitution cipher that shifts characters in a message by a specified amount.

## Features

- **Encrypt Messages**: Converts plaintext into encrypted text by shifting characters.
- **Decrypt Messages**: Converts encrypted text back into the original message.
- **Handles uppercase and lowercase letters**.
- **Ignores non-alphabetic characters** (punctuation, numbers, spaces remain unchanged).

## How It Works

1. **Input a Message**: Provide the text to be encrypted or decrypted.
2. **Choose a Shift Value**: Enter an integer to define the shift amount.
3. **Select Mode**: Choose `encrypt` to encode or `decrypt` to decode the message.

## Example Usage

### Encrypting a Message

**Input:**
- Message: `Hello, World!`
- Shift: `3`
- Mode: `encrypt`

**Output:**
- Encrypted Message: `Khoor, Zruog!`

### Decrypting a Message

**Input:**
- Encrypted Message: `Khoor, Zruog!`
- Shift: `3`
- Mode: `decrypt`

**Output:**
- Decrypted Message: `Hello, World!`

## Running the Program

1. Save the program code in a file named `caesar_cipher.py`.
2. Run the script in a Python environment:
   ```bash
   python caesar_cipher.py
3.Follow the on-screen prompts to encrypt or decrypt messages.

Follow the on-screen prompts to encrypt or decrypt messages.
Requirements
Python 3.x is required to run this program.
Program Structure
caesar_cipher(): Performs the encryption or decryption logic.
get_input(): Collects user input for the message, shift value, and mode.
main(): The entry point of the program, allowing users to perform multiple operations.
Contributions
Feel free to fork this repository and suggest improvements! You can also open issues to report bugs or suggest new features.

### Explanation:
- The **"Running the Program"**, **"Requirements"**, **"Program Structure"**, and **"Contributions"** sections are formatted as headings using `##` for proper visibility.
- Important terms like Python version, function names (`caesar_cipher()`, `get_input()`, `main()`) are **bolded**.
- Code and commands are placed inside triple backticks to ensure they're displayed correctly in a formatted manner.

This ensures that everything you mentioned is clearly visible and properly formatted in your **README.md** file.


