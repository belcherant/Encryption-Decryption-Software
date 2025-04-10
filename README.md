Encrypt and Decrypt Tool
A simple web-based application that allows users to encrypt and decrypt 4-digit numbers using a basic cryptographic algorithm.

Features
Encryption: Takes a 4-digit input and applies a mathematical transformation to encrypt it.

Decryption: Reverses the encryption process to retrieve the original number.

Interactive UI: Clean, minimalist interface with a single button to trigger the program.

How It Works
Encryption Process:

Each digit is modified using the formula: (digit + 7) % 10

The digits are then rearranged in the order: digit3, digit4, digit1, digit2

Decryption Process:

Each digit is modified using the formula: (digit - 7 + 10) % 10

The digits are rearranged back to their original order: digit3, digit4, digit1, digit2

Usage
Click the "Click to Run Program" button

For encryption:

Enter a 4-digit number when prompted

The encrypted result will be displayed

For decryption:

Enter a 4-digit encrypted number when prompted

The decrypted original number will be displayed

Technical Details
Built with HTML, CSS, and JavaScript

Uses prompt() for user input

Simple mathematical operations for encryption/decryption

Input validation ensures only 4-digit numbers are processed

Limitations
Only works with 4-digit numbers

Basic encryption not suitable for secure applications

Requires browser JavaScript execution
