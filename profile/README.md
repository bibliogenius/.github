# BiblioGenius 📚

**Your library, your rules.** A decentralized, privacy-first personal library manager.

🌐 [**bibliogenius.org**](https://bibliogenius.org)

[![Status](https://img.shields.io/badge/status-in_development-blue)](https://github.com/bibliogenius)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## ✨ What is BiblioGenius?

BiblioGenius is a **self-hosted ecosystem** for managing your personal book collection and sharing it with your network.

- 📖 **Catalog your books** via ISBN scan or manual entry
- 🔄 **Sync across devices** on your local network
- 🤝 **Share with friends** peer-to-peer, no central server
- 🤖 **Speak with your library** using **MCP (Model Context Protocol)** for local AI
- 🏆 **Gamification** — earn badges and level up your librarian status
- 🔒 **Privacy-first** — Digital Sovereignty by design

## 🏗️ Ecosystem

| Component | Description | Tech |
| --------- | ----------- | ---- |
| [**bibliogenius**](https://github.com/bibliogenius/bibliogenius) | Autonomous library server | Rust, Axum, SQLite |
| [**bibliogenius-app**](https://github.com/bibliogenius/bibliogenius-app) | Mobile & Desktop apps | Flutter + Rust (FFI) |
| [**bibliogenius-hub**](https://github.com/bibliogenius/bibliogenius-hub) | Optional central directory | Symfony |

## 🗺️ Roadmap and Ideas

- 🚧 **P2P Book Sharing** — Connect libraries on local network (mDNS)
- 🌐 **Global P2P** — Connect with friends anywhere (NAT traversal with **Iroh**)
- 🔐 **Crypto Identity** — Ed25519 keypairs for trust verification
- 📱 **Social Feed** — See what your friends are reading
- 🏛️ **Historical Theme** — Immersive "Old Library" ambiance

## 🚀 Quick Start

### For Users

Download the latest release for your platform:
<https://github.com/bibliogenius/bibliogenius-app/releases>

### For Developers

```bash
# Clone the monorepo
git clone https://github.com/bibliogenius/bibliotech.git
cd bibliotech/bibliogenius-app

# Run the app (Rust compiles automatically!)
flutter pub get
flutter run -d macos
```

> **Note**: No separate `cargo run` is needed. The Rust backend is embedded in the Flutter app via FFI (Cargokit handles compilation automatically).

See [DEVELOPMENT_SETUP.md](https://github.com/bibliogenius/bibliogenius-docs/blob/main/docs/technical/DEVELOPMENT_SETUP.md) for detailed instructions.

## 🧪 Testing Status

> [!NOTE]
> **Currently tested on:**
>
> - ✅ **macOS** (primary development platform)
> - ✅ **iPad** (limited testing)
>
> **Looking for testers on:**
>
> - 🔎 **iOS** (iPhone)
> - 🔎 **Android** (phones & tablets)
> - 🔎 **Windows**
> - 🔎 **Linux**
>
> If you can help test BiblioGenius on any of these platforms, please [open an issue](https://github.com/bibliogenius/bibliogenius-app/issues) with your feedback!

## 🤝 Contributing

We welcome contributions! Feel free to open issues or pull requests on any repository.

## 📄 License

MIT License — see LICENSE in each repository.

---

**Made with ❤️ by [Federico CALO](https://federico-calo.net)**
