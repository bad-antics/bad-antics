<div align="center">

<img src="header.svg" alt="bad-antics — Security Research · Systems Engineering · Language Design" width="100%">

<br><br>

[![Portal](https://img.shields.io/badge/🌐_Portal-bad--antics.github.io-7c5cfc?style=for-the-badge&labelColor=0a0a0f)](https://bad-antics.github.io/)
[![Lateralus](https://img.shields.io/badge/|>_Lateralus-Try_Playground-22d3ee?style=for-the-badge&labelColor=0a0a0f)](https://bad-antics.github.io/lateralus/playground/)
[![VS Code](https://img.shields.io/badge/VS_Code-Marketplace-34d399?style=for-the-badge&labelColor=0a0a0f)](https://marketplace.visualstudio.com/items?itemName=lateralus.lateralus-lang)
[![PyPI](https://img.shields.io/badge/PyPI-lateralus--lang-fb923c?style=for-the-badge&labelColor=0a0a0f)](https://pypi.org/project/lateralus-lang/)

</div>

<img src="divider.svg" width="100%">

<div align="center">

**Security researcher** · **language designer** · **732 repos** · **140+ tools** · **1M+ reach**

*Merged PRs in* **h4cker** ⭐25.6k · **Awesome-Hacking** ⭐108.8k · **android-security-awesome** ⭐9.3k · **awesome-flipperzero** ⭐23k

</div>

<img src="divider.svg" width="100%">

## |> Lateralus Programming Language

<div align="center">

<a href="https://bad-antics.github.io/lateralus/playground/">
<img src="lateralus-banner.svg" alt="Lateralus — Pipeline-native programming language" width="100%">
</a>

</div>

A compiled programming language where **data flows left-to-right** with the pipeline operator `|>`. Pattern matching, async/await, structs with impl blocks, `try/recover/ensure` error handling — and zero dependencies.

```
let report = transactions
    |> filter(|t| t.amount > 20.0)
    |> group_by(|t| t.category)
    |> sort_by(|e| e.total, descending)
```

| | |
|:---|:---|
| 🌐 **Website** | [bad-antics.github.io/lateralus](https://bad-antics.github.io/lateralus/) |
| ▶ **Playground** | [Try in browser — no install](https://bad-antics.github.io/lateralus/playground/) |
| 📦 **Install** | `pip install lateralus-lang` |
| 🧩 **VS Code** | [Marketplace](https://marketplace.visualstudio.com/items?itemName=lateralus.lateralus-lang) |
| 📚 **Tutorials** | [25 step-by-step lessons](https://github.com/bad-antics/lateralus-tutorials) |
| 🖥️ **LateralusOS** | [Full OS kernel written in .ltl](https://github.com/bad-antics/lateralus-os) |
| 📊 **Ecosystem** | 22 repos · 2,400+ .ltl files · compiler, VM, web framework, ML tools |

<img src="divider.svg" width="100%">

## 🐧 NullSec Linux v5.0

Security-focused Linux distribution with **140+ pre-installed tools**, AI-powered threat analysis, and 5 specialized editions spanning AMD64, ARM64, RISC-V, and Apple Silicon.

<table>
<tr>
<td width="50%">

**Editions:**
- 🔒 **Professional** — Full pentest suite
- 🏭 **Industrial** — ICS/SCADA security
- 📱 **Mobile** — Android/iOS testing
- ☁️ **Cloud** — AWS/GCP/Azure audit
- 🤖 **AI** — ML security research

</td>
<td width="50%">

**Highlights:**
- 🪓 **LogReaper** ⭐72 — High-speed log forensics
- 🔍 **RKHunt** v2.5 — 250+ rootkit signatures
- ☁️ **CloudAudit** — 500+ compliance checks
- 🤖 **LLMRed** — AI/ML red teaming
- 🛡️ **RCE Shield** — PC gamer hardening

</td>
</tr>
</table>

[![NullSec Linux](https://img.shields.io/badge/Download-NullSec_Linux_v5.0-34d399?style=for-the-badge&logo=linux&logoColor=white&labelColor=0a0a0f)](https://github.com/bad-antics/nullsec-linux)

<img src="divider.svg" width="100%">

## 💻 Tech Stack

<table>
<tr>
<td valign="top" width="33%">

**⚡ Systems & Low-Level**

![Rust](https://img.shields.io/badge/Rust-000?style=flat-square&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Zig](https://img.shields.io/badge/Zig-F7A41D?style=flat-square&logo=zig&logoColor=black)
![Lateralus](https://img.shields.io/badge/Lateralus-7c5cfc?style=flat-square)

</td>
<td valign="top" width="33%">

**🔬 Scientific & HPC**

![Julia](https://img.shields.io/badge/Julia-9558B2?style=flat-square&logo=julia&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Haskell](https://img.shields.io/badge/Haskell-5D4F85?style=flat-square&logo=haskell&logoColor=white)
![OCaml](https://img.shields.io/badge/OCaml-EC6813?style=flat-square&logo=ocaml&logoColor=white)
![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=flat-square&logo=elixir&logoColor=white)

</td>
<td valign="top" width="33%">

**☁️ Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![K8s](https://img.shields.io/badge/K8s-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)

</td>
</tr>
<tr>
<td valign="top" width="33%">

**📜 Scripting & Automation**

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![Nim](https://img.shields.io/badge/Nim-FFE953?style=flat-square&logo=nim&logoColor=black)

</td>
<td valign="top" width="33%">

**🐧 Linux & Embedded**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Buildroot](https://img.shields.io/badge/Buildroot-000?style=flat-square&logo=linux&logoColor=white)
![RPi](https://img.shields.io/badge/RPi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)

</td>
<td valign="top" width="33%">

**🔒 Security Tools**

![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Burp](https://img.shields.io/badge/Burp-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Ghidra](https://img.shields.io/badge/Ghidra-F00?style=flat-square)
![Frida](https://img.shields.io/badge/Frida-DC5C23?style=flat-square&logo=frida&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square)

</td>
</tr>
</table>

<img src="divider.svg" width="100%">

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🌐 Marshall Browser v3.0
Privacy-focused security browser with **Dr. Marshall AI assistant** and built-in exploit tools.

[![Marshall](https://img.shields.io/badge/View-Marshall_Browser-22d3ee?style=for-the-badge&labelColor=0a0a0f)](https://github.com/bad-antics/marshall)

</td>
<td width="50%" valign="top">

### 📱 NullKia v3.0
Mobile security framework — **18 manufacturers**, baseband exploitation, 5G/LTE testing, TEE/TrustZone research.

[![NullKia](https://img.shields.io/badge/View-NullKia-a78bfa?style=for-the-badge&labelColor=0a0a0f)](https://github.com/bad-antics/nullkia)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚗 BlackFlag
Automotive & ECU security — CAN bus, OBD-II, UDS protocols, key fob analysis, ECU fuzzing.

[![BlackFlag](https://img.shields.io/badge/View-BlackFlag-fb923c?style=for-the-badge&labelColor=0a0a0f)](https://github.com/bad-antics/blackflag)

</td>
<td width="50%" valign="top">

### 🛡️ RCE Shield
RCE hardening for PC gamers — game launcher scanning, anti-cheat auditing, mod & overlay vulnerability checks.

[![RCE Shield](https://img.shields.io/badge/View-RCE_Shield-22d3ee?style=for-the-badge&labelColor=0a0a0f)](https://github.com/bad-antics/rce-shield)

</td>
</tr>
</table>

<img src="divider.svg" width="100%">

## 🔮 Julia Security Suite

*High-performance security research in Julia · 40,000+ lines*

| Tool | Description | Lines |
|:-----|:------------|------:|
| [**🔬 Spectra**](https://github.com/bad-antics/spectra) | Cryptography, network analysis, forensics toolkit | 8,000+ |
| [**🔮 Oracle**](https://github.com/bad-antics/oracle) | AI vulnerability discovery — 87% prediction accuracy | 11,389 |
| [**👻 Phantom**](https://github.com/bad-antics/phantom) | Zero-knowledge proofs for anonymous disclosure | 6,302 |
| [**🌀 Vortex**](https://github.com/bad-antics/vortex) | Threat intelligence fusion — 50+ feeds, ML correlation | 8,406 |
| [**🪞 Mirage**](https://github.com/bad-antics/mirage) | Adversarial ML — attacks, defenses, robustness | 7,000+ |

<img src="divider.svg" width="100%">

## 🖥️ N01D Desktop Suite

| App | Description |
|:----|:------------|
| [**n01d-forge**](https://github.com/bad-antics/n01d-forge) ⭐9 | Secure image burner — LUKS, VeraCrypt, secure erase |
| [**n01d-machine**](https://github.com/bad-antics/n01d-machine) ⭐8 | VM manager — sandboxing, Tor, VPN isolation |
| [**n01d-media**](https://github.com/bad-antics/n01d-media) | Unified media player, editor & encoder |
| [**n01d-overwatch**](https://github.com/bad-antics/n01d-overwatch) | Real-time global conflict OSINT dashboard |
| [**n01d-docker**](https://github.com/bad-antics/n01d-docker) | Custom security & dev containers |
| [**n01d-timemachine**](https://github.com/bad-antics/n01d-timemachine) | Classic computing emulator — C64, Amiga, ZX, DOS |

<img src="divider.svg" width="100%">

## 🍍🐬 Device Suites

<table>
<tr>
<td width="50%" valign="top">

### 🍍 Pineapple Suite ⭐31
**96+ WiFi Pineapple Pager payloads** across 13 categories.

[![Pineapple](https://img.shields.io/badge/View-Pineapple_Suite-34d399?style=for-the-badge&labelColor=0a0a0f)](https://github.com/bad-antics/nullsec-pineapple-suite)

</td>
<td width="50%" valign="top">

### 🐬 Flipper Suite ⭐24
**430+ Flipper Zero files** — BadUSB, SubGHz, NFC, RFID, IR, animations.

[![Flipper](https://img.shields.io/badge/View-Flipper_Suite-34d399?style=for-the-badge&labelColor=0a0a0f)](https://github.com/bad-antics/nullsec-flipper-suite)

</td>
</tr>
<tr>
<td colspan="2">

### 🔥 Unleash Hell Collection
Hellfire-themed packs — 10 animations (88 frames) for Flipper Zero, 113 themed UI components for WiFi Pineapple Pager.

[![Flipper](https://img.shields.io/badge/Flipper-Unleash_Hell-f87171?style=flat-square&labelColor=0a0a0f)](https://github.com/bad-antics/nullsec-unleash-hell)
[![Pager](https://img.shields.io/badge/Pager-Unleash_Hell-f87171?style=flat-square&labelColor=0a0a0f)](https://github.com/bad-antics/nullsec-unleash-hell-pager)

</td>
</tr>
</table>

<img src="divider.svg" width="100%">

## ✅ Community Contributions

<div align="center">

**60 merged PRs** · **195 total submitted** · **1M+ combined stars**

*Accepted contributions across 17 major open-source security projects*

</div>

<table>
<tr>
<td valign="top" width="50%">

| Repository | ⭐ | Status |
|:-----------|---:|:------:|
| [**Awesome-Hacking**](https://github.com/Hack-with-Github/Awesome-Hacking) | 108.8k | ✅ |
| [**h4cker**](https://github.com/The-Art-of-Hacking/h4cker) | 25.6k | ×5 ✅ |
| [**awesome-pentest**](https://github.com/enaqx/awesome-pentest) | 25.6k | ✅ |
| [**awesome-osint**](https://github.com/jivoi/awesome-osint) | 25.4k | ✅ |
| [**awesome-flipperzero**](https://github.com/djsime1/awesome-flipperzero) | 23k | ✅ |
| [**awesome-privacy**](https://github.com/pluja/awesome-privacy) | 18.3k | ✅ |

</td>
<td valign="top" width="50%">

| Repository | ⭐ | Status |
|:-----------|---:|:------:|
| [**awesome-security**](https://github.com/sbilly/awesome-security) | 14.1k | ✅ |
| [**android-security-awesome**](https://github.com/ashishb/android-security-awesome) | 9.3k | ✅ |
| [**awesome-web-hacking**](https://github.com/infoslack/awesome-web-hacking) | 6.8k | ✅ |
| [**awesome-iot**](https://github.com/HQarroum/awesome-iot) | 3.9k | ✅ |
| [**bashbunny-payloads**](https://github.com/hak5/bashbunny-payloads) | 2.9k | ✅ |
| [**awesome-linux-rootkits**](https://github.com/milabs/awesome-linux-rootkits) | 2k | ✅ |

</td>
</tr>
</table>

<img src="divider.svg" width="100%">

## 📊 GitHub Stats

<div align="center">

<a href="https://github.com/bad-antics">
<img height="165" src="https://github-readme-stats-sigma-five.vercel.app/api?username=bad-antics&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&bg_color=0a0a0f&title_color=7c5cfc&icon_color=22d3ee&text_color=e8e8f0&ring_color=7c5cfc" />
</a>
<a href="https://github.com/bad-antics">
<img height="165" src="https://github-readme-streak-stats-eight.vercel.app/?user=bad-antics&theme=github-dark-blue&hide_border=true&background=0a0a0f&ring=7c5cfc&fire=22d3ee&currStreakLabel=22d3ee" />
</a>

</div>

<img src="divider.svg" width="100%">

<div align="center">

[![Portal](https://img.shields.io/badge/🌐_Portal-bad--antics.github.io-7c5cfc?style=for-the-badge&labelColor=0a0a0f)](https://bad-antics.github.io/)
&nbsp;
[![Lateralus](https://img.shields.io/badge/|>_Lateralus-Playground-22d3ee?style=for-the-badge&labelColor=0a0a0f)](https://bad-antics.github.io/lateralus/playground/)

*For authorized security testing and educational purposes only.*

**© 2024-2026 bad-antics · Security Engineering · Systems Research · Language Design**

</div>
