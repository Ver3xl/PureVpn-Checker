<div align="center">

  <h1>🛡️ PureVPN Account Checker</h1>
  
  <p>
    A robust, multi-threaded tool to check PureVPN accounts with high speed and accuracy.
  </p>

  <p>
    <img src="https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-green?style=for-the-badge&logo=linux&logoColor=white" alt="Platform" />
    <img src="https://img.shields.io/badge/License-MIT-purple?style=for-the-badge" alt="License" />
  </p>

  <h4>
    <a href="#-features">Features</a> •
    <a href="#-installation">Installation</a> •
    <a href="#-usage">Usage</a> •
    <a href="#-community--support">Support</a>
  </h4>
</div>

---

## 🔗 Community & Support

> [!NOTE]
> Join our community regarding updates and support!

*   Telegram: [t.me/meowleak](https://t.me/meowleak)
*   Discord: [discord.gg/a4PxpEMFcf](https://discord.gg/a4PxpEMFcf)

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

---

<div align="center">
  <p>Made with ❤️ by <a href="https://github.com/Ver3xl">Ver3xl</a></p>
</div>
