# 🔐 Caesar Cipher Project

## 1. Introduction & Explanation
The **Caesar Cipher** is one of the simplest and most widely known encryption techniques. It works by shifting each letter in the plaintext by a fixed number of positions down the alphabet.

- For example, with a shift of `3`:
  - `A → D`
  - `B → E`
  - `C → F`
  - ...
  - `X → A`
  - `Y → B`
  - `Z → C`

So, the word **HELLO** becomes **KHOOR** when encrypted with a shift of `3`.

This project provides a Python implementation of the Caesar Cipher that allows you to **encrypt** and **decrypt** messages easily.

---

## 2. Usage

### 🔧 Requirements
- Python 3.x installed on your system

### ▶️ Running the Program
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/caesar-cipher.git
   cd caesar-cipher
python caesar_cipher.py

3. Enter:
- A message (text you want to encrypt/decrypt)
- A shift value (integer)
Example Working
Example 1: Encryption
   === Caesar Cipher Program ===
Enter your message: Hello World
Enter shift value (integer): 3

--- Results ---
Original Message: Hello World
Encrypted Message: Khoor Zruog
Decrypted Message: Hello World

Example 2: Encryption with Shift 5
Enter your message: Python
Enter shift value (integer): 5

--- Results ---
Original Message: Python
Encrypted Message: Udymts
Decrypted Message: Python

caesar-cipher/
│
├── caesar_cipher.py   # Main program file
└── README.md          # Documentation

✨ Features- Encrypts and decrypts text using Caesar Cipher
- Handles both uppercase and lowercase letters
- Leaves non-alphabetic characters unchanged
- Simple and beginner-friendly implementation
