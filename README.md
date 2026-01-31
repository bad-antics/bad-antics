<div align="center">

# 👾 bad-antics

**Security Researcher | Systems Engineer | Open Source Developer**

[![GitHub](https://img.shields.io/badge/GitHub-bad--antics-181717?style=for-the-badge&logo=github)](https://github.com/bad-antics)
[![Repositories](https://img.shields.io/badge/Repositories-520+-blue?style=for-the-badge)](https://github.com/bad-antics?tab=repositories)
[![Tools](https://img.shields.io/badge/Security_Tools-140+-red?style=for-the-badge)](https://github.com/bad-antics/nullsec-linux)

</div>

---

## 🎯 About

Independent security researcher building the **bad-antics ./Dev** — a comprehensive ecosystem of 140+ specialized security tools, revolutionary Julia security frameworks, and a complete Linux distribution. My focus spans cloud security, AI/ML security research, hardware hacking, automotive systems, mobile security, and traditional penetration testing.

**Core Projects:**
- 🐧 **NullSec Linux v4.2.0** — Security distribution with 140+ tools, 5 specialized editions, 4 architectures
- 🔮 **Julia Security Suite** — Revolutionary high-performance security frameworks (Spectra, Oracle, Phantom, Vortex, Mirage)
- 📱 **NullKia v3.0** — Mobile security framework for 18 manufacturers with baseband, cellular, and TEE tools
- ☁️ **Cloud Security Suite** — AWS, GCP, Azure, Kubernetes, Terraform auditing
- 🤖 **AI/ML Security Suite** — LLM red teaming, prompt injection, model auditing
- 🔌 **Hardware Security Suite** — SDR, RFID, CAN bus, JTAG, glitch attacks

---

## ⚡ Julia Security Suite

Revolutionary high-performance security frameworks written in Julia, designed for speed, elegance, and real-world impact.

| Tool | Description | Lines |
|------|-------------|-------|
| [🌈 **Spectra**](https://github.com/bad-antics/spectra) | High-performance security toolkit with 25+ analyzers, NullSec integration | 8,000+ |
| [🔮 **Oracle**](https://github.com/bad-antics/oracle) | AI-Powered Vulnerability Discovery Engine with ML prediction | 11,000+ |
| [👻 **Phantom**](https://github.com/bad-antics/phantom) | Zero-Knowledge Proof Security Framework - prove vulns without revealing | 6,300+ |
| [🌀 **Vortex**](https://github.com/bad-antics/vortex) | Real-time Threat Intelligence Fusion - correlate 50+ feeds with ML | 8,400+ |
| [🎭 **Mirage**](https://github.com/bad-antics/mirage) | Adversarial ML Toolkit - evasion, poisoning, model extraction | 7,000+ |

**Total: 40,000+ lines of production Julia security code**

```julia
using Spectra, Oracle, Phantom, Vortex, Mirage

# Scan with AI-powered vulnerability detection
vulns = Oracle.scan("target_code/", model=:neural)

# Generate ZK proof of vulnerability without revealing details
proof = Phantom.prove_vulnerability(vulns[1])

# Check threat intel for related IOCs
intel = Vortex.correlate(vulns[1].indicators)

# Test adversarial robustness
robust = Mirage.evaluate_model("security_model.onnx")
```

📚 **[Julia Security Suite Documentation](https://github.com/bad-antics/julia-security-docs)**

---

## 🏆 Featured Projects

### 🐧 NullSec Linux v4.2.0

| Edition | Description | Tools |
|---------|-------------|-------|
| [**Standard**](https://github.com/bad-antics/nullsec-linux) | Full security distribution with complete toolkit | 140+ |
| [**Cloud Pentest**](https://github.com/bad-antics/nullsec-linux) | AWS, GCP, Azure, K8s, Terraform security | 6 |
| [**AI/ML Security**](https://github.com/bad-antics/nullsec-linux) | LLM red team, prompt inject, model audit | 5 |
| [**Hardware Hacking**](https://github.com/bad-antics/nullsec-linux) | SDR, RFID, CAN, JTAG, glitch attacks | 5 |
| [**Automotive Security**](https://github.com/bad-antics/nullsec-linux) | Vehicle systems, CAN, OBD-II, UDS | 4 |

**Architectures:** AMD64, ARM64, RISC-V, Apple Silicon (Asahi)

### 📱 NullKia v3.0 Mobile Security

| Feature | Description |
|---------|-------------|
| [**18 Manufacturers**](https://github.com/bad-antics/nullkia) | Samsung, Apple, Google, OnePlus, Xiaomi, Huawei, Motorola, LG, Sony, Nokia, Nothing, OPPO, Vivo, Realme, ASUS, ZTE, Fairphone, TCL |
| [**Baseband Tools**](https://github.com/bad-antics/nullkia) | Shannon, Qualcomm, MediaTek, Exynos, Apple modem exploitation |
| [**Cellular Security**](https://github.com/bad-antics/nullkia) | 5G/LTE security, eSIM tools, IMSI analysis, carrier unlock |
| [**TEE/TrustZone**](https://github.com/bad-antics/nullkia) | Secure Element, BootROM extraction, TrustZone research |

### ☁️ Cloud Security Tools

| Tool | Description |
|------|-------------|
| [nullsec-cloudaudit](https://github.com/bad-antics/nullsec-cloudaudit) | Multi-cloud security configuration auditing |
| [nullsec-k8sscan](https://github.com/bad-antics/nullsec-k8sscan) | Kubernetes cluster security scanner |
| [nullsec-awsrecon](https://github.com/bad-antics/nullsec-awsrecon) | AWS reconnaissance and enumeration |
| [nullsec-gcphunt](https://github.com/bad-antics/nullsec-gcphunt) | Google Cloud Platform security hunting |
| [nullsec-azuresweep](https://github.com/bad-antics/nullsec-azuresweep) | Azure infrastructure security sweeping |
| [nullsec-terraform-scan](https://github.com/bad-antics/nullsec-terraform-scan) | Terraform IaC security scanning |

### 🤖 AI/ML Security Tools

| Tool | Description |
|------|-------------|
| [nullsec-llmred](https://github.com/bad-antics/nullsec-llmred) | LLM red teaming and jailbreak testing |
| [nullsec-promptinject](https://github.com/bad-antics/nullsec-promptinject) | Prompt injection vulnerability scanner |
| [nullsec-modelaudit](https://github.com/bad-antics/nullsec-modelaudit) | ML model security auditing |
| [nullsec-adversarial](https://github.com/bad-antics/nullsec-adversarial) | Adversarial example generation |
| [nullsec-datapoisoning](https://github.com/bad-antics/nullsec-datapoisoning) | Training data poisoning detection |

### 🔌 Hardware Security Tools

| Tool | Description |
|------|-------------|
| [nullsec-sdr](https://github.com/bad-antics/nullsec-sdr) | Software-defined radio security analysis |
| [nullsec-rfid](https://github.com/bad-antics/nullsec-rfid) | RFID/NFC exploitation toolkit |
| [nullsec-canbus](https://github.com/bad-antics/nullsec-canbus) | CAN bus analysis and injection |
| [nullsec-jtag](https://github.com/bad-antics/nullsec-jtag) | JTAG/SWD debugging and extraction |
| [nullsec-glitch](https://github.com/bad-antics/nullsec-glitch) | Voltage glitching and fault injection |

### 🛠️ Core Security Tools

| Tool | Language | Description |
|------|----------|-------------|
| [nullsec-kernspy](https://github.com/bad-antics/nullsec-kernspy) | Go | Linux kernel module analyzer |
| [nullsec-memguard](https://github.com/bad-antics/nullsec-memguard) | Zig | Memory protection monitor |
| [nullsec-netseer](https://github.com/bad-antics/nullsec-netseer) | Haskell | Network traffic analyzer |
| [nullsec-sockwatch](https://github.com/bad-antics/nullsec-sockwatch) | Nim | Socket connection monitor |
| [nullsec-cryptocheck](https://github.com/bad-antics/nullsec-cryptocheck) | Ada/SPARK | Cryptographic verifier |
| [nullsec-injector](https://github.com/bad-antics/nullsec-injector) | Rust | Process injection toolkit |
| [nullsec-bingaze](https://github.com/bad-antics/nullsec-bingaze) | C++20 | ELF binary analyzer |
| [nullsec-rootcheck](https://github.com/bad-antics/nullsec-rootcheck) | D | Rootkit detector |

---

## 💻 Tech Stack

<div align="center">

### Systems & Security
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Zig](https://img.shields.io/badge/Zig-F7A41D?style=for-the-badge&logo=zig&logoColor=white)
![Julia](https://img.shields.io/badge/Julia-9558B2?style=for-the-badge&logo=julia&logoColor=white)

### Functional & Type-Safe
![Haskell](https://img.shields.io/badge/Haskell-5D4F85?style=for-the-badge&logo=haskell&logoColor=white)
![OCaml](https://img.shields.io/badge/OCaml-EC6813?style=for-the-badge&logo=ocaml&logoColor=white)
![F#](https://img.shields.io/badge/F%23-378BBA?style=for-the-badge&logo=fsharp&logoColor=white)
![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=for-the-badge&logo=elixir&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=for-the-badge&logo=scala&logoColor=white)

### Mobile & Platform
![Swift](https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Nim](https://img.shields.io/badge/Nim-FFE953?style=for-the-badge&logo=nim&logoColor=black)
![Crystal](https://img.shields.io/badge/Crystal-000000?style=for-the-badge&logo=crystal&logoColor=white)

</div>

---

## 📊 Statistics

<div align="center">

| Metric | Value |
|--------|-------|
| 📦 **Public Repositories** | 520+ |
| 🛠️ **Security Tools** | 140+ |
| 🌍 **Programming Languages** | 18+ |
| 📱 **Mobile Manufacturers** | 18 |
| 🐧 **Linux Editions** | 9 |
| 🖥️ **Architectures** | 4 |
| 🔮 **Julia Security Lines** | 40,000+ |

</div>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=bad-antics&show_icons=true&theme=github_dark&hide_border=true&count_private=true" alt="GitHub Stats" height="180" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bad-antics&layout=compact&theme=github_dark&hide_border=true&langs_count=12&hide=html,css,makefile,dockerfile" alt="Top Languages" height="180" />

<img src="https://github-readme-streak-stats-eight.vercel.app/?user=bad-antics&theme=github-dark-blue&hide_border=true" alt="GitHub Streak" />

<img src="https://github-profile-trophy.vercel.app/?username=bad-antics&theme=darkhub&no-frame=true&column=7&margin-w=15" alt="Trophies" />

</div>

---

## 🔗 Connect

<div align="center">

[![Website](https://img.shields.io/badge/Website-bad--antics.github.io-00C7B7?style=for-the-badge)](https://bad-antics.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-520+_Repos-181717?style=for-the-badge&logo=github)](https://github.com/bad-antics)
[![Julia Docs](https://img.shields.io/badge/Julia_Security_Docs-9558B2?style=for-the-badge&logo=julia)](https://github.com/bad-antics/julia-security-docs)

</div>

---

## 🚀 Community Contributions

Contributing NullSec tools to **93 open PRs (8 merged!)** across the security community:

| Category | PRs | Highlights |
|----------|-----|------------|
| 🏆 **Awesome Lists** | 55+ | awesome-rust, awesome-security, awesome-pentest, awesome-julia |
| 🔴 **Red Team Resources** | 8+ | Red-Teaming-Toolkit, RedTeam-Tools |
| 🐛 **Bug Bounty** | 5+ | nahamsec, KingOfBugBounty |
| 🎓 **Educational** | 5+ | h4cker, Ethical-Hacking-Tools |

**✅ Merged PRs (Community Accepted):**
- [The-Art-of-Hacking/h4cker](https://github.com/The-Art-of-Hacking/h4cker/pull/433) (24.8k ⭐) ✅ MERGED
- [Astrosp/Awesome-OSINT-For-Everything](https://github.com/Astrosp/Awesome-OSINT-For-Everything/pull/52) (2k ⭐) ✅ MERGED
- + 6 more merged PRs

---

<div align="center">

*All tools are intended for authorized security testing and educational purposes only.*

**© 2024-2026 bad-antics** • Security Engineering & Systems Research

</div>
