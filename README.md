**Caesar Cipher Program**
This program encrypts and decrypts text using the Caesar Cipher algorithm, a simple substitution cipher that shifts characters in a message by a specified amount.

**Features**
1.Encrypt Messages: Converts plaintext into encrypted text by shifting characters.
2.Decrypt Messages: Converts encrypted text back into the original message.
3.Handles uppercase and lowercase letters.
4.Ignores non-alphabetic characters (punctuation, numbers, spaces remain unchanged).

**How It Works**
1.Input a Message: Provide the text to be encrypted or decrypted.
2.Choose a Shift Value: Enter an integer to define the shift amount.
3.Select Mode: Choose encrypt to encode or decrypt to decode the message.

**Example Usage**
Input:-
Message: Hello, World!
Shift: 3
Mode: encrypt
Output:-
Encrypted Message: Khoor, Zruog!

**Decrypting:**
If the encrypted message Khoor, Zruog! is entered with the same shift value 3 and mode decrypt, the output will be the original message:
Decrypted Message: Hello, World!

**Running the Program**
1.Save the program code in a file named caesar_cipher.py.
2.Run the script in a Python environment:
   python caesar_cipher.py
3.Follow the on-screen prompts to encrypt or decrypt messages.

**Requirements**
Python 3.x is required to run this program.

**Program Structure**
1.caesar_cipher(): Performs the encryption or decryption logic.
2.get_input(): Collects user input for the message, shift value, and mode.
3.main(): The entry point of the program, allowing users to perform multiple operations.

**Contributions**
Feel free to fork this repository and suggest improvements!

