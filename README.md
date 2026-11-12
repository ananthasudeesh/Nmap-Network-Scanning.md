🔍 Nmap Network Scanning

🔐 Learn | Practice | Investigate | Defend

A beginner-friendly guide to network scanning, host discovery, port identification, and service detection using Nmap.

Author: Anantha Sudeesh SD  
Category: Network Security | Blue Team  
Tool: Nmap

---

🔍 What Is Nmap?

Nmap (Network Mapper) is an open-source tool used to discover network devices, identify open ports, detect running services, and analyze network exposure.

🎯 Why Use Nmap?

- Discover active hosts.
- Identify open and closed ports.
- Detect services and versions.
- Audit network security.
- Identify unexpected network exposure.

💻 Essential Nmap Commands

| Command | Purpose |
|---|---|
| `nmap --version` | Check Nmap version |
| `nmap 127.0.0.1` | Scan localhost |
| `nmap -sn 192.168.1.0/24` | Discover active hosts |
| `nmap -p 22,80,443 TARGET` | Scan specific ports |
| `nmap -p- TARGET` | Scan all TCP ports |
| `nmap -sV TARGET` | Detect service versions |
| `sudo nmap -O TARGET` | Detect operating system |
| `nmap -oN results.txt TARGET` | Save scan results |

Replace `TARGET` with an authorized IP address or hostname.

📊 Understanding Port States

| State | Meaning |
|---|---|
| Open | Service is accepting connections |
| Closed | No service is listening |
| Filtered | Firewall or network filtering prevents a clear result |

🧪 Practical Exercises

1. Scan your local machine using `nmap 127.0.0.1`.
2. Discover active devices on your authorized lab network.
3. Identify open ports and running services.
4. Save and analyze scan results.

🛡️ Blue Team Applications

- Network asset discovery
- Open-port auditing
- Service identification
- Network exposure assessment
- Security investigation support

📚 Learning Resources

- [Nmap Official Website](https://nmap.org/)
- [Nmap Reference Guide](https://nmap.org/book/man.html)
- [TryHackMe](https://tryhackme.com/)

⚖️ Disclaimer

For educational and defensive security purposes only. Scan systems only when you own them or have explicit authorization.

---

🔐 Learn | Practice | Investigate | Defend
