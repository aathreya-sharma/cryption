# **Cryptography and Information Security Project**

## **Team Members**

- **Amoghavarsha** (22bcs009)
- **Aathreya Sharma** (22bcs024)
- **Bhanodhay Rao** (22bcs028)
- **Yellaling Kalyane** (22bcs140)

## **Overview**

**Cryptex** is an open-source tool designed for AES encryption and decryption directly within the browser, eliminating the need to upload data to the cloud. By maintaining file integrity, Cryptex ensures that manipulation of files is impossible without the correct password.

## **Features**

- **In-browser AES Encryption and Decryption**: Encrypts and decrypts data within the browser, ensuring privacy and security.
- **Data Integrity Check**: Verifies that data has not been tampered with, preserving file authenticity.
- **Password Hints**: Provides helpful hints to users for password recall without compromising security.

## **Security Benefits**

Cryption offers strong protection against:

- **Unauthorized Access**: Password-based protection prevents access by unauthorized users.
- **Data Tampering**: Integrity checks confirm that files remain unchanged.

## **Technology Stack**

- **Frontend**: React.js
- **Encryption Logic**: AES (Advanced Encryption Standard) in JavaScript

## **Usage**

- **Encrypt and Decrypt Files**: Users can encrypt and decrypt files directly within the browser.

## **Prerequisites**

- **Node.js**
- **npm**

## **Starting the Server**

**PLEASE NOTE THAT npm and Node.js must be installed before this.**

1. **Clone the repository** (stable branch):
    ```bash
    git clone -b main https://github.com/aathreya-sharma/cryptography-project
    ```

2. **Change Directory**:
    ```bash
    cd cryptography-project
    ```

3. **Install Packages**:
    ```bash
    npm install
    ```

4. **In case of vulnerabilities run:**:
    ```bash
    npm audit fix --force
    ```

5. **If your Node.js version is after 16**, run this:
    ```bash
    set NODE_OPTIONS=--openssl-legacy-provider
    ```

6. **Otherwise, run this directly**:
    ```bash
    npm start
    ```

## **Conclusion**

**Cryption** provides a secure solution for browser-based file encryption, prioritizing data privacy and integrity with no dependency on cloud services. By offering an intuitive interface and essential features, Cryption empowers users to manage sensitive data confidently and securely.
