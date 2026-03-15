# 🔐 CheckMatch — Crypto Wallet Address Verifier

> **Bảo vệ bạn khỏi lừa đảo clipboard hijacking & address poisoning.**  
> Verify every crypto wallet address before sending.

🌐 **Live Demo**: [checkmatch on GitHub Pages](#) *(update URL after deploy)*

---

## ✨ Features

- 🔍 **Character-by-character comparison** — highlights every single diff
- 🚨 **Smart Risk Detection**: 🟢 SAFE / 🟡 WARNING / 🔴 DANGER (poisoning attack)
- ⛓️ **Auto-detects blockchain**: ETH/EVM · BTC · Solana · TRON · BNB
- 📎 **One-click clipboard paste**
- 🌐 **Bilingual**: Vietnamese 🇻🇳 + English 🇺🇸
- 🎨 **Dark glassmorphism UI** — zero dependencies, pure HTML/CSS/JS

---

## 🚀 Deploy on GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **main branch / root (`/`)**
4. Your site is live at `https://<username>.github.io/<repo>`

---

## 🧪 How it works

| Scenario | Result |
|---|---|
| Addresses identical | 🟢 SAFE (100%) |
| Prefix/suffix match, middle differs | 🔴 DANGER (classic poisoning) |
| Any other mismatch | 🟡 WARNING |

---

*Built with ❤️ to fight crypto scams. Open source, free forever.*
