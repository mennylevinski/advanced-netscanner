# 🔍 Secuditor Network Scanner

A lightweight, open-source Python tool for discovering devices on your local network.  
Built for **ethical diagnostics**, **security awareness**, and **administrative auditing**.

---

## 🚀 Features

- 🌐 **Automatic Subnet Detection** – Finds your local IP and scans the connected network.
- ⚡ **Fast & Accurate** – Combines ICMP, ARP, and socket checks.
- 🔎 **Open Port Detection** – Scans common service ports (FTP, SSH, SMB, HTTP, RDP, etc.).
- 🧩 **Custom Range Scanning** – Choose between entire subnet or a specific range.
- 🧠 **Input Validation** – Falls back safely if you mistype an IP or range.
- 🧱 **Console Mode** – Clean “black console” output; stays open after completion.
- 🚫 **Risk Highlighting** – Marks known vulnerable ports with “!!”.
- 🧾 **No Dependencies** – 100% Python standard library.

---

## 🧠 Technical Details

- Detects local IP and gateway automatically.

- Uses ICMP ping, ARP requests, and socket connections for discovery.

- Gracefully handles incorrect input and network errors.

- Displays structured tabular results with separators.

- Keeps the console open after finishing (pause on Windows).

---

## ⚙️ Installation

### 1️ Requirements
- Python **3.8+**
- Works on **Windows**, **Linux**, and **macOS**
- No external packages required

### 2️ Download & Run
