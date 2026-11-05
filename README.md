<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=5,4,24,8,30&height=180&section=header&text=Riad%20Moudjahed&fontSize=36&fontColor=ffffff&fontAlignY=35&descSize=18&animation=twinkling"/>

<p align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=AI+Agent+Security+Testing;LLM+Red+Teamer;AI+Security+Engineer;Bug+Hunter" alt="Typing SVG" /></a>
</p>

<img align="right" height="190" width="290" alt="GIF" src="pwc.nl.gif"/>
<img align="right" src="spacer.png"/>

<p align="justify">I test AI agents the way an attacker would. My focus is agents that call tools, read customer data and take actions, and the ways untrusted content can turn them against the systems they serve. I also build security frameworks for LLM and RAG systems: red teaming, vulnerability assessment, operational controls, incident response and compliance. Current work: Agent Range, a RAG security engineering framework, 22 AI red team labs, the ModelGuard ML scanner and AI-powered security tools.
</p>

---

## Agent Range

**[Agent Range](https://riadmoudjahed.github.io/agent-range/)** is my security testing service for companies shipping AI agents with tool access. Fixed-scope assessments find what an attacker could actually make the agent do, with proof of impact, fixes in code and a retest of every finding.

[Sample report](https://riadmoudjahed.github.io/agent-range/sample-report.html) · [Book a free 30-minute threat-model review](https://cal.com/riad-moudjahed-favfz4/threat-model-review)

### [Larkspur: a vulnerable AI agent lab](https://github.com/RiadMoudjahed/larkspur-lab)
A fictional shop with two tool-calling agents, three challenges graded from real side effects in the database, and a fixed mode where every fix lives in code. Against a local 7B model, a single customer support ticket made the staff triage agent approve a refund ten times its policy limit in 4 of 5 runs.

---

## AI security projects

### AI Red Team Lab Series
**22 hands-on labs** teaching LLM adversarial attacks across **4 difficulty tiers** (Easy to Expert). Covers prompt injection, jailbreaking, model manipulation, guardrail bypasses and advanced evasion techniques for GPT, Claude and Llama models.

### [ModelGuard](https://github.com/RiadMoudjahed/ModelGuard)
Scans AI/ML models for malicious code, backdoors and security vulnerabilities, using entropy analysis, pattern matching and optional AI-powered deep analysis through a local Ollama model, so nothing leaves your machine.

### [GCP AI Security Auditor](https://github.com/RiadMoudjahed/GCP-AI-Security-Auditor)
Automated security auditing for Google Cloud AI/ML services. Scans Vertex AI models, AI Platform resources and ML workflows for misconfigurations, policy violations and security risks, and generates compliance reports aligned with cloud security best practices.

### [AI-Powered PCAP Analyzer](https://github.com/RiadMoudjahed/AI-Powered-PCAP-Analyzer)
Automated network threat detection using **Ollama LLMs and Scapy**. Analyzes packet captures to detect DDoS, port scans and suspicious patterns. Tested on **11K+ packets**: identified a DDoS attack (56% traffic concentration), extracted IOCs automatically and generated actionable security reports.

### [LLM-Powered Backdoor Analyzer](https://github.com/RiadMoudjahed/SOC-Analyst-Projects/tree/main/SIEM/Backdoor%20Activity%20Analyzer)
Combines **Isolation Forest ML** (92% accuracy, 67% fewer false positives) with **Ollama LLM analysis** for C2 detection. Processes **15K+ logs in under 3 seconds** and writes threat reports in SOC analyst terms.

---

## Cloud and traditional security projects

### [GCP Security Scanner](https://github.com/RiadMoudjahed/GCP-Security-Scanner)
Automated security assessment for Google Cloud Platform across IAM, Compute Engine, Cloud Storage, networking and logging. Identifies misconfigurations, generates risk reports and recommends remediation aligned with CIS GCP benchmarks.

### [SOC Home Lab Environment](https://github.com/RiadMoudjahed/SOC-Analyst-Projects/blob/main/Networking/Full%20SOC%20Analyst%20LAB%20%26%20Network%20Configuring.md)
SOC infrastructure with **VMware, pfSense and Wazuh SIEM**: threat detection, network segmentation and SPAN port mirroring for forensic analysis. **35+ completed labs** covering incident response, threat hunting and SIEM rule creation.

### [Malware Reverse Engineering Lab](https://github.com/RiadMoudjahed/Keylogger_MalwareAnalysis_Lab)
**15+ guided exercises** in static and dynamic malware analysis with **Ghidra, dnSpy and Wireshark**, built around a custom keylogger sample: hash identification, PE analysis, PCAP inspection and IOC extraction.

### [SQL Injection Prevention Demo](https://github.com/RiadMoudjahed/SOC-Analyst-Projects/blob/main/Vulnerability%20Management/SQL%20Injection%20Prevention%20Demo.md)
Live exploitation and mitigation for the **OWASP Top 10**: vulnerable and secure Python login systems showing parameterized queries and bcrypt authentication.

### [Vulnerability Assessment with Nessus](https://github.com/RiadMoudjahed/SOC-Analyst-Projects/blob/main/Vulnerability%20Management/Basic%20Vulnerability%20Analysis%20With%20Nessus.md)
The full vulnerability management lifecycle: scanning, CVE prioritization with CVSS scoring, and remediation planning for simulated infrastructure.

---

## Technical arsenal

**AI security and red teaming**
AI agent security testing · Tool abuse and indirect prompt injection · MCP security · Jailbreaking · Model manipulation · OWASP LLM Top 10 · Adversarial ML

**Cloud security**
Google Cloud Platform (GCP) · Cloud IAM · Cloud Security Posture Management · CIS Benchmarks · Cloud Audit Logging

**AI/ML development**
Python (Scikit-learn, Pandas) · Ollama integration · Isolation Forest · Scapy · Feature engineering

**Security operations**
Wazuh SIEM · Nessus · IDS/IPS · PCAP analysis · Threat hunting · Incident response

**Malware and forensics**
Ghidra · dnSpy · Binary Ninja · Autopsy · FTK Imager · Volatility · Wireshark · IOC extraction

**Development and automation**
Python · Bash · SQL · Secure coding · API integration · Security tool development

**Frameworks**
MITRE ATT&CK · NIST Cybersecurity Framework · OWASP Top 10 · OWASP LLM Top 10

<p align="center">
<img src="https://skillicons.dev/icons?i=py,bash,pytorch,tensorflow,sklearn,gcp,aws,github,git,githubactions,kali&perline=12" alt="Tech Stack"/>
</p>

---

## Writing

**[19 technical articles on Medium](https://medium.com/@riadmouja47)** (1.2k+ reads). Recent posts:

- [Beyond the Voice: Architecture for Preventing Deepfake Exploitation in AI Dubbing](https://medium.com/@riadmouja47/beyond-the-voice-architecture-for-preventing-deepfake-exploitation-in-ai-dubbing-64aa7594fb61)
- [The Secret Behind Anthropic's Secured Models](https://medium.com/@riadmouja47/the-secret-behind-anthropics-secured-models-b9dc81b566c4)
- [The AI Security Handbook: Defending the Machine Learning Pipeline](https://medium.com/@riadmouja47/the-ai-security-handbook-defending-the-machine-learning-pipeline-e196cbe72773)
- [Demystifying GPT: A Deep Dive into the Future of AI Security](https://medium.com/@riadmouja47/demystifying-gpt-a-deep-dive-into-the-future-of-ai-securitya-2026-deep-dive-for-ai-security-cb923aa140c7)
- [Coding Made for Anyone… Really!](https://medium.com/@riadmouja47/coding-made-for-anyone-really-96b05e865f27)

---

## Certifications

- [Google Cloud Cybersecurity Certificate](https://www.credly.com/badges/e3df8043-40f6-4124-ace0-1d2f4484e92a/public_url) (2026)
- Securiti AI Security & Governance (2025, valid to December 2027)
- [Google Cybersecurity Professional Certificate](https://coursera.org/verify/professional-cert/YSNROCQLDPDS) (2025)
- [IBM Cybersecurity Analyst Professional Certificate](https://coursera.org/verify/professional-cert/5RK1U3QW03YV) (2025)

---

## Let's connect

[![Agent Range](https://img.shields.io/badge/Agent%20Range-0E6B68?logoColor=white)](https://riadmoudjahed.github.io/agent-range/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/riad-moudjahed/) [![Medium](https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white)](https://medium.com/@riadmouja47) [![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.com/users/907345577669435423)

**Open to:** AI agent security assessments through [Agent Range](https://riadmoudjahed.github.io/agent-range/) · AI Security roles · Security Researcher · Remote opportunities (US, Europe, Middle East)

---

> *"Tawakkul, consistency, and passion: my formula for growth."*

---

<p align="center">
  <img
    width="99%"
    src="https://github-readme-activity-graph.vercel.app/graph?username=RiadMoudjahed&theme=github-compact&hide_border=true&area=true"
    alt="GitHub Activity Graph"
  />
</p>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=5,4,24,8,30&height=100&section=footer"/>
</p>
