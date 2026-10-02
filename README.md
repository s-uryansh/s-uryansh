# Hi, I'm Suryansh Rohil 👋

**Backend & Systems Engineer · Security Research** · [Portfolio](https://s-uryansh.vercel.app/)

I build backend systems in Go and C/C++, and research security at the kernel and binary level. Security is a design input, not a patch.

- Shipped a 10-module warehouse inventory and dispatch system for a live enterprise client
- Co-authored an IEEE paper on parallel blockchain execution (4.3x throughput)
- Merged PRs in [freellmapi](https://github.com/tashfeenahmed/freellmapi) and Epic Games' [PixelStreamingInfrastructure](https://github.com/EpicGames/PixelStreamingInfrastructure)
- Focus: eBPF, TPM attestation, binary analysis, post-quantum migration

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/suryansh-rohil-982a21270/)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:suryanshrohilwork@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://www.instagram.com/suryansh.rohil/)

---


## Featured Projects

### [CipherFault](https://github.com/s-uryansh/CipherFault)
Crypto-usage evidence engine for compiled binaries. Ghidra P-code lifting plus a GNN recognizer for classical and post-quantum primitives. Deterministic taint engine emits CWE-mapped facts with provenance paths. CycloneDX 1.6 CBOM output. Trained on a 9,295-binary corpus across GCC/Clang, x86_64/AArch64.

### [vanguard-linux-poc](https://github.com/s-uryansh/vanguard-linux-poc)
Hardware-anchored attestation for Linux. TPM2 quote bound to TLS session (RFC 9266) closes relay attacks. eBPF-LSM monitors kernel module loads and ptrace. Verified ALLOW/DENY on Secure Boot on/off hosts.

### [GradGuard](https://github.com/s-uryansh/GradGuard)
Adaptive SSH honeypot in pure Go. Ephemeral Docker container per session. ML (Logistic Regression, Naive Bayes, anomaly detection) trained on 170MB+ of Cowrie/CIC-IDS/NSL-KDD scores intent live. Mutates the environment to defeat fingerprinting. eBPF `execve` tracing, egress sinkhole, AWS honeytokens.

### [GradPQC](https://github.com/s-uryansh/GradPQC)
Cryptographic inventory and governance platform. Go scanner, CT-log subdomain discovery, Quantum Migration Risk Scores. PNB PSB Hackathon 2026.

### [OPT-MorphDAG](https://github.com/s-uryansh/OPT-MorphDAG)
Conflict-aware parallel transaction scheduler for DAG blockchains. [IEEE paper](https://ieeexplore.ieee.org/document/11310865/).

### [GradLedger](https://github.com/s-uryansh/GradLedger) · [GladMeds](https://gladmeds.vercel.app/) · [PortaYourPCB](https://portayourpcb.vercel.app/)
Blockchain alumni mentorship platform. · AI healthcare and emergency app. · Live full-stack platform for a startup.

---

## Open Source
- **freellmapi**: admin hardening. Stricter CSP, per-IP rate limiting, password-gated key export ([#498](https://github.com/tashfeenahmed/freellmapi/pull/498))
- **PixelStreamingInfrastructure**: opt-in streamer token auth on signalling server
- **MorphDAG**: benchmarking feature

## Achievements
🥇 Smart SNU Hackathon '25 · 📄 IEEE 2025

---

### Research: [OPT-MorphDAG](https://github.com/s-uryansh/OPT-MorphDAG)  
📄 [Paper (IEEE)](https://ieeexplore.ieee.org/document/11310865/footnotes#full-text-header)  
Optimized DAG-based blockchain designed for **throughput and concurrency improvements**.  
By introducing **per-account read/write frequency classification**, OPT-MorphDAG improves transaction scheduling, reducing block latency and increasing throughput up to **2.5× over serial execution** and **1.4× over MorphDAG baseline**, with no inconsistencies.  

---

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=s-uryansh&theme=transparent&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=s-uryansh&theme=transparent&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=s-uryansh&theme=transparent&hide_border=false&layout=compact&hide=Jupyter%20Notebook)
