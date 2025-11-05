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

## 🧰 Example Output

Running scan.. Scanned subnet: 192.168.11.0/24 — found 2 devices
IP Hostname MAC Alive Open Ports
192.168.11.112 - 1c:69:7a:a1:49:a7 True 139(NetBIOS), 445(SMB), 338... !!
192.168.11.254 - 90:6c:ac:a9:6e:ed True 22(SSH), 80(HTTP)

Scan finished successfully.
Press any key to close...

---

## ⚙️ Installation

### 1️.Requirements
- Python **3.8+**
- Works on **Windows**, **Linux**, and **macOS**
- No external packages required

### 2️. Download & Run
