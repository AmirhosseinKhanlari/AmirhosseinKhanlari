# Amirhossein Khanlari

PhD student in Computer Science at **Stony Brook University**, advised by [Prof. Amir Rahmati](https://amir.rahmati.com/) in the Ethos Lab.

I build **LLM-powered pipelines** for **large-scale measurement** and **vulnerability discovery**, mostly on iOS: how apps protect what they sell, and how those protections fail across thousands of apps at once.

---

### Research

- **Clandestine iOS app stores.** Built [Havva](https://github.com/AmirhosseinKhanlari/Havva), the first system for measuring third-party iOS app stores. Over 5.5 months it analyzed **1,767 decrypted IPAs**, uncovering 159 cracked and 308 pirated paid apps and an estimated **$5.26M** in lost developer revenue. *(IMC '26)*
- **iOS in-app subscription security.** An LLM-driven exploitation pipeline (Llama 4) that captures decrypted app traffic over MITM and synthesizes proxy rewrite rules. It flagged **1,829 of 5,776** subscription apps as vulnerable (90.8% confirmed by hand) and found two new attacks that unlock paid subscriptions on non-jailbroken devices, disclosed to Apple and SDK vendors. *(under submission)*
- **The Contagious Interview campaign.** Analysis of trojanized npm repositories sent as fake job coding tests, reconstructing the five-stage kill chain and its C2 rotation. *(IWCC '26)*
- **LLM-assisted exploit generation from SBOMs.** Parsing software bills of materials, matching them against CVE corpora, and prompting LLMs to synthesize proof-of-concept exploits to quantify supply-chain risk.

### Publications

- **A. Khanlari**, A. Rahmati. *Taking a Bite Out of the Forbidden Fruit: Characterizing Third-Party Iranian iOS App Stores.* IMC 2026. [[DOI]](https://doi.org/10.1145/3777912.3839789) [[arXiv]](https://arxiv.org/abs/2604.26343)
- A. Pitumpe, J. Podleski, **A. Khanlari**, P. Dziubecki, D. Muthukumaramani, A. Rahmati. *From Fake Job Offer to Full Environment Compromise: Anatomy of the Contagious Interview Campaign.* IWCC 2026. [[Springer]](https://link.springer.com/chapter/10.1007/978-3-032-35586-7_17)

### Projects

| | |
|---|---|
| [**Havva**](https://github.com/AmirhosseinKhanlari/Havva) | iOS app analysis suite: tests client-integrity defenses (SSL pinning, App Attest, IAP validation) at scale on real iPhones. Python, Objective-C, Frida, FastAPI. |
| [**Osprey**](https://github.com/AmirhosseinKhanlari/Osprey) | IDM-style download manager for macOS with 32-connection segmented downloads, browser capture and crash-safe resume. Swift 6, SwiftUI. |
| [**Putio & Chill**](https://github.com/AmirhosseinKhanlari/putio-and-chill) | put.io streaming client for iPhone, iPad and Apple TV, plus a [web version](https://github.com/AmirhosseinKhanlari/putio-and-chill-web), with subtitles and offline downloads. Swift 6, SwiftUI, React, TypeScript. |

### Service and teaching

- **External reviewer:** USENIX Security 2027 · PoPETs 2027 · ACM ASIA CCS 2027 · The Web Conference (WWW) 2026
- **Teaching assistant:** CSE 331 Computer Security Fundamentals (Stony Brook, Spring 2026) · Computer Architecture (Amirkabir University)

### Interests

AI security · adversarial robustness · vulnerability research · reverse engineering · mobile platform security · supply-chain security · malware analysis · LLMs for offensive security

### Toolbox

- **Languages:** Python · Swift · Objective-C · C/C++ · JavaScript/TypeScript · Bash
- **Security & RE:** Frida · Hopper · otool · Mach-O analysis · dylib injection · MITM proxies · MITRE ATT&CK
- **LLMs:** Llama · Hugging Face Transformers · Anthropic and OpenAI APIs · PyTorch
- **Engineering:** Scrapy · FastAPI · Django · React · SwiftUI · PostgreSQL · Docker · Linux

### Get in touch

[akhanlari@cs.stonybrook.edu](mailto:akhanlari@cs.stonybrook.edu) · [LinkedIn](https://linkedin.com/in/amirhossein-khanlari-110545343/)

<!--
Hidden notes for future me:
- Pin: autoCV, plus 5 best repos that are clean and have a real README
- Keep this README short. Researchers skim.
- Update venue tags when papers move from "under submission" to accepted.
-->
