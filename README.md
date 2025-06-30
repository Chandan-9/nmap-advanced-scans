# nmap-advanced-scans
Advanced Nmap scanning on Metasploitable 2 using Kali Linux
# 🔍 Advanced Nmap Scanning on Metasploitable 2

## 🔧 Lab Setup
- Attacking Machine: Kali Linux
- Target Machine: Metasploitable 2
- Network Type: Host-only (VirtualBox)

## ✅ Scans Performed

| Scan Type           | Command Example                      |
|---------------------|--------------------------------------|
| Ping Scan           | `nmap -sn 192.168.1.0/24`            |
| Stealth Scan        | `nmap -sS target-ip`                 |
| Full TCP Scan       | `nmap -sT -p- target-ip`             |
| Aggressive Scan     | `nmap -A target-ip`                  |
| FIN Scan            | `nmap -sF target-ip`                 |
| UDP Scan            | `nmap -sU target-ip`                 |
| Script Vulnerability| `nmap --script vuln target-ip`       |
| Version Detection   | `nmap -sV target-ip`                 |
| Random Host Order   | `nmap --randomize-hosts target-ip`  |
| IP Decoy Scan       | `nmap --decoy 10.10.10.1 target-ip` |

## 📸 Screenshots & Outputs
Find the results in the `/scan-results` and `/screenshots` folders.

## 🧠 Key Learning:
Each scan reveals different layers of a system's behavior and security posture. Understanding when and why to use them is key in real-world penetration testing.

