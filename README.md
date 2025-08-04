Simple Password Manager
This repository contains a simple, command-line-based password manager written in Python. It allows users to store, retrieve, and delete passwords in an encrypted database.

⚠️ Disclaimer: Security Warning ⚠️
This project is for educational purposes only and should not be used to store real or sensitive passwords. The encryption scheme used in this project is a custom implementation based on AES principles but is not a production-ready, cryptographically secure solution. It contains known vulnerabilities and is susceptible to various attacks.

For a secure password manager, always use established and peer-reviewed cryptographic libraries (e.g., PyCryptodome, cryptography) and industry-standard key derivation functions.

Features
Generate Passwords: Create a strong, random password of a specified length.

Add Credentials: Store a site name, username, and password in a local database.

Retrieve Passwords: Decrypt and view passwords for a specific site using an ID.

Delete Entries: Remove stored credentials from the database.

Local Storage: All data is stored locally in an encrypted format using a SQLite database.
