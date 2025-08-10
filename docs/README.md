# Overview: gofilencryptor

This project, `gofilencryptor`, is a **simple and secure tool** designed to *protect your digital files*. It allows you to **encrypt** them, turning readable data into an unreadable format, and then **decrypt** them back to their original state using a password. Built with a *command-line interface*, it's easy to use and can even be run consistently across different environments thanks to *Docker*.


## Visual Overview

```mermaid
flowchart TD
    A0["File Encryption/Decryption Core
"]
    A1["Cryptographic Key Derivation
"]
    A2["Authenticated Encryption (AES-GCM)
"]
    A3["Command-Line Interface (CLI)
"]
    A4["Secure User Input Handling
"]
    A5["File System Interaction
"]
    A6["Application Packaging (Docker)
"]
    A3 -- "Invokes operations" --> A0
    A4 -- "Provides password" --> A3
    A5 -- "Handles file I/O" --> A0
    A0 -- "Derives key" --> A1
    A0 -- "Applies encryption" --> A2
    A3 -- "Validates paths" --> A5
    A6 -- "Executes application" --> A3
```

## Chapters


1. [Command-Line Interface (CLI)
](01_command_line_interface__cli__.md)
2. [File System Interaction
](02_file_system_interaction_.md)
3. [Secure User Input Handling
](03_secure_user_input_handling_.md)
4. [File Encryption/Decryption Core
](04_file_encryption_decryption_core_.md)
5. [Cryptographic Key Derivation
](05_cryptographic_key_derivation_.md)
6. [Authenticated Encryption (AES-GCM)
](06_authenticated_encryption__aes_gcm__.md)
7. [Application Packaging (Docker)
](07_application_packaging__docker__.md)

---
