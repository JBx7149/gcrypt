# Simple libgcrypt-based encryption/decryption tool

## Description

The tool encrypts and decrypts files using the 256-bit AES block cipher for encryption, PBKDF2 for key stretching and derivation, and HMAC-SHA512 (over the ciphertext, KDF salt, and initialization vector) for file integrity and authenticity checking.

## Usage

```
./gcrypt-tool [encrypt|decrypt] <input file path> <output file path> <some-super-strong-password>
```

