# 🧑‍💻 Shnouda’s Admin Tool

[![Bash](https://img.shields.io/badge/Language-Bash-blue.svg)](https://www.gnu.org/software/bash/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Linux-lightgrey.svg)](#)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)](#)

---

## 🎯 Overview

**Shnouda’s Admin Tool** is a **Bash-based Linux administration utility** that provides an **interactive and colorful command-line interface** for managing users and groups.  
It simplifies system administration tasks by combining essential user and group management operations into one script with an easy-to-use menu.

This project demonstrates **Bash scripting**, **menu-driven automation**, **color formatting**, and **user/group management** commands with secure handling.

---

## 🌟 Features

### 👤 User Management
- Add, modify, delete, and list users  
- Automatically filters human users (UID ≥ 1000)

### 👥 Group Management
- Add, modify, delete, and list groups

### 🔐 Account Control
- Lock (disable) or unlock (enable) user accounts securely

### 🔑 Password Management
- Change user passwords easily via interactive menu

### 🧭 Interactive Menu
- Simple menu-driven system using the `select` command  
- Colorful and clear terminal output with animations

### 🖥️ Visuals
- Displays **ASCII art banner** and a **spinner animation** at startup

### 🛡️ Security
- Requires **root privileges**, ensuring administrative safety

---

## 📂 Project Structure

Bash-Script/
│
├── print_SHNOUDA.sh # Main script (menu interface)
│
└── scripts/ # Sub-scripts for each operation
├── useradd
├── usermod
├── deluser
├── listusers
├── groupadd
├── groupmod
├── groupdel
├── listgroups
├── lockacc
├── unlookacc
├── changpass
└── about

## ⚙️ Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/Bash-Script.git
cd Bash-Script
```
## 2️⃣ Give Execution Permission
```bash
chmod +x print_SHNOUDA.sh
chmod +x scripts/*
```
## 3️⃣ Run the Script (as root)
```bash
sudo ./print_SHNOUDA.sh
```
### 🧩 Example Terminal Output
```bash
  ____   _   _  _   _   _____   _   _  ____   ____    _    
 / ___| | | | || \ | | /  _  \ | \ | ||  _ \ |  _ \  / \   
 \___ \ | |_|_||  \| ||  / \  ||  \| || | | || | | |/ _ \  
  ___) || |_| || |\  ||  \_/  || |\  || |_| || |_| / ___ \ 
 |____/ |_| |_||_| \_| \_____/ |_| \_||____/ |____/_/   \_\ 

Loading... please wait
-/|\*-/|\*-/|\*-/|\*-/|\*

This script was made by: 
🟢🟡🔴 Shnouda 🔵🟣💻

```
🧭 Interactive Menu Example

After the spinner animation, the interactive menu appears:
```bash
shnouda> 1) Add User
          2) Modify User
          3) Delete User
          4) List Users
          5) Add Group
          6) Modify Group
          7) Delete Group
          8) List Groups
          9) Disable User
          10) Enable User
          11) Change Password
          12) About
          13) Exit

```
Each selection triggers a dedicated script from the scripts/ folder.
For example:

Selecting “Add User” runs ./scripts/useradd

Selecting “List Users” runs ./scripts/listusers

Selecting “About” runs ./scripts/about

👨‍💻 Author

Developed by: Shnouda Nabil

🛠️ Programmer • Security Engineer • Linux Enthusiast

📜 License

This project is licensed under the MIT License — you are free to use, modify, and distribute it.
See the LICENSE
 file for details.

💫 Support

If you find this project useful, please consider:

⭐ Starring the repository on GitHub

🐛 Reporting bugs or suggestions via Issues

🔄 Contributing improvements via Pull Requests
