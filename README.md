# PRODIGY_CS_01

# Caesar Cipher Encoder/Decoder

This repository contains a simple Python implementation of the Caesar cipher, a classic encryption technique used for encoding and decoding text. The script allows users to shift characters in the alphabet by a specified number of positions, supporting both encoding (encryption) and decoding (decryption) processes.

## Features

- **Encoding and Decoding**: Easily switch between encoding (encrypting) and decoding (decrypting) text.
- **Flexible Shift Amount**: Input any integer shift value to customize the encoding/decoding process.
- **Alphabet Handling**: Automatically wraps shifts within the alphabet range (supports lowercase English letters).
- **User-Friendly Interface**: Interactive prompts guide users through the process, ensuring smooth usage.

## Usage

1. **Run the Script**: Execute the script using a Python interpreter.
2. **Select Action**: Choose to encode (encrypt) or decode (decrypt) the text.
3. **Enter Text**: Provide the text you want to process.
4. **Specify Shift**: Input the number of positions to shift the characters.
5. **View Result**: The script outputs the processed text.
6. **Repeat or Exit**: Optionally repeat the process or exit the script.

## Example

```sh
$ python caesar_cipher.py
Enter 'encode' to encrypt or 'decode' to decrypt: encode
Enter text: hello
Enter shift number: 3

Result: khoor

Do you want to go again? (y/n): n
Exiting.
