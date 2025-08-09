# TEOS NFT AI Generator
Official TEOS Network Ecosystem
**Empowering Cultural Expression through AI & NFTs**
> **TEOS NFT AI Generator** is a full-stack platform for generating culturally inspired NFTs using AI. Built with React + Flask, it supports multi-language prompts, Egyptian art styles, and is ready for blockchain minting (Solana, Ethereum). Phase 1 is live. Phase 2 (minting) launches September 2025.

 ![TEOS NFT AI Generator](https://img.shields.io/badge/Status-Live-brightgreen) ![Phase](https://img.shields.io/badge/Phase-1%20Complete-blue) ![License](https://img.shields.io/badge/License-TEOS%20Egypt-gold)
![Python](https://img.shields.io/badge/Python-3.11%2B-blue.svg)
![Node.js](https://img.shields.io/badge/Node.js-20%2B-green.svg)
![React](https://img.shields.io/badge/React-18-blue.svg)
![Flask](https://img.shields.io/badge/Flask-Backend-lightgrey.svg)
![SQLite](https://img.shields.io/badge/Database-SQLite-orange.svg)
![AI-Powered](https://img.shields.io/badge/AI-Powered%20NFTs-purple.svg)
![ERC-721](https://img.shields.io/badge/NFT-ERC--721-blueviolet.svg)
![Solana](https://img.shields.io/badge/Solana-Ready-teal.svg)
![License](https://img.shields.io/github/license/Elmahrosa/TEOS-NFT-AI-Generator.svg)
![CI/CD](https://img.shields.io/github/actions/workflow/status/Elmahrosa/TEOS-NFT-AI-Generator/deploy.yml?branch=main)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)

## 🌟 About the Project

TEOS NFT AI Generator is a groundbreaking platform that uses artificial intelligence to create NFTs inspired by Egyptian culture, heritage, and innovation. Built on top of the TEOS ecosystem, it invites users to generate unique, AI-powered digital assets that can be minted, traded, and showcased worldwide.

**Live Demo:** [https://qjh9iecnj9z1.manus.space](https://qjh9iecnj9z1.manus.space)

## 🌍 Vision

To preserve and promote Egyptian cultural identity using the power of blockchain and AI. We aim to create a new generation of artists and collectors who can use smart tools to tell their stories through digital art.

## ⚙️ Features

### Phase 1 (✅ Completed)
- **AI-powered NFT generation** from text prompts (Arabic/English)
- **Custom Egyptian templates** with three distinct styles:
  - 🏺 **Pharaonic**: Ancient Egyptian royal art style
  - 🕌 **Islamic**: Traditional Islamic geometric patterns  
  - 🏙️ **Modern Egyptian**: Contemporary Egyptian cultural fusion
- **Multi-language support** (English/Arabic)
- **User collections** and social sharing
- **Responsive design** optimized for all devices
- **Beautiful Egyptian-themed UI** with cultural patterns

### Phase 2 (🔄 In Development - September 2025)
- Real AI integration with OpenAI DALL-E
- One-click minting to Solana blockchain
- Ethereum network support
- Wallet integration (Phantom, MetaMask)
- NFT metadata generation

### Phase 3 (📅 Planned - October 2025)
- Marketplace integration
- NFT trading functionality
- Advanced search and filtering
- Social features and community

### Phase 4 (📅 Planned - Q4 2025)
- Mobile app development
- Telegram bot for NFT minting
- Cross-platform integration

## 🎯 Use Cases

- **Create and sell** cultural NFT art
- **Gaming integration** with AI NFTs for virtual worlds
- **Educational projects** for museums and cultural institutions
- **Personal art creation** with Egyptian cultural themes

## 🚀 Quick Start

### Prerequisites
- Node.js 20+ and pnpm
- Python 3.11+ and pip
- Git

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Elmahrosa/teos-nft-ai-generator.git
cd teos-nft-ai-generator
```

2. **Setup Frontend**
```bash
cd teos-nft-frontend
pnpm install
pnpm run dev
```

3. **Setup Backend**
```bash
cd ../teos-nft-backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python src/main.py
```

4. **Access the application**
- Frontend: http://localhost:5173
- Backend API: http://localhost:5000
- Full-stack: http://localhost:5000 (recommended)

## 🏗️ Architecture

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   React Frontend │    │   Flask Backend │    │   AI Services   │
│                 │    │                 │    │                 │
│ • Egyptian UI   │◄──►│ • REST API      │◄──►│ • OpenAI DALL-E │
│ • Multi-language│    │ • SQLite DB     │    │ • Style Engine  │
│ • Responsive    │    │ • CORS Enabled  │    │ • Enhancement   │
└─────────────────┘    └─────────────────┘    └─────────────────┘
         │                       │                       │
         └───────────────────────┼───────────────────────┘
                                 ▼
                    ┌─────────────────┐
                    │   Blockchain    │
                    │                 │
                    │ • Solana        │
                    │ • Ethereum      │
                    │ • Pi Network    │
                    └─────────────────┘
```

## 🎨 Egyptian Art Styles

### 🏺 Pharaonic Style
- Ancient Egyptian royal aesthetics
- Hieroglyphic elements and golden colors
- Temple architecture and divine motifs
- Royal Egyptian symbolism

### 🕌 Islamic Style  
- Traditional Islamic geometric patterns
- Arabic calligraphy integration
- Mosque architecture elements
- Intricate mathematical designs

### 🏙️ Modern Egyptian Style
- Contemporary Egyptian cultural fusion
- Cairo cityscape with ancient elements
- Nile river motifs
- Modern interpretation of heritage

## 🛠️ Technology Stack

### Frontend
- **React 18** with Hooks and Context
- **Tailwind CSS** for styling
- **shadcn/ui** component library
- **Lucide React** for icons
- **Vite** for build tooling

### Backend
- **Flask** web framework
- **SQLAlchemy** ORM
- **Flask-CORS** for cross-origin requests
- **SQLite** database (production-ready)

### AI & Blockchain (Phase 2)
- **OpenAI DALL-E** for image generation
- **Solana Web3.js** for blockchain interaction
- **Ethereum Web3** integration
- **IPFS** for decentralized storage

## 📊 API Documentation

### Generate NFT
```http
POST /api/generate-nft
Content-Type: application/json

{
  "prompt": "A majestic pharaoh with golden crown",
  "style": "pharaonic",
  "language": "en"
}
```

### Mint NFT (Phase 2)
```http
POST /api/mint-nft
Content-Type: application/json

{
  "imageUrl": "https://...",
  "metadata": {...},
  "blockchain": "solana"
}
```

## 🌐 Deployment

The application is deployed on Vercel with automatic CI/CD:

- **Production URL:** https://qjh9iecnj9z1.manus.space
- **Custom Domain:** nft.teosegypt.com (configure DNS)
- **Environment:** Production-ready with monitoring

### Deploy Your Own

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Elmahrosa/teos-nft-ai-generator)

## 🤝 Contributing

We welcome contributions from the community! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting pull requests.

### Development Workflow
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the TEOS Egypt License. See [LICENSE](LICENSE) for details.

## 🤝 Powered By

- **TEOS Egypt** - Cultural preservation through technology
- **Elmahrosa Blockchain** - Blockchain infrastructure
- **Solana** - High-performance blockchain
- **Ethereum** - Decentralized platform
- **Pi Network** - Accessible cryptocurrency

## 📞 Support

- **Website:** [teosegypt.com](https://teosegypt.com)
- **Email:** support@teosegypt.com
- **Telegram:** [@teosegypt](https://t.me/teosegypt)
- **Twitter:** [@teosegypt](https://twitter.com/teosegypt)

## 🛣️ Roadmap

- [x] **Phase 1:** Website + Generator Launch (August 2025)
- [ ] **Phase 2:** Smart Contract Minting (September 2025)  
- [ ] **Phase 3:** Marketplace Integration (October 2025)
- [ ] **Phase 4:** Mobile + Telegram Bot (Q4 2025)

## 📈 Stats

![GitHub stars](https://img.shields.io/github/stars/Elmahrosa/teos-nft-ai-generator?style=social)
![GitHub forks](https://img.shields.io/github/forks/Elmahrosa/teos-nft-ai-generator?style=social)
![GitHub issues](https://img.shields.io/github/issues/Elmahrosa/teos-nft-ai-generator)
![GitHub pull requests](https://img.shields.io/github/issues-pr/Elmahrosa/teos-nft-ai-generator)

---

**© 2025 TEOS Egypt. All rights reserved. Elmahrosa International.**

*Empowering Cultural Expression through AI & NFTs* 🇪🇬

