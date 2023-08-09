# RSA Factoring Challenge

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

A Bash script to generate RSA keys by utilizing the Factors Challenge Checker.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [License](#license)

## Introduction

The **RSA Key Generator** is a Bash script designed to create RSA key pairs by leveraging the Factors Challenge Checker. RSA keys are used for encryption, decryption, and digital signatures. This script utilizes the Factors Challenge Checker script to assess factors and generate RSA key pairs.

## Usage

To use the **RSA Key Generator**, follow these steps:

1. Ensure you have met the necessary prerequisites (See [Prerequisites](#prerequisites)).
2. Download or clone the RSA Key Generator script and the Factors Challenge Checker script to your local system.
3. Open a terminal window.
4. Navigate to the directory where both scripts are located.
5. Make both scripts executable by running: `chmod +x factor rsa`
6. Generate RSA keys using the command: `./rsa <file>`

Replace `<file>` with the path to the input file containing the numbers for which factors need to be checked.

## Prerequisites

- Bash: Both scripts are designed to run on the Bash shell, commonly available on Unix-like systems, including Linux and macOS.

## Installation

To install the **RSA Key Generator** and **Factors Challenge Checker**, proceed as follows:

1. Download or clone the repository to your desired directory on your local machine.
2. Open a terminal window.
3. Navigate to the directory where both scripts are located.
4. Make both scripts executable by running: `chmod +x factors_challenge.sh rsa.sh`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Note:** The RSA key generation process is a critical security operation. It's important to ensure the security and validity of the generated keys. The scripts provided are for illustrative purposes and should be thoroughly reviewed and validated before being used in a real-world, security-sensitive scenario.
