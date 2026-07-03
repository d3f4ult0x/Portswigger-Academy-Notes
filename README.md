# PortSwigger Academy Notes

> A structured knowledge base of notes, methodologies, payloads, and practical techniques derived from the **PortSwigger Web Security Academy**. This repository serves as a centralized reference for web application security testing using **Burp Suite** and industry-standard penetration testing practices.

<p align="center">

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-In%20Progress-orange)
![Platform](https://img.shields.io/badge/Platform-PortSwigger%20Academy-red)
![Security](https://img.shields.io/badge/Web-Security-blue)
![Burp Suite](https://img.shields.io/badge/Burp-Suite-orange)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

</p>

---

# Table of Contents

- [Overview](#overview)
- [Objectives](#objectives)
- [Repository Structure](#repository-structure)
- [Learning Roadmap](#learning-roadmap)
- [Topics Covered](#topics-covered)
- [Progress Tracker](#progress-tracker)
- [Repository Standards](#repository-standards)
- [Methodology](#methodology)
- [Tools](#tools)
- [References](#references)
- [Roadmap](#roadmap)
- [Disclaimer](#disclaimer)
- [License](#license)

---

# Overview

This repository documents concepts, testing methodologies, payloads, and practical techniques learned while working through the **PortSwigger Web Security Academy**.

The primary objective is to create a comprehensive reference for web application penetration testing rather than a collection of lab solutions.

The repository includes:

- Technical notes
- Vulnerability explanations
- Testing methodologies
- Burp Suite workflows
- Payload collections
- HTTP request examples
- Remediation summaries
- Practical cheat sheets
- Personal observations and research

All documentation is written for educational purposes and focuses on understanding vulnerability classes and exploitation methodology.

---

# Objectives

- Build a structured knowledge base for web security.
- Document common attack methodologies.
- Develop reusable testing checklists.
- Organize payload collections.
- Improve Burp Suite proficiency.
- Create concise references for future engagements.
- Track completion of all PortSwigger Academy topics.

---

# Repository Structure

```text
Portswigger-Academy-Notes
│
├── Server-Side
│   ├── SQL Injection
│   ├── Authentication
│   ├── Path Traversal
│   ├── Command Injection
│   ├── Business Logic Vulnerabilities
│   ├── Information Disclosure
│   ├── Access Control
│   ├── File Upload Vulnerabilities
│   ├── Race Conditions
│   ├── SSRF
│   ├── XXE
│   ├── NoSQL Injection
│   ├── API Testing
│   └── Web Cache Deception
│
├── Client-Side
│   ├── Cross-Site Scripting
│   ├── CSRF
│   ├── CORS
│   ├── Clickjacking
│   ├── DOM-Based Vulnerabilities
│   └── WebSockets
│
├── Advanced
│   ├── Insecure Deserialization
│   ├── Web LLM Attacks
│   ├── GraphQL
│   ├── SSTI
│   ├── Web Cache Poisoning
│   ├── HTTP Host Header
│   ├── HTTP Request Smuggling
│   ├── OAuth
│   ├── JWT
│   ├── Prototype Pollution
│   └── Essential Skills
│
├── Payloads
├── Cheat Sheets
├── Burp Suite
├── Images
└── README.md
```

---

# Learning Roadmap

## Server-Side Security

- SQL Injection
- Authentication
- Path Traversal
- Command Injection
- Business Logic Vulnerabilities
- Information Disclosure
- Access Control
- File Upload Vulnerabilities
- Race Conditions
- SSRF
- XXE Injection
- NoSQL Injection
- API Testing
- Web Cache Deception

---

## Client-Side Security

- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- Cross-Origin Resource Sharing (CORS)
- Clickjacking
- DOM-Based Vulnerabilities
- WebSockets

---

## Advanced Security

- Insecure Deserialization
- Web LLM Attacks
- GraphQL API Vulnerabilities
- Server-Side Template Injection
- Web Cache Poisoning
- HTTP Host Header Attacks
- HTTP Request Smuggling
- OAuth Authentication
- JWT Attacks
- Prototype Pollution
- Essential Skills

---

# Topics Covered

| Category                       | Labs | Status |
| ------------------------------ | ---: | :----: |
| SQL Injection                  |   18 |   ⏳   |
| Authentication                 |   14 |   ⏳   |
| Path Traversal                 |    6 |   ⏳   |
| Command Injection              |    5 |   ⏳   |
| Business Logic Vulnerabilities |   11 |   ⏳   |
| Information Disclosure         |    5 |   ⏳   |
| Access Control                 |   13 |   ⏳   |
| File Upload Vulnerabilities    |    7 |   ⏳   |
| Race Conditions                |    6 |   ⏳   |
| SSRF                           |    7 |   ⏳   |
| XXE                            |    9 |   ⏳   |
| NoSQL Injection                |    4 |   ⏳   |
| API Testing                    |    5 |   ⏳   |
| Web Cache Deception            |    5 |   ⏳   |
| XSS                            |   30 |   ⏳   |
| CSRF                           |   12 |   ⏳   |
| CORS                           |    3 |   ⏳   |
| Clickjacking                   |    5 |   ⏳   |
| DOM-Based Vulnerabilities      |    7 |   ⏳   |
| WebSockets                     |    3 |   ⏳   |
| Insecure Deserialization       |   10 |   ⏳   |
| Web LLM Attacks                |    7 |   ⏳   |
| GraphQL                        |    5 |   ⏳   |
| SSTI                           |    7 |   ⏳   |
| Web Cache Poisoning            |   13 |   ⏳   |
| HTTP Host Header Attacks       |    7 |   ⏳   |
| HTTP Request Smuggling         |   22 |   ⏳   |
| OAuth Authentication           |    6 |   ⏳   |
| JWT Attacks                    |    8 |   ⏳   |
| Prototype Pollution            |   10 |   ⏳   |
| Essential Skills               |    2 |   ⏳   |

**Total Labs:** **272**

---

# Progress Tracker

## Overall Progress

```
Progress

□□□□□□□□□□□□□□ 0%

Completed: 0 / 272 Labs
```

---

## Completion Checklist

### Server-Side

- [ ] SQL Injection
- [ ] Authentication
- [ ] Path Traversal
- [ ] Command Injection
- [ ] Business Logic Vulnerabilities
- [ ] Information Disclosure
- [ ] Access Control
- [ ] File Upload Vulnerabilities
- [ ] Race Conditions
- [ ] SSRF
- [ ] XXE
- [ ] NoSQL Injection
- [ ] API Testing
- [ ] Web Cache Deception

### Client-Side

- [ ] Cross-Site Scripting
- [ ] CSRF
- [ ] CORS
- [ ] Clickjacking
- [ ] DOM-Based Vulnerabilities
- [ ] WebSockets

### Advanced

- [ ] Insecure Deserialization
- [ ] Web LLM Attacks
- [ ] GraphQL
- [ ] SSTI
- [ ] Web Cache Poisoning
- [ ] HTTP Host Header Attacks
- [ ] HTTP Request Smuggling
- [ ] OAuth
- [ ] JWT
- [ ] Prototype Pollution
- [ ] Essential Skills

---

# Repository Standards

Each topic directory follows a consistent format:

```
Topic
│
├── README.md
├── Notes.md
├── Methodology.md
├── Payloads.md
├── References.md
└── Images
```

---

# Methodology

Each vulnerability category is documented using the following structure:

1. Overview
2. Root Cause
3. Impact
4. Identification
5. Exploitation
6. Burp Suite Workflow
7. Payloads
8. Prevention
9. References

---

# Tools

- Burp Suite Community / Professional
- Firefox Developer Edition
- Chromium
- Kali Linux
- Parrot Security OS
- OWASP Testing Guide
- Developer Tools
- cURL
- Postman
- Windows

---

# References

- PortSwigger Web Security Academy
- PortSwigger Documentation
- OWASP Top 10
- OWASP Web Security Testing Guide
- CWE
- CVE Program
- MITRE ATT&CK

---

# Roadmap

- [ ] Complete all 272 Academy labs
- [ ] Publish notes for every vulnerability
- [ ] Expand payload library
- [ ] Create Burp Suite cheat sheets
- [ ] Add exploitation flow diagrams
- [ ] Include remediation guidance
- [ ] Develop reusable testing checklists
- [ ] Document useful Burp extensions
- [ ] Improve repository organization
- [ ] Maintain regular updates

---

# Disclaimer

This repository is intended exclusively for educational and authorized security testing.

The material provided here is designed to promote responsible security research, improve understanding of web application vulnerabilities, and support defensive security practices.

Do not use any techniques or payloads contained in this repository against systems without explicit authorization.

---

# License

This project is licensed under the **MIT License**.

See the `LICENSE` file for additional information.

---

## Acknowledgements

Special thanks to the **PortSwigger Web Security Academy** team for providing one of the most comprehensive free web application security training platforms available.
