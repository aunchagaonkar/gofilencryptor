# GO File Encryptor

A simple and secure file encryption and decryption tool written in Go.

## Features

- **Encrypt Files**: Protect your files with AES-GCM encryption.
- **Decrypt Files**: Easily decrypt your files using the same password.
- **Command-Line Interface**: Simple and intuitive CLI for everyday use.
- **Docker Support**: Run the application in a Docker container.

## Usage

### Encrypt a File

```sh
go run . encrypt /path/to/your/file
```
### Decrypt a File

```sh
go run . decrypt /path/to/your/file
```

### Commands
* encrypt: Encrypts a file given a password.
* decrypt: Tries to decrypt a file using a password.
* help: Displays help text.

### Docker
You can also run the application inside a Docker container:
1. Build the Docker Image:
```sh
docker build -t go-file-encryptor
```
2. Run the Docker Container:
```sh
docker run -v /path:/app/files go-file-encryptor encrypt /app/files/file.txt
```

