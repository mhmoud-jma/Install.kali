# ⚙️ Kali Linux Installer for Termux (Auto Toolkit) – v3

A powerful and ready-to-use Kali Linux installer for Termux, featuring essential Red Team tools — now upgraded with **v3** including three different installation methods, command-line flexibility, and improved support for Termux.

---

## 🚀 New in v3

- ✅ Switched from `pkg` to `apt` for better compatibility with Termux
- ✅ Added error handling for missing Kali installation
- ✅ Includes 3 different installation methods for Kali
- ✅ Clear fallback when auto-install fails
- ✅ Clean interface without color bugs on Termux
- ✅ Menu now shows manual install instructions if needed

---

## 📦 What's Inside?

- `menu.sh` → Main interactive launcher (auto-installer + tools)
- `kali.sh` → Automates Kali installation (method-based)
- `tools/install-tools.sh` → Installs tools like `nmap`, `sqlmap`, `metasploit`, etc.
- `T.DROP` → Custom Red Team tool from this repo  
  → [T.DROP GitHub](https://github.com/mhmoud-jma/T.DROP)

---

## 📸 Screenshots

### 🔹 Main Menu
![Main Menu](photos/Interface.jpg)
### 🔹 Run kali
![Run kali](https://github.com/mhmoud-jma/Install.kali/blob/main/Termux%202.jpg)

To see more screenshots, please visit:(https://github.com/mhmoud-jma/Install.kali/commit/26a59c70124f2e2844666f2b29e58fae783046a3#diff-58916ba9f6962785eaba9773a9a50145633cd8917b32a5c87f80e1440f9343f7)
---

## 📥 How to Install

### 1. Download and Run the Project

```bash
apt update && apt upgrade 
apt install proot
git clone https://github.com/mhmoud-jma/Install.kali.git
cd Install.kali
chmod +x install.sh
bash install.sh
```
### 1.1 You may have a problem with the key. 
 ```bash
apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 827C8569F2518CC677FECA1AED65462EC8D5E4C5
```

### 2. Run the Installer Menu Manually

chmod +x install.sh
bash install.sh


---

### 🧰 Available Tools

Recon:
```
nmap, whois, amass, dnsutils, recon-ng, theHarvester
```
Scanning:
```
whatweb, nikto, wafw00f
```
Exploitation:
```
sqlmap, metasploit-framework, hydra
```
Password Cracking:
```
john, crunch
```
Phishing:
```
zphisher, HiddenEye, SocialFish
```
Extras:
```
T.DROP → https://github.com/mhmoud-jma/T.DROP
```

---

🔧 Manual Tool Installation (if auto fails)

If the tools fail to install automatically, you can run this inside Kali:
```
sudo apt update
sudo apt install -y nmap whois dnsutils net-tools whatweb nikto wafw00f theharvester recon-ng amass sqlmap metasploit-framework hydra john crunch
```
And clone phishing tools manually:
```
git clone https://github.com/htr-tech/zphisher
git clone https://github.com/DarkSecDevelopers/HiddenEye
git clone https://github.com/UndeadSec/SocialFish
git clone https://github.com/mhmoud-jma/T.DROP
```

---

###⭐ Support This Project

If you find this project helpful, please consider giving it a ⭐ on GitHub:
👉 https://github.com/mhmoud-jma/Install.kali


---

###⚠️ Disclaimer

> This script is for educational purposes only. The author is not responsible for any misuse.
Please use ethically and responsibly.




---

📄 License

This project is licensed under the MIT License – see the LICENSE file for details.


---

👨‍💻 Author

Mahmoud Jmaiel
Red Team enthusiast & cybersecurity student
GitHub: @mhmoud-jma
