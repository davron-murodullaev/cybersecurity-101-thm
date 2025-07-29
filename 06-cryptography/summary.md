# Section 6: Cryptography

## 🧭 Overview

Cryptography is the science of securing information. This module introduces you to the basic principles of encryption, decryption, hashing, and how cryptographic protocols ensure confidentiality, integrity, and authenticity. These are critical concepts used in nearly all areas of cybersecurity.

## 📌 Key Concepts

| Topic            | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| Encryption       | Converting readable data into ciphertext to prevent unauthorized access     |
| Decryption       | Reversing ciphertext back to plaintext using a key                          |
| Hashing          | One-way transformation of data used to verify integrity                     |
| Symmetric Crypto | Same key is used for both encryption and decryption (e.g., AES)             |
| Asymmetric Crypto| Public/private key encryption (e.g., RSA, SSL/TLS)                          |
| Digital Signatures | Prove origin and authenticity of messages                                 |

---

## 🧪 Hands-On Practice Examples

### 🔐 Symmetric Encryption with OpenSSL

```bash
# Encrypt a file using AES-256
openssl enc -aes-256-cbc -salt -in secret.txt -out secret.enc

# Decrypt the file
openssl enc -aes-256-cbc -d -in secret.enc -out decrypted.txt
```

## Screenshot
<img width="1753" height="934" alt="image" src="https://github.com/user-attachments/assets/7a40a34e-a5f4-4cc5-94c9-bb237d2337c4" />
