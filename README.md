# AES-CBC Encryption for Bitcoin Wallet Passwords

This web-based tool allows you to securely encrypt and decrypt data using AES encryption (CBC mode), which can be used for generating and managing secure passwords for Bitcoin wallets.

## Features

- **Encrypt**: Encrypt any phrase with a password using AES-CBC encryption.
- **Decrypt**: Decrypt encrypted data back into the original phrase.
- **Base64 Encoding**: The encrypted data, salt, and IV (Initialization Vector) are displayed in Base64 encoding, making it easy to store or share securely.
- **Password Protection**: Data is encrypted/decrypted using a password that you provide.
- **Loading Spinner**: A spinner appears while the data is being processed, indicating the operation is in progress.
- **Copy to Clipboard**: Easily copy the encrypted data, salt, IV, or decrypted text using the built-in copy buttons.

## How to Use

### Encrypt Data
1. **Enter the phrase** you want to encrypt in the "Phrase to encrypt" field.
2. **Enter the password** to use for encryption in the "Password" field.
3. Click the **Generate Encrypted Data** button.
4. The encrypted data, salt, and IV will be displayed in Base64 format.
5. You can copy these values to your clipboard using the copy icons next to each field.

### Decrypt Data
1. **Enter the encrypted data** (Base64) in the "Encrypted Text" field.
2. **Enter the salt** (Base64) in the "Salt" field.
3. **Enter the IV** (Base64) in the "IV" field.
4. **Enter the password** you used for encryption in the "Password to Decrypt" field.
5. Click the **Decrypt** button.
6. If the password is correct, the original phrase will appear in the "Original Text (Decrypted)" field. If the password is incorrect, an error message will be displayed.
