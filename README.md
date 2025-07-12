# 🛡️ Linux Firewall with iptables

This project demonstrates how to build a secure, default-deny firewall using `iptables` on a Linux system like Kali or Ubuntu. It includes a script to automate the setup, and instructions to test it with `nmap`.

## 🎯 Features

- Denies all inbound traffic by default
- Allows specific ports: `SSH (22)`, `HTTP (80)`, `HTTPS (443)`
- Accepts loopback and related/established connections
- Persists firewall rules with `iptables-persistent`
- Validated using real-world scanning (`nmap`)

## 🧰 Tools Used

- `iptables`
- `iptables-persistent`
- `nmap`
- Bash

## 📂 Files

- `firewall-setup.sh` – script to apply the firewall rules
- `README.md` – this documentation

## 🚀 How to Use

1. Clone the repo:

```bash
git clone https://github.com/Ajul55/iptables-firewall-project.git
cd iptables-firewall-project
chmod +x firewall-setup.sh
