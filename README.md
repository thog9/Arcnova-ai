# ArcNova - Daily Check-in 🌟

This script automates daily check-in on the **ArcNova** platform — a Web3 TV ecosystem where users earn points by completing daily tasks using Ethereum wallet authentication.

🔗 Register: [ArcNova](https://arcnova.tv/en/tasks?inviter=5U2GUGX326ES)

---

## ✨ Features Overview

### General Features

- **Multi-Account Support**: Reads Ethereum private keys from `pvkey.txt` to process multiple wallets in parallel.
- **Colorful CLI**: Uses `colorama` for visually appealing output with box-drawing borders and colored icons.
- **Asynchronous Execution**: Built with `asyncio` for efficient concurrent task processing (configurable thread count).
- **Error Handling**: Comprehensive error catching with retry logic (configurable attempts) for API failures.
- **Bilingual Support**: Supports both English and Vietnamese output.
- **Proxy Support**: Supports SOCKS5/HTTP proxies via `proxies.txt` (`host:port:user:pass` format).

---

### Included Scripts

✨ **Check-in Bot** (`checkin-arcnova.py`)

- ✅ Automatic daily check-in (taskId: 7)
- ✅ EIP-4361 auto sign-in — getNonce → sign message → login → check-in
- ✅ Current points balance display
- ✅ "Already checked in" detection
- ✅ Proxy & multi-threading support

---

## 🛠️ Prerequisites

Before running the scripts, ensure you have the following installed:

- **Python 3.8+**
- **pip** (Python package manager)
- **Dependencies**: Install via `pip install -r requirements.txt`
- **pvkey.txt**: Add Ethereum private keys (one per line) — with or without `0x` prefix
- **proxies.txt** (optional): Add proxy addresses for network requests

---

## 📦 Installation

1. **Clone or download this repository:**
   ```sh
   git clone https://github.com/thog9/Arcnova-ai.git
   cd Arcnova-ai
   ```

2. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Prepare Input Files:**

   Create `pvkey.txt` in the root directory with Ethereum private keys (one per line):
   ```
   0x999...
   0x999...
   ```

   Create `proxies.txt` (optional) — one proxy per line:
   ```
   socks5://user:pass@host:port
   http://user:pass@host:port
   host:port:user:pass
   ```

4. **Run:**
   ```sh
   python main.py
   ```
   - Choose a language (Vietnamese / English).
   - Select the script you want to run.

**Language Selection:**
- Choose between Vietnamese (Tiếng Việt) and English.
- All scripts support bilingual output.

---

## 📁 Project Structure

```
Arcnova-ai/
├── main.py             # Central menu system
├── pvkey.txt           # EVM private keys (one per line)
├── proxies.txt         # Proxies (optional)
├── README.md           # This file
└── scripts/            # Individual scripts
    └── checkin.py      # Task Check-in automation bot

```

---

## 📨 Contact

Connect with us for support or updates:

- **Telegram**: [thog099](https://t.me/thog099)
- **Channel**: [CHANNEL](https://t.me/thogairdrops)
- **Group**: [GROUP CHAT](https://t.me/thogchats)
- **X**: [Thog](https://x.com/thog099)

---

## ☕ Support Us

Love these scripts? Fuel our work with a coffee!

🔗 BUYMECAFE: [BUY ME CAFE](https://buymecafe.vercel.app/)

🔗 WEBSITE: [BUY SCRIPTS](https://thogtoolhub.com/)
