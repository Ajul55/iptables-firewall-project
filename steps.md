# 🧾 Project Execution Log – Kali Linux Firewall with iptables

### Environment:
- Kali Linux 2025.2 (VM)
- GitHub repo: [Ajul55/iptables-firewall-project](https://github.com/Ajul55/iptables-firewall-project)

---

## 🛠️ Steps Performed

1. Created a new project folder and bash script
2. Set default policies: DROP inbound, ACCEPT outbound
3. Allowed essential traffic (22, 80, 443)
4. Added loopback and stateful return rule
5. Enabled `iptables-persistent` for rule saving
6. Started SSH and Apache services using `systemctl`
7. Used `nmap -sT` to verify firewall rule behavior
8. Fixed DNS and networking issues (resolv.conf)
9. Generated and used GitHub personal access token
10. Pushed to GitHub with `git add`, `commit`, `push`

---

## 🔍 Notes

- `nmap` showed "closed" ports until services were started
- `iptables -L -v` helped confirm which rules were active
- Persistence required `iptables-persistent` package

