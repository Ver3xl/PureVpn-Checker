<div align="center">

  <h1>🛡️ PureVPN Account Checker</h1>
  
  <p>
    A robust, multi-threaded tool to check PureVPN accounts with high speed and accuracy.
  </p>

  <p>
    <a href="https://github.com/purevpn-checker/graphs/contributors">
      <img src="https://img.shields.io/github/contributors/vishal/purevpn-checker?style=for-the-badge&color=blue" alt="Contributors" />
    </a>
    <a href="https://github.com/purevpn-checker/network/members">
      <img src="https://img.shields.io/github/forks/vishal/purevpn-checker?style=for-the-badge&color=orange" alt="Forks" />
    </a>
    <a href="https://github.com/purevpn-checker/stargazers">
      <img src="https://img.shields.io/github/stars/vishal/purevpn-checker?style=for-the-badge&color=yellow" alt="Stars" />
    </a>
    <a href="https://github.com/purevpn-checker/issues">
      <img src="https://img.shields.io/github/issues/vishal/purevpn-checker?style=for-the-badge&color=red" alt="Issues" />
    </a>
    <a href="https://github.com/purevpn-checker/blob/master/LICENSE.txt">
      <img src="https://img.shields.io/github/license/vishal/purevpn-checker?style=for-the-badge&color=green" alt="License" />
    </a>
  </p>

  <h4>
    <a href="#-features">Features</a> •
    <a href="#-installation">Installation</a> •
    <a href="#-usage">Usage</a> •
    <a href="#-community--support">Support</a>
  </h4>
</div>

---

## ⚡ Features

*   **🚀 Multi-threaded**: Process thousands of accounts efficiently utilizing full CPU power.
*   **🧠 Smart Classification**: Automatically sorts accounts into folders:
    *   `Hits`: Active Premium Subscriptions
    *   `Free`: No Active Plan / Expired Trial
    *   `Expired`: Previously Paid, Now Expired
*   **🕵️ Smart Expiry Detection**: Advanced logic identifies expired plans even on `404` API responses.
*   **🔒 Proxy Support**: Full support for `HTTP`, `HTTPS`, `SOCKS4`, and `SOCKS5` with authentication.
*   **💻 Cross-Platform**:
    *   `main.py` for **Windows** (Console Title Stats)
    *   `Main_Linux.py` for **Linux/VPS** (ANSI Title Updates)

## 🛠️ Installation

1.  **Install Python 3.10+**  
    Ensure you have Python installed and added to PATH.

2.  **Install Dependencies**  
    Run the following command in your terminal:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Usage

### 1. Prepare your files
*   **Combos**: Add your `email:password` list to `combos.txt`.
*   **Proxies**: Add your proxies to `proxies.txt`.
    *   Supported formats: `ip:port` or `user:pass@ip:port`

### 2. Run the Checker

#### 🪟 Windows
```bash
python main.py
```

#### 🐧 Linux / VPS
```bash
python3 Main_Linux.py
```

## 🔗 Community & Support

> **Note**  
> Join our community for updates, configs, and support!

<div align="left">
  <a href="https://t.me/meowleak">
    <img src="https://img.shields.io/badge/Telegram-Join%20Channel-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
  <a href="https://discord.gg/a4PxpEMFcf">
    <img src="https://img.shields.io/badge/Discord-Join%20Server-7289DA?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  </a>
</div>

---

<div align="center">
  <p>Made with ❤️ by <a href="https://github.com/Ver3xl">Ver3xl</a></p>
</div>
