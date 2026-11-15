# Gistup 💬
### Connect. Chat. Share.

**Gistup** is a modern messaging platform built to make communication simple, fast, and accessible. It provides users with the tools to chat, share media, create groups, manage conversations, and stay connected.

We are building Gistup with scalability, security, and flexibility in mind, and we welcome developers and technology enthusiasts who want to contribute to its growth.

---

## 🚀 About Gistup

Gistup is powered by a plain PHP REST API, MySQL/MariaDB, JSON, and bearer-token authentication.

The API is designed to support multiple frontend platforms, including:
- Web applications (React, JavaScript)
- Android and iOS applications
- React Native
- Flutter
- Other applications that support HTTP and JSON

## ✨ Features

- **Authentication:** Phone number registration and OTP verification.
- **Private Messaging:** One-to-one conversations.
- **Group Chats:** Create groups and manage members.
- **Media Sharing:** Images, voice messages, and files.
- **Message Management:** Edit, delete, reply, and react to messages.
- **Read Receipts:** Delivered and read status.
- **Disappearing Messages:** Messages that expire automatically.
- **Scheduled Messages:** Schedule messages for later delivery.
- **Voice and Video Calls:** Call management and integration-ready architecture.
- **Push Notifications:** Device push-token registration.
- **Payments:** Flutterwave checkout and transaction verification.
- **Real-time Synchronization:** Event feeds and optional WebSocket integration.
- **Security:** Bearer tokens, hashed refresh tokens, rate limiting, and prepared SQL statements.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| PHP 8.1+ | Backend API |
| MySQL / MariaDB | Database |
| JSON | API communication |
| JavaScript | Client integration |
| cURL | External API communication |
| JWT | Access-token authentication |
| WebSocket | Optional real-time delivery |
| Flutterwave | Payment integration |

## 📦 Installation

1. Upload the Gistup project to your PHP hosting environment.
2. Create a MySQL/MariaDB database.
3. Import `schema.sql`.
4. Copy `.env.example` to `.env`.
5. Configure database credentials and application settings.
6. Generate a secure JWT secret:

```bash
openssl rand -hex 32
```

7. Configure your storage permissions.
8. Configure URL rewriting for `/v1/` routes.
9. Start the background worker using cron:

```bash
* * * * * php /path/to/worker.php
```

10. Test your API:

```http
GET /v1/health
```

See the project documentation for complete installation and configuration instructions.

## 🔌 API Overview

Gistup provides REST API endpoints for:

- Authentication
- Users and contacts
- Chats and groups
- Messages and reactions
- Media uploads
- Payments
- Calls
- Event synchronization

All API requests use JSON unless otherwise specified.

Authentication uses:

```http
Authorization: Bearer YOUR_ACCESS_TOKEN
```

## 🤝 We Need Contributors!

**Gistup is open to developers, designers, testers, and technology enthusiasts who want to contribute to building something useful.**

We believe great software is built through collaboration, shared knowledge, and continuous improvement.

We are looking for contributors in the following areas:

### 👨‍💻 Backend Developers
- PHP developers
- MySQL/MariaDB developers
- API security specialists
- WebSocket and real-time communication developers

### 🎨 Frontend Developers
- React developers
- JavaScript developers
- React Native developers
- Flutter developers

### 📱 Mobile App Developers
- Android developers
- iOS developers
- Cross-platform application developers

### 🧪 Testers & Security Researchers
- API testing
- Bug identification
- Performance testing
- Security reviews

### 🎨 UI/UX Designers
- Mobile application design
- Web application interfaces
- User experience improvements

### 💡 Other Contributors
- Technical writers
- Documentation contributors
- Product designers
- Open-source enthusiasts

## 🌱 How to Contribute

We welcome contributions of all sizes.

1. Fork this repository.
2. Create a new branch for your contribution.
3. Make your changes.
4. Test your changes.
5. Submit a Pull Request explaining what you improved.

You can also contribute by:
- Reporting bugs.
- Suggesting new features.
- Improving documentation.
- Reviewing code.
- Helping test API endpoints.
- Sharing ideas for improving Gistup.

If you find an issue, please open a GitHub Issue with steps to reproduce it.

## 📋 Contribution Guidelines

To keep the project organized:

- Write clean and readable code.
- Follow the existing project structure.
- Avoid introducing unnecessary dependencies.
- Do not commit API keys, passwords, or `.env` files.
- Test your changes before submitting a Pull Request.
- Explain significant changes clearly.

## 🗺️ Project Roadmap

Some areas we aim to improve and expand include:

- [ ] Complete web messaging interface.
- [ ] Android and iOS applications.
- [ ] Improved real-time messaging.
- [ ] Live voice and video calling integrations.
- [ ] Improved media storage and CDN support.
- [ ] Enhanced end-to-end encryption.
- [ ] Expanded payment and wallet functionality.
- [ ] More automated testing and security improvements.

Contributions toward these goals are welcome.

## 🔐 Security

If you discover a security vulnerability, please report it privately to the project maintainers rather than publicly exposing sensitive details.

Never submit API credentials, private keys, or user data in issues or pull requests.

## ❤️ Support the Project

You can support Gistup by:

- Starring the repository ⭐
- Sharing the project with other developers.
- Contributing code.
- Reporting bugs.
- Suggesting improvements.
- Inviting other developers to collaborate.

## 📬 Get Involved

Interested in contributing?

**We would love to have you on board!**

Open an issue, submit a pull request, or contact the project maintainer to discuss collaboration opportunities.

Every contribution, whether small or significant, helps move Gistup forward.

---

## 💬 Gistup

**Your People. Your Conversations. Your Connection.**

*Built with the vision of making communication easier for everyone.*

**Let's build Gistup together! 🚀**
