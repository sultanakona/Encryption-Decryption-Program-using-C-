# Encryption & Decryption Program

Secure your important information like passwords, IDs, or personal messages using various classical and modern ciphers.

## Authors

| Name                         | ID       | Email                       | Ciphers                                                      |
|-------------------------------|----------|----------------------------|-------------------------------------------------------------|
| Mohammed Atef Abd EL-Kader   | 20231143 | mohamed45452020@gmail.com  | Route Cipher, Vigenere Cipher, Polybius Square Cipher, Morse Cipher |
| Esraa Emary Abd El-Salam     | 20230054 | esraaemary33@gmail.com     | Atbash Cipher, Baconian Cipher, Simple Substitution Cipher, Morse Decipher |
| Aly El-Deen Yasser Aly       | 20230054 | aibakgaming747@gmail.com   | Affine Cipher, XOR Cipher, Rail Fence Cipher               |

## Project Description

This C++ program allows users to encrypt and decrypt text using a variety of ciphers. It is designed to secure sensitive information like passwords, IDs, or personal messages and make them difficult for unauthorized users to access.

The program provides a simple menu-driven interface, where users can select a cipher, choose between encryption or decryption, and input the text and keys as required.

## Features

- Supports 10 different ciphers:
  - Affine Cipher
  - Route Cipher
  - Atbash Cipher
  - Vigenere Cipher
  - Baconian Cipher
  - Simple Substitution Cipher
  - Polybius Square Cipher
  - Morse Cipher
  - XOR Cipher
  - Rail-Fence Cipher
- Easy-to-use menu interface
- Loop until the user decides to exit the program
- Works for both encryption and decryption

## How to Run
##Compile the program
g++ main.cpp -o encrypt_decrypt


Make sure all header files (*.h) are included in the source/ folder.

##Run the program
./encrypt_decrypt


Follow the on-screen menu to select a cipher, encrypt/decrypt text, or exit.

##Sample Output
# ===== Welcome To Encryption and Decryption Program ===== #

Which type of Cipher do you want?
 [1] Affine Cipher.
 
 [2] Route Cipher.
 
 [3] Atbash Cipher.
 
 [4] Vigenere Cipher.
 [5] Baconian Cipher.
 [6] Simple Substitution Cipher.
 [7] Polybius Square Cipher.
 [8] Morse Cipher.
 [9] XOR Cipher.
 [10] Rail-Fence Cipher.
 [11] Exit Program.
Enter Your Choice: 1

You selected Affine Cipher.
Do you want to:
[1] Encrypt
[2] Decrypt
Enter your choice: 1
Enter the plaintext: HELLO
Enter key values (a and b): 5 8
Encrypted text: RCLLA


##Folder Structure
Encryption-Decryption-Program/
│
├─ main.cpp
├─ README.md
├─ source/
│   ├─ Affine_Cipher.h
│   ├─ Route_Cipher.h
│   ├─ Atbash_Cipher.h
│   ├─ Vigenere_Cipher.h
│   ├─ Baconian_Cipher.h
│   ├─ Simple_Substitution_Cipher.h
│   ├─ Polybius_Square_Cipher.h
│   ├─ Morse_Cipher.h
│   ├─ XOR_Cipher.h
│   └─ Rail-Fence_Cipher.h


