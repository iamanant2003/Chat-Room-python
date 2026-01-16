# Chat-Room-python
A secure, multi-client chat application built in Python that supports real-time messaging, file sharing, and multiple encryption standards (AES, DES, RSA) for secure communications.

## Features
* 🔐 Multi-Encryption Support: Choose between AES, DES, or RSA encryption algorithms
* 👥 Multi-Client Chat Room: Multiple users can connect and chat simultaneously
* 📁 Secure File Sharing: Share files with end-to-end encryption
* 🔏 Digital Signatures: DSA implementation for message authentication
* 🔒 SHA-256 Hashing: Secure hashing for data integrity verification
* 🌐 Network Communication: Client-server architecture with reliable connections

## Project Structure
Chat-Room-python/
* ├── host.py
* ├── client.py
* ├── AESImplement.py
* ├── DESImplement.py
* ├── RSAImplement.py
* ├── DSA.py
* ├── SHA256.py
* ├── FileSharing/
* └── README.md

## Getting Started
### Prerequisites
* Python
* Required Python libraries (install via pip)

### Installation
1. Clone the repository:
* git clone https://github.com/kartikMahendru/Chat-Room-python.git
* cd Chat-Room-python

2. Run the server:
* python host.py

3. Run clients (in separateterminal windows):
* python client.py

# Usage
## Basic Chat Functionality
1. Start the server using host.py
2. Launch multiple client instances using client.py
3. Enter your username when prompted
4. Start sending messages - all connected clients will receive them

## File Sharing
1. From within the chat interface, use the file sharing commands
2. Select the file you want to share
3. Choose encryption method (AES, DES, or RSA)
4. The file will be encrypted and sent to all connected clients

## Encryption Options
* AES: Advanced Encryption Standard (symmetric)
* DES: Data Encryption Standard (symmetric)
* RSA: Rivest–Shamir–Adleman (asymmetric)
* DSA: Digital Signature Algorithm for authentication

# Technical Details
## Encryption Implementations
* AES-Symmetric: 128/192/256 bit and AESImplement.py
* DES-Symmetric: 56 bit and DESImplement.py
* RSA-Asymmetric: 2048+ bit	and RSAImplement.py
* DSA-Digital Signature: DSA.py
* SHA-256	Hash: 256 bit	SHA256.py

## Network Architecture
* Server (host.py): Manages client connections, message routing, and file distribution
* Client (client.py): Connects to server, sends/receives messages and files
* Threading: Multiple client connections handled concurrently

# Contributors
* kartikMahendru - Project maintainer
* Abhishek1103 - Contributor
* abhi1358 - Contributor

# Contributing
Contributions are welcome! Please follow these steps:
* Fork the repository
* Create a feature branch (git checkout -b feature/AmazingFeature)
* Commit your changes (git commit -m 'Add some AmazingFeature')
* Push to the branch (git push origin feature/AmazingFeature)
* Open a Pull Request

# Areas for Contribution
* Additional encryption algorithms
* Improved GUI interface
* Enhanced file transfer protocols
* Better error handling and logging
* Performance optimizations

# Known Issues & Troubleshooting
* Port conflicts: Ensure default port is available or modify in host.py
* Firewall issues: Allow Python through firewall for network connections
* Large files: File size limitations may exist based on encryption method
* Python version: Compatible with Python 3.x, may need adjustments for specific versions

# Future Enhancements
Planned features for future development:
* Web-based interface using Flask/Django
* Mobile client applications
* Voice and video chat capabilities
* End-to-end encryption with perfect forward secrecy
* Message history and persistence
* Group chat with admin controls

# Acknowledgments
* Cryptography libraries and documentation that made this project possible
* Contributors and testers who helped improve the software
* Open-source community for inspiration and resources

# Support
* For support, questions, or feature requests:
* Open an issue on the GitHub Issues page
* Contact the maintainers through GitHub profiles

