# BiblioGenius 📚

**Your library, your rules.** A decentralized, privacy-first personal library manager.

[![Status](https://img.shields.io/badge/status-v1.0.0--beta.1-blue)](https://github.com/bibliogenius)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## ✨ What is BiblioGenius?

BiblioGenius is a **self-hosted ecosystem** for managing your personal book collection and sharing it with friends — without Big Tech.

- 📖 **Catalog your books** via ISBN scan or manual entry
- 🔄 **Sync across devices** on your local network
- 🤝 **Share with friends** peer-to-peer, no central server
- 🏆 **Gamification** — earn badges and level up your librarian status
- 🔒 **Privacy-first** — you own your data

## 🏗️ Ecosystem

| Component | Description | Tech |
|-----------|-------------|------|
| [**bibliogenius**](https://github.com/bibliogenius/bibliogenius) | Autonomous library server | Rust, Axum, SQLite |
| [**bibliogenius-app**](https://github.com/bibliogenius/bibliogenius-app) | Mobile & Desktop apps | Flutter |
| [**bibliogenius-hub**](https://github.com/bibliogenius/bibliogenius-hub) | Optional central directory | Symfony |

## 🗺️ Roadmap

| Version | Name | Target | Focus |
|---------|------|--------|-------|
| **v1.0.0-beta** | Sovereign Librarian | ✅ Now | Personal library + LAN sync |
| v1.0.0 | Local Network | Q1 2026 | Stable P2P on local network |
| v2.0.0 | Trusted Network | Q2-Q3 2026 | Global P2P + Social Features |

### 🔮 Coming in v2.0

- 🌐 **True P2P** — Connect with friends anywhere (NAT traversal with libp2p)
- 🔐 **Crypto Identity** — Ed25519 keypairs for trust verification
- 📱 **Social Feed** — See what your friends are reading
- 🤖 **Local AI** — Chat with your library using an offline LLM
- 🏛️ **Historical Theme** — Immersive "Old Library" ambiance

## 🚀 Quick Start

```bash
# Download the latest release for your platform
# https://github.com/bibliogenius/bibliogenius-app/releases

# Or build from source:
git clone https://github.com/bibliogenius/bibliogenius.git
cd bibliogenius && cargo run
```

## 🤝 Contributing

We welcome contributions! Feel free to open issues or pull requests on any repository.

## 📄 License

MIT License — see LICENSE in each repository.

---

**Made with ❤️ by [Federico CALO](https://federico-calo.net)**
