# ⚙️ Kali Linux Installer for Termux (Auto Toolkit)

A ready-to-use Kali Linux installer for Termux, packed with essential Red Team tools. Download, extract, run — and you're in.

---

## 🚀 Features

- Install Kali Linux in one click inside Termux
- Interactive tools menu with 20+ Red Team tools
- Run all tools or install one by one
- Simple terminal interface (menu-based)
- Fully offline setup after downloading

---

## 📦 What's Inside?

- `menu.sh` → Main interactive launcher
- `kali.sh` → Automates Kali installation
- `tools/install-tools.sh` → Installs tools like `nmap`, `sqlmap`, `metasploit`, etc.
- `T.DROP` → A custom Red Team tool from this repo  
  → [T.DROP GitHub](https://github.com/mhmoud-jma/T.DROP)
## 📸 Screenshots

### 🔹 Main Menu
![Main Menu](https://github.com/mhmoud-jma/Install.kali/blob/main/Termux%201.jpg)

### 🔹 Run kali
![Run kali](https://github.com/mhmoud-jma/Install.kali/blob/main/Termux%202.jpg)

## 📥 How to Install

### 1. Download the Project

```bash
dpkg --configure -a
y
apt update && apt upgrade
apt install unzip
git clone https://github.com/mhmoud-jma/Install.kali.git
cd /Install.kali
unzip kali-installer.zip
cd kali
chmod +x menu.sh
bash menu.sh

```
---
### 2. Run the Installer Menu

chmod +x menu.sh

bash menu.sh

🧰 Available Tools

Recon: nmap, whois, amass, dnsutils, recon-ng, theHarvester

Scanning: whatweb, nikto, wafw00f

Exploitation: sqlmap, metasploit, hydra

Password Cracking: john, crunch

Phishing: zphisher, HiddenEye, SocialFish

Extras: T.DROP



---

⭐ Support This Project

If you find this project helpful, please consider giving it a ⭐ on GitHub:

👉 https://github.com/mhmoud-jma/Install.kali


---

⚠️ Disclaimer

> This script is for educational purposes only. The author is not responsible for any misuse.
Please use ethically and responsibly.



---
## License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

👨‍💻 Author

Mahmoud Jmaiel
Red Team enthusiast & cybersecurity student
GitHub: @mhmoud-jma
