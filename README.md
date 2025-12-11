# KTalki 🔒

A private messenger with a focus on security and minimalism, developed in C++/Qt.

## 🌟 Features

- **Privacy**: End-to-end encryption of all messages.
- **Minimalism**: Clean and user-friendly interface.
- **Reliability**: Operation as a ground-based PTS with guaranteed delivery.
- **Independence**: Full control over data and server infrastructure.

## 🛡️ Security

- **Offline Registration**: Man-in-the-middle attack prevention
- **TLS** with ECH (Encrypted Client Hello) support for metadata protection. - Modern cryptographic algorithms
- Local storage of encryption keys
- Protection against MITM attacks

## 📦 Tech Stack

### Backend

- Language: **C++23**
- Framework: **Qt 6**
- Databases:
- PostgreSQL (main storage)
- Redis (caching and sessions)
- Logging: **spdlog**
- Networking: **TCP with TLS with ECH support**

### Infrastructure

- Containerization: **Docker** - Reverse Proxy: **Nginx**
- CI/CD: **GitHub Actions**
- Documentation: **Doxygen**

### Development Tools

#### Testing

- **GTest** (C++ unit tests)
- **Pytest** (integration tests)

#### Code Analysis

- **clangd** (LSP server)
- **clang-format** (formatting)
- **clang static analyzer** (static analysis)

#### Project Management

- **GitHub Projects**
