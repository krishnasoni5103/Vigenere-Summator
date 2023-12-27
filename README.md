# Vigenere-Summator
Explore the world of cryptography with this Python implementation of the Vigenere Cipher! This repository contains a simple yet effective script for encrypting text using the Vigenere Cipher algorithm.

Features:

Vigenere Cipher Implementation: Encrypt your text using the Vigenere Cipher, a classic polyalphabetic substitution cipher that adds an extra layer of security to your messages.

Interactive Usage: Easily encrypt your own text by providing input through the command line. Enter the text you want to encrypt and the keyword for a personalized encryption experience.

Dual Output: Witness the encrypted text along with a unique twist – a secondary cipher text generated based on the sum of the digits in the ASCII values of the encrypted characters.

How to Use:

Clone the repository to your local machine.
Run the script and follow the prompts to enter the text you want to encrypt and the keyword for encryption.
Explore the output, featuring both the standard Vigenere Cipher encrypted text and the intriguing secondary cipher text.
Contribution Guidelines:

Fork the repository, create a new branch, and contribute improvements, optimizations, or additional features.
Engage in discussions to share insights, suggestions, or ways to enhance the Vigenere Cipher implementation.
Example Usage:

python
Copy code
# Example usage
text = input("Enter the text you want to encrypt: ")
key = input("Enter the keyword: ")

encrypted_text, new_cipher_text = vigenere_cipher(text, key)

print("Original Text:", text)
print("Encrypted Text (Vigenere Cipher):", encrypted_text)
print("New Cipher Text (Secondary Cipher):", new_cipher_text)
Dive into the world of cryptography and explore the Vigenere Cipher with this Python implementation. Whether you're a cryptography enthusiast or a Python developer looking to understand encryption algorithms, this repository is your gateway to learning and contributing to the fascinating realm of secure communication. Happy encrypting! 🔐🐍






