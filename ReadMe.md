Caesar Cipher Program
This program encrypts and decrypts text using the Caesar Cipher algorithm, a simple substitution cipher that shifts the characters in a message by a specified amount.

Features
Encrypt messages: Converts plaintext into encrypted text by shifting characters.
Decrypt messages: Converts encrypted text back into the original message.
Handles uppercase and lowercase letters.
Ignores non-alphabetic characters (punctuation, numbers, spaces remain unchanged).
How It Works
Input a message: Provide the text to be encrypted or decrypted.
Choose a shift value: Enter an integer to define the shift amount.
Select mode: Choose encrypt to encode or decrypt to decode the message.
Example Usage
Input
Message: Hello, World!
Shift: 3
Mode: encrypt
Output
Encrypted Message: Khoor, Zruog!
Decrypting
If the encrypted message Khoor, Zruog! is entered with the same shift value 3 and mode decrypt, the output will be the original message:

Decrypted Message: Hello, World!
Running the Program
Save the program code in a file named caesar_cipher.py.
Run the script in a Python environment:
bash
Copy code
python caesar_cipher.py
Follow the on-screen prompts to encrypt or decrypt messages.
Requirements
Python 3.x is required to run this program.
Program Structure
caesar_cipher(): Performs the encryption or decryption logic.
get_input(): Collects user input for the message, shift value, and mode.
main(): The entry point of the program, allowing users to perform multiple operations.
Contributions
Feel free to fork this repository and suggest improvements!