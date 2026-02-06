# BiblioGenius 📚

**Your library, your rules.** A decentralized, privacy-first personal library manager.

🌐 [**bibliogenius.org**](https://bibliogenius.org)

[![Status](https://img.shields.io/badge/status-active-success)](https://github.com/bibliogenius)
[![License](https://img.shields.io/badge/license-MIT-green)](https://github.com/bibliogenius/bibliogenius/blob/main/LICENSE)
[![Latest Version](https://img.shields.io/github/v/tag/bibliogenius/bibliogenius-app?sort=semver&label=version&color=blue)](https://github.com/bibliogenius/bibliogenius-app/tags)

---

## 🎯 I Want To

| Goal | Go To Repository |
| :--- | :--- |
| **📱 Use the App** | [**bibliogenius-app**](https://github.com/bibliogenius/bibliogenius-app) (iOS, Android, Desktop) |
| **⚙️ Hack the Backend** | [**bibliogenius**](https://github.com/bibliogenius/bibliogenius) (Rust Core) |
| **📖 Read Docs** | [**bibliogenius-website**](https://github.com/bibliogenius/bibliogenius-website) (Website) |

---

## ✨ What is BiblioGenius?

BiblioGenius is a **self-hosted ecosystem** for managing your personal book collection and sharing it with your network.

- 📖 **Catalog your books** via ISBN scan or manual entry
- 🔄 **Sync across devices** on your local network
- 🤝 **Share with friends** peer-to-peer, no central server
- 🤖 **Speak with your library** using **MCP (Model Context Protocol)** for local AI
- 🏆 **Gamification** — earn badges and level up your librarian status
- 🔒 **Privacy-first** — Digital Sovereignty by design

## 📱 Supported Platforms

- ✅ **macOS**
- ✅ **Windows**
- ✅ **Linux**
- ✅ **iOS**
- ✅ **Android**

## 🚀 Quick Start for Developers

```bash
# Create a workspace folder
mkdir bibliogenius-workspace && cd bibliogenius-workspace

# Clone both repositories (they must be siblings)
git clone https://github.com/bibliogenius/bibliogenius.git       # Rust backend
git clone https://github.com/bibliogenius/bibliogenius-app.git   # Flutter app

# Run the app (Rust compiles automatically via FFI!)
cd bibliogenius-app
flutter pub get
flutter run
```

> **Note**: The Flutter app expects `bibliogenius` (Rust) as a sibling folder. No separate `cargo run` is needed — the backend compiles automatically during `flutter run`.

## 🤝 Contributing

We welcome contributions!

- **Issues**: Open a ticket in the relevant repository.

## 📄 License

MIT License — see LICENSE in each repository.

---

**Made with ❤️ by [Federico CALO](https://federico-calo.net)**
