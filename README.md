# Crypto Toolkit

A Streamlit-based educational cryptographic toolkit that demonstrates encryption, hashing, and data encoding techniques through an interactive interface.

## Project Overview

Crypto Toolkit is a team project developed to demonstrate fundamental cryptographic concepts and their practical implementation using Python and Streamlit.

The application is organized into four main modules:
- **Symmetric Encryption**
- **Asymmetric Encryption**
- **Encoding & Decoding**
- **Hashing**

---

## Features

### Symmetric Encryption
Supports encryption and decryption using:
- **AES** (CBC mode with PKCS7 padding)
- **DES** & **3DES**
- Base64 representation of encrypted output

### Asymmetric Encryption
Implements RSA-based encryption with:
- 2048-bit key generation
- Public key encryption
- Private key decryption
- PKCS#1 OAEP padding

### Encoding & Decoding
Provides conversion between:
- Base64
- Hexadecimal
- URL Encoding

### Hashing
Supports integrity verification with:
- SHA-256 and SHA-512
- Random salting, custom salting, and unsalted hashing

---

## Technologies Used

- **Language:** Python
- **UI Framework:** Streamlit
- **Cryptography Library:** PyCryptodome

---

## Project Structure

```text
crypto-toolkit/
├── CryptoToolkit.py
├── requirements.txt
└── .gitignore
```

## Installation and Usage

### 1.Clone the Repository
```
git clone https://github.com/maii818/crypto-toolkit.git
cd crypto-toolkit
```

### 2. Install Dependencies
```
pip install -r requirements.txt
```

### 3. Run the Application
```
streamlit run CryptoToolkit.py
```

## Team Members

This project was developed as a team project by:
- Malak Ashraf Rezk
- Nourhan Essam Abd El-Razek
- Farah Ibrahim Ahmed Ibrahim
- Maii Walid Mohamed Al-Ahmer

## Disclaimer

This project was developed strictly for educational purposes to demonstrate cryptographic concepts and their implementation.
