# Tesserarx - Content Pass System

A blockchain-based content distribution platform with NFT-based access control. This repository organizes the complete Tesserarx ecosystem as git submodules.

## 📦 Repository Structure

This is an umbrella repository containing three submodules:

### [tesserarx-contracts](https://github.com/jordyarms/tesserarx-contracts)
Smart contracts for the Tesserarx content pass system.
- ERC-1155 based ContentPassFactory
- Governance and versioning system
- Deployed on Moonbase Alpha testnet

### [tesserarx-demo](https://github.com/jordyarms/tesserarx-demo)
Frontend web applications for the Tesserarx platform.
- Market page for browsing and claiming decks
- Vault for managing owned content
- Reader for viewing tarot deck content
- Live demo at: https://tesserarx-demo.vercel.app

### [tdp-standard](https://github.com/jordyarms/tdp-standard)
Tarot Deck Package (TDP) specification and standard.
- TDP-1.0 format specification
- Package structure documentation
- Reference implementations

## 🚀 Quick Start

```bash
# Clone with submodules
git clone --recursive https://github.com/jordyarms/tesserarx.git

# Or if already cloned, initialize submodules
git submodule update --init --recursive
```

## 📚 Learn More

Each submodule has its own README with detailed setup and usage instructions:

- **Contracts:** See [tesserarx-contracts/README.md](tesserarx-contracts/README.md)
- **Frontend:** See [tesserarx-demo/README.md](tesserarx-demo/README.md)
- **Standard:** See [tdp-standard/README.md](tdp-standard/README.md)

## 🎯 What is Tesserarx?

Tesserarx is a content distribution platform that uses blockchain-based NFT passes to control access to digital content. Originally designed for tarot deck distribution, the system is content-agnostic and can handle any digital media.

**Key Features:**
- ✅ NFT-based access control (ERC-1155)
- ✅ Decentralized content distribution
- ✅ Versioned content updates
- ✅ Free and paid content support
- ✅ On-chain metadata and manifest URIs

## 🔗 Links

- **Live Demo:** https://tesserarx-demo.vercel.app
- **Contract Address:** `0xBFF26E227Cb5fb0Feb0D18250C0a655A6066C865` (Moonbase Alpha)
- **Block Explorer:** [View on Moonscan](https://moonbase.moonscan.io/address/0xBFF26E227Cb5fb0Feb0D18250C0a655A6066C865)

## 📄 License

MIT License - See [LICENSE](LICENSE) for details
