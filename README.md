# MathMint Quiz 🧮✨

**Learn times tables → Mint NFT badges**  
A zero-risk, educational-first introduction to Web3 on **Mezo Bitcoin L2**  
Be Your Own Bank – Math Mint Mezo Edition  

[![Mezo Hackathon](https://img.shields.io/badge/Mezo-Hackathon-2025-blue)](https://mezo.org)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
[![Live Demo](https://img.shields.io/badge/demo-play%20now-brightgreen)](https://shipbulldj.github.io/Math-mint-bank/)  
[![Contracts](https://img.shields.io/badge/contracts-mathmint--quiz-orange)](https://github.com/shipbulldj/mathmint-quiz)  

## 🚀 One-Liner
A fun multiplication quiz for 8–14 yr olds that rewards perfect rounds with **achievement NFT badges** on Mezo testnet — **zero wallet required to play**, zero financial risk, 100% privacy.

## 🎯 Problem We Solve
- Web3 onboarding = scary (gas, scams, complexity)  
- Math practice apps = boring + sell kids’ data  
- NFTs = speculation, not learning  

**Target:** 980M kids • 1.09B parents • 44M teachers → **207M potential Mezo users in 5 years**

## 🛠️ Tech Stack
| Layer       | Technology                                                            |
|-------------|-----------------------------------------------------------------------|
| Blockchain  | Mezo Bitcoin L2 (EVM-compatible, low gas, Bitcoin security)          |
| Contracts   | Solidity 0.8.24 → `QuizContract` + `MathMintNFT` (ERC-721)            |
| Frontend    | React 18 + Vite + Tailwind CSS (retro arcade theme)                   |
| Web3        | ethers.js v6 + wagmi + viem                                           |
| Wallets     | MetaMask • Unisat • Leather                                           |
| Hosting     | GitHub Pages (demo) → IPFS + custom domain (Phase 2)                   |
| Storage     | On-chain scores + IPFS metadata                                       |

### Deployed Contracts (Mezo Testnet)
QuizContract:   0x59bDB59107f29e9712A37c7015ee28675DD7d30f
MathMintNFT:    0x03672f6b20622176554a4C0ba7B037d9dCE531f0
text→ Full source + Hardhat config: https://github.com/shipbulldj/mathmint-quiz

## 🎮 How It Works
### Casual Player (No Wallet)
1. Visit https://shipbulldj.github.io/Math-mint-bank/  
2. Instant play – 5 random × questions (1–10)  
3. 15-sec timer ⏱️  
4. Score: +10 correct, -1 wrong (min 0)  
5. Leaderboard + optional wallet connect  

### Web3 Explorer
1. Connect wallet (MetaMask / Unisat / Leather)  
2. Scores saved on Mezo blockchain  
3. ≥50 pts → Mint NFT badge (gas < $0.01)  
4. Badge = permanent proof of math mastery  

**NFTs are achievement-only** – non-tradeable (soulbound option in Phase 3)

## 🏗️ Project Structure
mathmint-quiz/          ← Smart contracts + tests
└── contracts/
├── QuizContract.sol
└── MathMintNFT.sol

Math-mint-bank/         ← Demo frontend (this repo)
├── src/
│   ├── components/Quiz.tsx
│   └── App.tsx
├── public/
└── vite.config.ts

text## 🚀 Quick Start
```bash
# 1. Clone both repos
git clone https://github.com/shipbulldj/mathmint-quiz.git
git clone https://github.com/shipbulldj/Math-mint-bank.git

# 2. Run demo
cd Math-mint-bank
npm install
npm run dev
# → http://localhost:5173
Deploy to GitHub Pages
bashnpm run deploy
# Auto-pushes to gh-pages → https://shipbulldj.github.io/Math-mint-bank/
🎨 Live Demo
https://shipbulldj.github.io/Math-mint-bank/
Play instantly – no install, no wallet needed!
🌍 Why Mezo?

Bitcoin security → parents trust it
Sub-cent gas → kids can mint without allowance
Fast finality → instant feedback in class
EVM compatibility → built in <48h

🗺️ Roadmap


Phase Milestone MVP (Now)
  Quiz + NFT mint on testnet
Phase 2
  IPFS hosting,mathmint.xyz domain,mobile PWA
Phase 3 
  Daily streaks, difficulty levels, teacher dashboardsPhase 4Security audit + Mezo mainnet launch + school pilots

👥 Contributing

Fork mathmint-quiz (contracts) or Math-mint-bank (frontend)
Create branch feat/your-feature
PR with clear title + demo GIF

We welcome:

Retro pixel art
Translations (Spanish, Hindi, Arabic…)
Teacher feedback forms

📜 License
MIT © 2025 shipbulldj
⭐ Star us if math + Bitcoin = the future!
One badge at a time → 207 million new Mezo wallets.
Play now – scan QR:
<img src="https://api.qrserver.com/v1/create-qr-code/?size=220x220&#x26;data=https://shipbulldj.github.io/Math-mint-bank/" alt="Play Now">
Built with ❤️ for Mezo Hackathon – November 2025
