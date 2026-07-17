<!-- 
  ╔══════════════════════════════════════════════════════════════╗
  ║  PATRIXX RECON FRAMEWORK v2.0 — github.com/Prateek-squadron ║
  ╚══════════════════════════════════════════════════════════════╝
-->

<div align="center">

```
██████╗   █████╗  ████████╗ ██████╗  ██╗ ██╗  ██╗ ██╗  ██╗
██╔══██╗ ██╔══██╗ ╚══██╔══╝ ██╔══██╗ ██║ ╚██╗██╔╝ ╚██╗██╔╝
██████╔╝ ██████╔╝    ██║    ██████╔╝ ██║  ╚███╔╝   ╚███╔╝
██╔═══╝  ██╔══██╗    ██║    ██╔══██╗ ██║  ██╔██╗   ██╔██╗
██║      ██║  ██║    ██║    ██║  ██║ ██║ ██╔╝ ██╗ ██╔╝ ██╗
╚═╝      ╚═╝  ╚═╝    ╚═╝    ╚═╝  ╚═╝ ╚═╝ ╚═╝  ╚═╝ ╚═╝  ╚═╝
```

**`RECON FRAMEWORK v2.0`** &nbsp;|&nbsp; `Cybersecurity & Digital Forensics` &nbsp;|&nbsp; `Root Access to Life`

[![LinkedIn](https://img.shields.io/badge/OSINT%20LEAD-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prateek-sharma-cyber/)
[![Twitter](https://img.shields.io/badge/SIGINT-X%20%2F%20Twitter-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/Prateek26087)
[![Email](https://img.shields.io/badge/ENCRYPTED%20CHANNEL-Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ps.prateek1709@gmail.com)
[![Discord](https://img.shields.io/badge/COMMS-ferrarisf90stradale-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.com)
[![Portfolio](https://img.shields.io/badge/SHELL-patrixx.dev-00ff41?style=flat-square&logo=gnometerminal&logoColor=white)](https://prateek-squadron.github.io/portfolio)

</div>

---

```
patrixx@recon:~$ ./scan.sh --target "Prateek Sharma" --mode full --verbose
```

```
╔══════════════════════════════════════════════════════════════════════════════╗
║  PATRIXX RECON FRAMEWORK v2.0 — Full Spectrum Reconnaissance Report        ║
║  Target: Prateek Sharma | Codename: PATRIXX                               ║
║  Scan initiated: $(date) | Status: ACTIVE                                 ║
╚══════════════════════════════════════════════════════════════════════════════╝

[*] Phase 1: Initializing scan modules...
[+] OSINT module ............... LOADED
[+] Network recon module ....... LOADED
[+] Forensics module ........... LOADED
[+] Cloud scan module .......... LOADED
[+] Social engineering module .. LOADED
[*] All modules operational. Beginning reconnaissance...
```

---

### `📡 PHASE 1 — TARGET PROFILE`

```
┌─────────────────────────────────────────────────────────────┐
│ SUBJECT IDENTIFICATION                                      │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  Name ........... Prateek Sharma                            │
│  Alias .......... PATRIXX                                   │
│  Location ....... VIT Bhopal, India                         │
│  Classification . B.Tech — Cybersecurity & Digital Forensics│
│  Status ......... 2nd Year | 3rd Semester                   │
│  Threat Level ... ████████████████████░░ 90%  [ELEVATED]    │
│                                                             │
│  [!] Subject operates primarily from Linux environments     │
│  [!] Confirmed Arch Linux user (btw)                        │
│  [!] Distro history: Mint → Fedora → Debian → Tails →      │
│      NixOS → Pop!_OS → Arch (settled)                       │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

### `🔍 PHASE 2 — PORT SCAN (SKILL SERVICES DETECTED)`

```
patrixx@recon:~$ nmap -sV -sC -p- prateek-sharma --script=skills-enum

Starting Nmap 7.94 ( https://nmap.org ) at 2025-XX-XX XX:XX IST
Nmap scan report for prateek-sharma (127.0.0.1)
Host is up (0.00042s latency).

PORT      STATE  SERVICE              VERSION
═══════════════════════════════════════════════════════════════════
22/tcp    open   linux-mastery        Arch Linux 6.x (Hardened Kernel)
                                      ├─ Distro Competency: ALL
                                      ├─ Shell: bash/zsh (dual wield)
                                      └─ Terminal: Alacritty / Kitty
                                      
80/tcp    open   osint-recon          PATRIXX-Scanner/2.0
                                      ├─ Nmap, Burp Suite Pro, Shodan
                                      ├─ OSINT Toolchain (full stack)
                                      └─ 2x CTF Completions
                                      
443/tcp   open   network-security     TCP/IP + OSI Model Expert
                                      ├─ OWASP Top 10 (familiar)
                                      ├─ Wireshark Protocol Analysis
                                      └─ Firewall/IDS Concepts

993/tcp   open   digital-forensics    Autopsy/Volatility/Splunk
                                      ├─ Memory Forensics (theoretical)
                                      ├─ Steganography Detection
                                      └─ THM: Splunk Room ✓
                                      
3306/tcp  open   python-arsenal       Python 3.x (Primary Weapon)
                                      ├─ Scripting & Automation
                                      ├─ Tool Development
                                      └─ API Integration
                                      
5432/tcp  open   cloud-devops         Azure + Docker + Tailscale
                                      ├─ Full Cloud Deployment
                                      ├─ Containerization (Docker)
                                      └─ VirtualBox / VMware

8080/tcp  open   web-development      Full-Stack (Vibe-Coded)
                                      ├─ HTML / CSS / JavaScript
                                      ├─ Flask / API Integration
                                      └─ SQL / Database Management

8443/tcp  open   ai-ml-foundations    Basic Fundamentals
                                      ├─ Model Understanding
                                      └─ Applied Use Cases
                                      
9090/tcp  open   automotive-intel     GOD-TIER ████████████ 99%
                                      ├─ Engine Tech & Dynamics
                                      ├─ Lexus LFA V10 Specialist
                                      └─ Chassis & Ballistics
═══════════════════════════════════════════════════════════════════

Nmap done: 1 host scanned, 9 services detected, 0 filtered
[+] Subject classified as: JACK OF ALL TRADES
```

---

### `🛠️ PHASE 3 — ARSENAL INVENTORY`

<div align="center">

#### `// OFFENSIVE TOOLS`
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite_Pro-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge&logo=nmap&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)

#### `// LANGUAGES & SCRIPTING`
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash/Zsh-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

#### `// INFRASTRUCTURE`
![Arch](https://img.shields.io/badge/Arch_Linux_(btw)-1793D1?style=for-the-badge&logo=archlinux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-000000?style=for-the-badge&logo=tailscale&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

#### `// FORENSICS & SIEM`
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![Volatility](https://img.shields.io/badge/Volatility-333333?style=for-the-badge&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)

</div>

---

### `🎯 PHASE 4 — ACTIVE EXPLOITS (PROJECTS)`

```
patrixx@recon:~$ cat /var/log/exploits.log
```

<table>
<tr>
<td width="50%">

#### 🔥 `hyprconf2lua` — _FEATURED_
> Convert Hyprland `.conf` → Lua for `v0.55+`
> ~97% auto-conversion accuracy, 0% guesswork.
> Used by the Arch/Hyprland community.

[![Stars](https://img.shields.io/github/stars/Prateek-squadron/hyprconf2lua?style=flat-square&color=gold&label=★%20Stars)](https://github.com/Prateek-squadron/hyprconf2lua)
[![Language](https://img.shields.io/badge/🐍-Python-3776AB?style=flat-square)](https://github.com/Prateek-squadron/hyprconf2lua)

</td>
<td width="50%">

#### 🛡️ `OSINT Threat Intel Platform` — _IN PROGRESS_
> Automated OSINT reconnaissance & threat intelligence
> aggregation platform. Multi-API, risk scoring,
> PDF reports, Dockerized deployment.

[![Status](https://img.shields.io/badge/Status-In%20Development-yellow?style=flat-square)]()
[![Language](https://img.shields.io/badge/🐍-Python%20+%20Flask-3776AB?style=flat-square)]()

</td>
</tr>
</table>

```
[+] 2 active exploits found. More in development...
[*] Run 'ls -la /projects/' on profile for full inventory.
```

---

### `📊 PHASE 5 — INTELLIGENCE DASHBOARD`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Prateek-squadron&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=ff0040&text_color=c9d1d9&ring_color=00ff41" width="48%" />
<img src="https://streak-stats.demolab.com?user=Prateek-squadron&theme=radical&hide_border=true&background=0D1117&ring=00FF41&fire=FF0040&currStreakLabel=00FF41&sideLabels=C9D1D9&dates=555555" width="48%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Prateek-squadron&layout=compact&theme=radical&hide_border=true&bg_color=0d1117&title_color=00ff41&text_color=c9d1d9" width="40%" />

</div>

---

### `📡 PHASE 6 — EXTRACTED INTEL (CONTACT)`

```
╔══════════════════════════════════════════════════════════════╗
║  COMMUNICATION CHANNELS — ACTIVE                           ║
╠══════════════════════════════════════════════════════════════╣
║                                                            ║
║  🐙 GitHub ....... github.com/Prateek-squadron             ║
║  🔗 LinkedIn ..... linkedin.com/in/prateek-sharma-cyber    ║
║  🐦 X/Twitter .... x.com/Prateek26087                     ║
║  💬 Discord ...... ferrarisf90stradale                     ║
║  ✉  Email ........ ps.prateek1709@gmail.com                ║
║  🌐 Portfolio .... PATRIXX SHELL v2.0 (terminal UI)        ║
║                                                            ║
╠══════════════════════════════════════════════════════════════╣
║  [*] Preferred contact: LinkedIn or Email                  ║
║  [*] Response time: < 24 hours                             ║
║  [!] Do NOT attempt social engineering. I'll know.         ║
╚══════════════════════════════════════════════════════════════╝
```

---

### `🐍 PHASE 7 — CONTRIBUTION ACTIVITY`

<div align="center">

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Prateek-squadron&theme=react-dark&hide_border=true&bg_color=0d1117&color=00ff41&line=ff0040&point=00ff41&area=true&area_color=1a0a2e)

</div>

---

```
╔══════════════════════════════════════════════════════════════╗
║  SCAN COMPLETE                                             ║
║  Targets scanned: 1 | Vulnerabilities: 0 | Status: SECURE ║
║  Classification: PATRIXX — Cybersec & Forensics Operator   ║
║                                                            ║
║  "I don't just use the terminal. I live in it."            ║
║                                                            ║
║  Report generated by: PATRIXX RECON FRAMEWORK v2.0         ║
╚══════════════════════════════════════════════════════════════╝
```

<div align="center">
  
![Visitors](https://komarev.com/ghpvc/?username=Prateek-squadron&color=00ff41&style=flat-square&label=SCANS+ON+THIS+PROFILE)

</div>

<!-- EOF — patrixx@recon:~$ exit -->
