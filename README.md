<div align="center">

<!-- Animated Night Hacker Girl Banner (SVG) -->
<svg width="860" height="280" viewBox="0 0 860 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="bg-glow" cx="50%" cy="100%" r="80%">
      <stop offset="0%" stop-color="#0a1628"/>
      <stop offset="100%" stop-color="#020810"/>
    </radialGradient>
    <radialGradient id="screen-glow" cx="50%" cy="50%" r="60%">
      <stop offset="0%" stop-color="#00d4ff" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#00d4ff" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="lamp-glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ffe97a" stop-opacity="0.7"/>
      <stop offset="100%" stop-color="#ffb347" stop-opacity="0"/>
    </radialGradient>
    <filter id="glow-blue">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <clipPath id="screen-clip"><rect x="320" y="102" width="170" height="105" rx="4"/></clipPath>
    <style>
      @keyframes blink { 0%,90%,100%{opacity:1} 92%,98%{opacity:0} }
      @keyframes pulse-screen { 0%,100%{opacity:0.9} 50%{opacity:1} }
      @keyframes lamp-flicker { 0%,100%{opacity:0.85} 47%{opacity:0.75} 50%{opacity:1} }
      @keyframes float-lock { 0%,100%{transform:translateY(0)} 50%{transform:translateY(-4px)} }
      @keyframes float-shield { 0%,100%{transform:translateY(0)} 50%{transform:translateY(-5px)} }
      @keyframes scan-line { 0%{transform:translateY(0)} 100%{transform:translateY(105px)} }
      @keyframes arm-type { 0%,100%{transform:rotate(-2deg)} 50%{transform:rotate(2deg)} }
      .scan { animation: scan-line 2.5s linear infinite; }
      .screen-pulse { animation: pulse-screen 3s ease-in-out infinite; }
    </style>
  </defs>
  <rect width="860" height="280" fill="url(#bg-glow)" rx="16"/>
  <g fill="#ffffff">
    <circle cx="40" cy="20" r="1" opacity="0.6"/><circle cx="80" cy="10" r="0.8" opacity="0.4"/>
    <circle cx="130" cy="30" r="1.2" opacity="0.7"/><circle cx="190" cy="15" r="0.7" opacity="0.5"/>
    <circle cx="750" cy="18" r="1" opacity="0.6"/><circle cx="800" cy="8" r="0.8" opacity="0.4"/>
    <circle cx="820" cy="35" r="1.2" opacity="0.7"/><circle cx="840" cy="22" r="0.7" opacity="0.5"/>
    <circle cx="60" cy="50" r="0.6" opacity="0.3"/><circle cx="700" cy="40" r="0.9" opacity="0.5"/>
    <circle cx="600" cy="12" r="1" opacity="0.45"/><circle cx="500" cy="25" r="0.7" opacity="0.35"/>
  </g>
  <circle cx="790" cy="45" r="22" fill="#1a2540" opacity="0.9"/>
  <circle cx="798" cy="38" r="18" fill="#e8eaf6" opacity="0.92"/>
  <circle cx="808" cy="32" r="12" fill="#1a2540" opacity="0.88"/>
  <ellipse cx="405" cy="160" rx="130" ry="80" fill="url(#screen-glow)"/>
  <rect x="140" y="210" width="580" height="18" rx="4" fill="#0d1f3c"/>
  <rect x="155" y="224" width="550" height="8" rx="2" fill="#0a1628"/>
  <rect x="390" y="205" width="20" height="12" rx="2" fill="#1a2f4a"/>
  <rect x="370" y="215" width="60" height="5" rx="2" fill="#1a2f4a"/>
  <rect x="310" y="92" width="190" height="122" rx="8" fill="#0d1826" stroke="#1e3a5f" stroke-width="2"/>
  <rect x="318" y="99" width="174" height="109" rx="4" fill="#030d1a" class="screen-pulse"/>
  <rect x="318" y="99" width="174" height="109" rx="4" fill="#00d4ff" opacity="0.04"/>
  <g clip-path="url(#screen-clip)">
    <rect x="320" y="102" width="170" height="3" fill="#00d4ff" opacity="0.15" class="scan"/>
  </g>
  <g clip-path="url(#screen-clip)" font-family="monospace" font-size="8" fill="#00d4ff">
    <text x="326" y="117" opacity="0.9">$ nmap -sV 192.168.1.0/24</text>
    <text x="326" y="129" opacity="0.75">Host: 192.168.1.1 [open]</text>
    <text x="326" y="141" fill="#00ff9d" opacity="0.65">22/tcp  open  ssh</text>
    <text x="326" y="153" fill="#00ff9d" opacity="0.55">80/tcp  open  http</text>
    <text x="326" y="165" fill="#ff4d6d" opacity="0.8">443/tcp VULN detected</text>
    <text x="326" y="177" fill="#ffe066" opacity="0.7">Analyzing threats...</text>
    <text x="326" y="189" opacity="0.9">█</text>
  </g>
  <rect x="500" y="128" width="120" height="86" rx="6" fill="#0d1826" stroke="#1e3a5f" stroke-width="1.5"/>
  <rect x="506" y="134" width="108" height="74" rx="3" fill="#030d1a"/>
  <g font-family="monospace" font-size="7" fill="#ff4d6d">
    <text x="512" y="148" opacity="0.9">ALERT: Port scan</text>
    <text x="512" y="159" fill="#ffe066" opacity="0.8">ISO 27001 check</text>
    <text x="512" y="170" fill="#00ff9d" opacity="0.9">Firewall: ACTIVE</text>
    <text x="512" y="181" fill="#00d4ff" opacity="0.7">GRC status: OK</text>
    <text x="512" y="192" fill="#aaaaaa" opacity="0.6">Audit log: 847 ok</text>
  </g>
  <rect x="550" y="210" width="12" height="8" rx="1" fill="#1a2f4a"/>
  <rect x="536" y="216" width="40" height="4" rx="1" fill="#1a2f4a"/>
  <rect x="200" y="180" width="5" height="38" rx="2" fill="#1a2f4a"/>
  <path d="M202 180 Q192 165 185 150" stroke="#1a2f4a" stroke-width="4" fill="none" stroke-linecap="round"/>
  <ellipse cx="183" cy="146" rx="18" ry="10" fill="#1a2f4a"/>
  <ellipse cx="183" cy="150" rx="18" ry="10" fill="#0d1826" opacity="0.8"/>
  <ellipse cx="183" cy="170" rx="55" ry="38" fill="url(#lamp-glow)" opacity="0.6" style="animation:lamp-flicker 4s ease-in-out infinite"/>
  <rect x="238" y="195" width="62" height="6" rx="3" fill="#1a2f4a"/>
  <rect x="252" y="200" width="8" height="18" rx="2" fill="#1a2f4a"/>
  <rect x="278" y="200" width="8" height="18" rx="2" fill="#1a2f4a"/>
  <rect x="230" y="200" width="10" height="18" rx="2" fill="#122040"/>
  <rect x="298" y="200" width="10" height="18" rx="2" fill="#122040"/>
  <rect x="248" y="152" width="44" height="50" rx="10" fill="#1a2f4a"/>
  <path d="M260 152 Q270 162 280 152" stroke="#0d1826" stroke-width="1.5" fill="none"/>
  <text x="263" y="180" font-family="monospace" font-size="6" fill="#00d4ff" opacity="0.7">SEC</text>
  <g style="transform-origin:260px 175px; animation:arm-type 0.6s ease-in-out infinite">
    <rect x="240" y="168" width="24" height="10" rx="5" fill="#2a4060"/>
    <rect x="240" y="175" width="4" height="7" rx="2" fill="#2a4060"/>
    <rect x="246" y="175" width="4" height="8" rx="2" fill="#2a4060"/>
    <rect x="252" y="175" width="4" height="7" rx="2" fill="#2a4060"/>
    <rect x="258" y="175" width="4" height="6" rx="2" fill="#2a4060"/>
  </g>
  <g style="transform-origin:282px 175px; animation:arm-type 0.6s ease-in-out infinite reverse">
    <rect x="276" y="168" width="24" height="10" rx="5" fill="#2a4060"/>
    <rect x="276" y="175" width="4" height="6" rx="2" fill="#2a4060"/>
    <rect x="282" y="175" width="4" height="7" rx="2" fill="#2a4060"/>
    <rect x="288" y="175" width="4" height="8" rx="2" fill="#2a4060"/>
    <rect x="294" y="175" width="4" height="7" rx="2" fill="#2a4060"/>
  </g>
  <rect x="232" y="208" width="76" height="8" rx="3" fill="#0d1826" stroke="#1e3a5f" stroke-width="1"/>
  <g fill="#1e3a5f">
    <rect x="234" y="210" width="6" height="4" rx="1"/><rect x="242" y="210" width="6" height="4" rx="1"/>
    <rect x="250" y="210" width="6" height="4" rx="1"/><rect x="258" y="210" width="6" height="4" rx="1"/>
    <rect x="266" y="210" width="6" height="4" rx="1"/><rect x="274" y="210" width="6" height="4" rx="1"/>
    <rect x="282" y="210" width="6" height="4" rx="1"/><rect x="290" y="210" width="6" height="4" rx="1"/>
    <rect x="298" y="210" width="6" height="4" rx="1"/>
  </g>
  <!-- Girl head -->
  <ellipse cx="270" cy="137" rx="19" ry="21" fill="#c8a882"/>
  <!-- Long hair back layer -->
  <ellipse cx="270" cy="122" rx="23" ry="16" fill="#1a0a00"/>
  <path d="M248 130 Q242 160 246 195" stroke="#1a0a00" stroke-width="10" fill="none" stroke-linecap="round"/>
  <path d="M292 130 Q298 160 294 195" stroke="#1a0a00" stroke-width="10" fill="none" stroke-linecap="round"/>
  <!-- Hair front top -->
  <path d="M250 122 Q252 108 270 106 Q288 108 290 122" fill="#1a0a00"/>
  <!-- Side bangs -->
  <path d="M250 122 Q247 130 249 136" stroke="#1a0a00" stroke-width="4" fill="none" stroke-linecap="round"/>
  <!-- Hair tie / bun detail -->
  <circle cx="270" cy="106" r="5" fill="#ff4d6d" opacity="0.8"/>
  <circle cx="270" cy="106" r="3" fill="#cc2244" opacity="0.9"/>
  <!-- Ear -->
  <ellipse cx="251" cy="138" rx="3" ry="4" fill="#b8987a"/>
  <ellipse cx="289" cy="138" rx="3" ry="4" fill="#b8987a"/>
  <!-- Glasses -->
  <rect x="256" y="135" width="10" height="7" rx="3" fill="none" stroke="#00d4ff" stroke-width="1.5" opacity="0.9" filter="url(#glow-blue)"/>
  <rect x="272" y="135" width="10" height="7" rx="3" fill="none" stroke="#00d4ff" stroke-width="1.5" opacity="0.9" filter="url(#glow-blue)"/>
  <line x1="266" y1="138" x2="272" y2="138" stroke="#00d4ff" stroke-width="1" opacity="0.7"/>
  <line x1="256" y1="138" x2="251" y2="137" stroke="#00d4ff" stroke-width="1" opacity="0.5"/>
  <line x1="282" y1="138" x2="289" y2="137" stroke="#00d4ff" stroke-width="1" opacity="0.5"/>
  <!-- Eyes -->
  <circle cx="261" cy="138" r="2.5" fill="#1a0a00"/>
  <circle cx="277" cy="138" r="2.5" fill="#1a0a00"/>
  <circle cx="262" cy="137" r="0.8" fill="#ffffff" opacity="0.7"/>
  <circle cx="278" cy="137" r="0.8" fill="#ffffff" opacity="0.7"/>
  <!-- Eyelashes (feminine detail) -->
  <line x1="258" y1="134" x2="257" y2="132" stroke="#1a0a00" stroke-width="0.8"/>
  <line x1="261" y1="133" x2="261" y2="131" stroke="#1a0a00" stroke-width="0.8"/>
  <line x1="264" y1="134" x2="265" y2="132" stroke="#1a0a00" stroke-width="0.8"/>
  <line x1="274" y1="134" x2="273" y2="132" stroke="#1a0a00" stroke-width="0.8"/>
  <line x1="277" y1="133" x2="277" y2="131" stroke="#1a0a00" stroke-width="0.8"/>
  <line x1="280" y1="134" x2="281" y2="132" stroke="#1a0a00" stroke-width="0.8"/>
  <!-- Small smile -->
  <path d="M265 147 Q270 151 275 147" stroke="#a07050" stroke-width="1.2" fill="none" stroke-linecap="round"/>
  <!-- Cursor blink -->
  <rect x="279" y="135" width="2" height="7" fill="#00d4ff" opacity="0.8" style="animation:blink 1.2s step-end infinite"/>
  <g style="animation:float-shield 3s ease-in-out infinite; transform-origin:640px 130px">
    <path d="M640 112 L655 118 L655 135 Q655 145 640 150 Q625 145 625 135 L625 118 Z" fill="#0d2040" stroke="#00d4ff" stroke-width="1.5" filter="url(#glow-blue)" opacity="0.85"/>
    <text x="640" y="135" text-anchor="middle" font-size="12" fill="#00d4ff" opacity="0.9">ok</text>
  </g>
  <g style="animation:float-lock 2.5s ease-in-out infinite 0.5s; transform-origin:680px 85px">
    <rect x="668" y="88" width="24" height="18" rx="4" fill="#0d2040" stroke="#ffe066" stroke-width="1.5" opacity="0.85"/>
    <path d="M672 88 Q672 80 680 80 Q688 80 688 88" fill="none" stroke="#ffe066" stroke-width="1.5" opacity="0.85"/>
    <circle cx="680" cy="97" r="3" fill="#ffe066" opacity="0.8"/>
  </g>
  <rect x="636" y="200" width="22" height="18" rx="3" fill="#1a2f4a"/>
  <rect x="634" y="198" width="26" height="4" rx="1" fill="#0d1826"/>
  <path d="M658 206 Q666 206 666 210 Q666 214 658 214" fill="none" stroke="#1a2f4a" stroke-width="2"/>
  <path d="M641 196 Q643 190 641 184" stroke="#334d6e" stroke-width="1.5" fill="none" stroke-linecap="round" opacity="0.5"/>
  <path d="M648 196 Q650 188 648 182" stroke="#334d6e" stroke-width="1.5" fill="none" stroke-linecap="round" opacity="0.4"/>
  <rect x="148" y="204" width="40" height="30" rx="2" fill="#0d2040" stroke="#1e3a5f" stroke-width="1"/>
  <line x1="152" y1="212" x2="184" y2="212" stroke="#1e3a5f" stroke-width="0.8" opacity="0.6"/>
  <line x1="152" y1="218" x2="184" y2="218" stroke="#1e3a5f" stroke-width="0.8" opacity="0.6"/>
  <line x1="152" y1="224" x2="178" y2="224" stroke="#1e3a5f" stroke-width="0.8" opacity="0.6"/>
  <text x="430" y="55" text-anchor="middle" font-family="'Courier New', monospace" font-size="26" font-weight="700" fill="#00d4ff" filter="url(#glow-blue)" opacity="0.95">JAYASRI DURAIPANDI</text>
  <text x="430" y="78" text-anchor="middle" font-family="'Courier New', monospace" font-size="12" fill="#7ec8e3" opacity="0.8">> Cybersecurity | ISO Lead Auditor | Ethical Hacker in Progress</text>
  <rect x="0" y="265" width="860" height="15" fill="#00d4ff" opacity="0.04"/>
</svg>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=00D4FF&background=00000000&center=true&vCenter=true&width=700&lines=%24+whoami+--+Jayasri+Duraipandi;ISO+27001+%26+42001+Lead+Auditor+%F0%9F%94%90;Cybersecurity+Intern+%7C+Dubai+%26+Abu+Dhabi;Building+secure+systems%2C+one+port+at+a+time;CCNA+%7C+CCNP+%7C+CISO+%E2%80%94+In+Progress...)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jayasri-duraipandi/)
[![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=00d4ff)](https://github.com/jayasriduraipandi)
[![Email](https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=ff4d6d)](mailto:jayasriduraipandi1415@gmail.com)

</div>

---

```bash
$ cat about_me.txt
```
```
> M.Sc. Software Systems @ SKASC, Coimbatore  |  CGPA: 8.3
> Cybersecurity Intern — Altayaboon IT Solutions, Dubai
> Freelance ISO Trainer — QRS, Abu Dhabi (20+ Gulf companies trained)
> ISO 27001 & 42001 Lead Auditor  |  GRC & Risk Assessment
> Preparing: CCNA → CCNP → CISO
> Status: Scanning for vulnerabilities. Threats: 0. Coffee: infinite ☕
```

---

## `> experience --list`

<table>
<tr>
<td width="50%" valign="top">

**🔐 Cybersecurity & Networking Intern**
`Altayaboon IT Solutions` · Dubai, UAE

```diff
+ ISO 27001 frameworks & IMS activities
+ Clients: CPX Holding, Sukoon Insurance
+ Enterprise network security & compliance
```
🌐 [altayaboon.com](https://altayaboon.com)

</td>
<td width="50%" valign="top">

**📋 Freelance ISO Technical Trainer**
`Quality Registration Services` · Abu Dhabi

```diff
+ Trained 20+ Gulf companies on ISO standards
+ Standards: 9001 · 14001 · 45001 · 27001 · 42001
+ 10+ security awareness programs delivered
```
🌐 [qrsyst.com](https://qrsyst.com)

</td>
</tr>
</table>

---

## `> ls projects/`

<table>
<tr>
<td width="50%" valign="top">

#### 🛡️ IoT Security Scanner
```
Scans & identifies vulnerabilities in IoT devices
├── Device discovery & port scanning
├── Threat analysis & report generation
└── Real-time monitoring dashboard
```
![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=00d4ff)
![Flask](https://img.shields.io/badge/Flask-0d1117?style=flat-square&logo=flask&logoColor=00d4ff)
![SocketIO](https://img.shields.io/badge/Socket.IO-0d1117?style=flat-square&logo=socket.io&logoColor=00d4ff)

</td>
<td width="50%" valign="top">

#### 🔗 CertChain — Blockchain Verification
```
Blockchain-based academic certificate system
├── QR verification & audit trail
├── Multi-signature revocation
└── Roles: University · Student · Employer
```
![React](https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=00d4ff)
![Node](https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=node.js&logoColor=00d4ff)
![Blockchain](https://img.shields.io/badge/Blockchain-0d1117?style=flat-square&logo=ethereum&logoColor=00d4ff)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🤖 AI Discord Productivity Bot
```
Bridges employee-manager communication
├── Task reminders & notifications
└── Automated intelligent responses
```
![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=00d4ff)
![Discord](https://img.shields.io/badge/Discord_API-0d1117?style=flat-square&logo=discord&logoColor=00d4ff)

</td>
<td width="50%" valign="top">

#### 🗂️ File Integrity Monitor
```
Detects unauthorized file modifications
├── SHA-256 cryptographic hashing
└── Real-time integrity alerts
```
![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=00d4ff)
![SHA256](https://img.shields.io/badge/SHA--256-0d1117?style=flat-square&logo=gnuprivacyguard&logoColor=00d4ff)

</td>
</tr>
</table>

---

## `> cat tech_stack.conf`

**Languages**

![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=00d4ff)
![Java](https://img.shields.io/badge/Java-0d1117?style=for-the-badge&logo=openjdk&logoColor=ff4d6d)
![JavaScript](https://img.shields.io/badge/JavaScript-0d1117?style=for-the-badge&logo=javascript&logoColor=ffe066)
![HTML5](https://img.shields.io/badge/HTML5-0d1117?style=for-the-badge&logo=html5&logoColor=ff4d6d)
![CSS3](https://img.shields.io/badge/CSS3-0d1117?style=for-the-badge&logo=css3&logoColor=00d4ff)

**Frameworks & Libraries**

![Flask](https://img.shields.io/badge/Flask-0d1117?style=for-the-badge&logo=flask&logoColor=00d4ff)
![React](https://img.shields.io/badge/React-0d1117?style=for-the-badge&logo=react&logoColor=00d4ff)
![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=for-the-badge&logo=node.js&logoColor=00ff9d)
![Socket.io](https://img.shields.io/badge/Socket.io-0d1117?style=for-the-badge&logo=socket.io&logoColor=ffffff)

**Cybersecurity & Networking**

![Wireshark](https://img.shields.io/badge/Wireshark-0d1117?style=for-the-badge&logo=wireshark&logoColor=00d4ff)
![Cisco](https://img.shields.io/badge/Cisco_Packet_Tracer-0d1117?style=for-the-badge&logo=cisco&logoColor=00d4ff)
![Fortinet](https://img.shields.io/badge/FortiGate-0d1117?style=for-the-badge&logo=fortinet&logoColor=ff4d6d)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-0d1117?style=for-the-badge&logo=kalilinux&logoColor=00d4ff)
![Nmap](https://img.shields.io/badge/Nmap-0d1117?style=for-the-badge&logo=nmap&logoColor=00ff9d)

**Governance, Risk & Compliance**

![ISO 27001](https://img.shields.io/badge/ISO_27001-0d1117?style=for-the-badge&logo=shield&logoColor=ffe066)
![ISO 42001](https://img.shields.io/badge/ISO_42001-0d1117?style=for-the-badge&logo=shield&logoColor=ffe066)
![GRC](https://img.shields.io/badge/GRC-0d1117?style=for-the-badge&logo=checkmk&logoColor=00ff9d)
![Archer](https://img.shields.io/badge/Archer_GRC-0d1117?style=for-the-badge&logo=target&logoColor=ff4d6d)

**Tools & Platforms**

![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=ffffff)
![VS Code](https://img.shields.io/badge/VS_Code-0d1117?style=for-the-badge&logo=visualstudiocode&logoColor=00d4ff)
![Figma](https://img.shields.io/badge/Figma-0d1117?style=for-the-badge&logo=figma&logoColor=ff4d6d)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=for-the-badge&logo=linux&logoColor=ffe066)
![Git](https://img.shields.io/badge/Git-0d1117?style=for-the-badge&logo=git&logoColor=ff4d6d)

---

## `> achievements --verified`

| status | achievement |
|--------|-------------|
| ✅ | **ISO/IEC 27001:2022 Lead Auditor** — Mastermind Assurance · Aug 2025 |
| ✅ | **ISO/IEC 42001:2023 Lead Auditor** — Mastermind Assurance · Dec 2025 |
| 📄 | Published: *IoT Scanner for Securing Connected Assets* — IJSART Vol.11 · Nov 2025 |
| 🎤 | Presented: *AI in Cybersecurity* — NCSET 2026 · Jan 2026 |
| 🥉 | **3rd Prize** — Binary Expo Solvathon Competition · Feb 2026 |
| 🔓 | Participant — **Pentathon 2025** National Penetration Testing Hackathon |
| 📚 | Preparing: **CCNA · CCNP · CISO** — Academy of Network Kings · Ongoing |

---

## `> github --stats`

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=jayasriduraipandi&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00d4ff&icon_color=00d4ff&text_color=7ec8e3&ring_color=00d4ff" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jayasriduraipandi&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00d4ff&text_color=7ec8e3" />

<br/>

![GitHub Streak](https://streak-stats.demolab.com?user=jayasriduraipandi&theme=github-dark-blue&hide_border=true&background=0d1117&ring=00d4ff&fire=ff4d6d&currStreakLabel=00d4ff)

</div>

---

<div align="center">

```
╔══════════════════════════════════════════════════════╗
║   "Security is not a product, but a process."        ║
║                              — Bruce Schneier        ║
╚══════════════════════════════════════════════════════╝
```

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=jayasriduraipandi.jayasriduraipandi&color=00d4ff)

</div>
