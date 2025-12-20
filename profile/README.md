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

> **Supported by the [NLnet foundation](https://nlnet.nl/) (NGI Zero Commons Fund)** to build a Human-centric Internet.

## 🏗️ Ecosystem

| Component | Description | Tech |
|-----------|-------------|------|
| [**bibliogenius**](https://github.com/bibliogenius/bibliogenius) | Autonomous library server | Rust, Axum, SQLite |
| [**bibliogenius-app**](https://github.com/bibliogenius/bibliogenius-app) | Mobile & Desktop apps | Flutter |
| [**bibliogenius-hub**](https://github.com/bibliogenius/bibliogenius-hub) | Optional central directory | Symfony |

## 🗺️ Roadmap

| Version | Name | Target | Focus |
|---------|------|--------|-------|
| **In Development** | Sovereign Librarian | ✅ Now | Personal library + LAN sync |
| v1.0.0 | Local Network | Q1 2026 | Stable P2P on local network |
| v1.5.0 | AI Librarian | Q2 2026 | **MCP Integration** (Local AI Agents) |
| v2.0.0 | Trusted Network | Q3 2026 | Global P2P + Social Features |

### 🔮 Coming in v2.0

- 🌐 **True P2P** — Connect with friends anywhere (NAT traversal with libp2p)
- 🤖 **MCP Server** — Expose your library as a resource to local AI agents (Claude, Ollama)
- 🔐 **Crypto Identity** — Ed25519 keypairs for trust verification
- 📱 **Social Feed** — See what your friends are reading
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
