# Password Hashing CLI (Go)

A simple command-line tool in Go for hashing passwords.  
Based on the official Go documentation example, with an added prompt for interactive user input.

## Features

- Securely hash passwords using bcrypt  
- Interactive user prompt for entering a password  
- Prints the generated hash to stdout

## Prerequisites

- Go 1.16 or later (https://golang.org/dl/)

## Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/mrigueti/password-hashing.git
   cd password-hashing
   ```

## Usage

Run the program and follow the prompt:

```bash
go run main.go
```

You will see:

```
Enter a password:
```

Type your password and press Enter. The tool will output your bcrypt hash:

```
Generated hash: $2a$10$...
```

## License

This project is released under the MIT License.  
Feel free to use and modify as needed.
