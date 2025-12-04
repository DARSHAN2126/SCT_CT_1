# 🔐 Caesar Cipher Program

This project implements a simple **Caesar Cipher encryption and decryption tool** using Python.
It allows users to enter a message and a shift value, then outputs:

* The **original message**
* The **encrypted message**
* The **decrypted message**

This is a classic example of a substitution cipher used for educational and cryptography practice.

---

## 📌 Features

* Encrypt any text using a Caesar Cipher
* Decrypt automatically using the same shift
* Supports both uppercase and lowercase letters
* Non-alphabet characters remain unchanged
* Simple command-line user interface

---

## 🧠 How It Works

The Caesar Cipher shifts each letter by a specified number.
Example with shift = 3:

```
A → D  
B → E  
C → F  
...
```

Decryption reverses the shift.

---

## 📂 Project Structure

```
├── caesar_cipher.py     # Main Python script
└── README.md            # Documentation
```

---

## ▶️ Usage

### 1. Run the program

```bash
python caesar_cipher.py
```

### 2. Enter your message

Example:

```
Enter your message: Hello World
```

### 3. Enter a shift value

Example:

```
Enter shift value (integer): 3
```

### 4. Program Output

```
--- Results ---
Original Message: Hello World
Encrypted Message: Khoor Zruog
Decrypted Message: Hello World
```

---
