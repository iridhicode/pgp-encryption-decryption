## PGP Encryption and Decryption in Java 🔒

![Implementing Encryption in Java](https://github.com/iridhicode/pgp-encryption-decryption/assets/52284756/3ae28068-41dc-4bfd-ad65-161e0eccd45b)

This repository provides a tutorial and example code for implementing PGP (Pretty Good Privacy) encryption and decryption in Java using the Bouncy Castle library. 📚

### Introduction
PGP is an asymmetric encryption algorithm that uses public-key cryptography to secure data communication. It involves generating a pair of keys: a public key for encryption and a private key for decryption.🌟

### Prerequisites
Before getting started, make sure you have the following prerequisites:

- [Java Development Kit](https://www.oracle.com/in/java/technologies/downloads/) (JDK) installed on your system 📥
- [Bouncy Castle](https://www.bouncycastle.org/) library added to your project dependencies 📦

### Getting Started
To get started with PGP encryption and decryption in Java, follow these steps:

- Clone this repository to your local machine using the following command:
```bash
git clone https://github.com/iridhicode/pgp-encryption-decryption
```

- Open the project in your favorite Java IDE. 💻
- Make sure you have the Bouncy Castle library added to your project dependencies. You can download it from the Bouncy Castle website or add it using a build tool like Maven or Gradle. 📚
- Generate a pair of public and private keys for the sender and receiver. You can use the `ssh-keygen` command-line tool or any other PGP key generation tool. 🔑

### Usage
To use the PGP encryption and decryption functionality, follow these steps:

- Update the main method in the `PGPReader` class with the appropriate file paths for your input file, private key, public keys, and email addresses. 📝
- Run the main method to perform encryption and decryption. 🚀
- The encrypted file will be generated, and the decrypted file will be output to the console or saved to a file, depending on your implementation. 📤


### Contributing
Contributions to this project are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request. 🤝
