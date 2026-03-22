# PoC4CVEs

A curated list of working Proof-of-Concept (PoC) exploits for publicly disclosed CVEs. This collection includes both references to existing PoCs found online and original exploit scripts developed for security research purposes.

## ⚠️ Legal Disclaimer

**FOR EDUCATIONAL AND AUTHORIZED TESTING PURPOSES ONLY**

**Unauthorized access to computer systems is illegal.** Users are solely responsible for ensuring they have proper authorization before testing any exploit. The repository maintainer assumes no liability for misuse of the information provided. This repository is intended for:
- Security researchers conducting authorized vulnerability assessments
- Penetration testers with explicit permissions
- Educational purposes in controlled environments
- Defensive security teams testing detection capabilities


## 📋 CVE List

### 2025

| CVE ID | Type | CVSS | PoC Link |
|--------|------|------|----------|
| CVE-2025-55182 | Authenticated RCE | N/A | [Link](https://github.com/gunzf0x/CVE-2025-60787) |
| CVE-2025-55182 | Unauthenticated ![RCE](https://img.shields.io/badge/RCE-critical-red) | 10.0 | [Link](https://github.com/freeqaz/react2shell) |
| CVE-2025-49132 | Unauthenticated ![RCE](https://img.shields.io/badge/RCE-critical-red) | 10.0 | [Link](https://github.com/Pwndalf/CVE-2025-49132-PoC) |
| CVE-2025-47812 | Unauthenticated ![RCE](https://img.shields.io/badge/RCE-critical-red) | 10.0 | [Link](https://github.com/0xcan1337/CVE-2025-47812-poC) |
| CVE-2025-6019 | Linux Local Privilege Escalation ![LPE](https://img.shields.io/badge/LPE-high-red) | 7.0 | [Link](https://github.com/MichaelVenturella/CVE-2025-6018-6019-PoC) |
| CVE-2025-4138 | Arbitrary File Write ![AFW](https://img.shields.io/badge/AFW-high-red) | 7.5 | [Link](https://github.com/MichaelVenturella/CVE-2025-6018-6019-PoC) |
| CVE-2025-2304 | Privilege Escalation ![PE](https://img.shields.io/badge/PE-critical-red) | 9.4 | [Link](https://github.com/lil0xplorer/CVE-2025-2304-PoC) |


### 2024

| CVE ID | Type | CVSS | PoC Link |
|--------|------|------|----------|
| CVE-2024-46987 | SQL Injection ![SQLi](https://img.shields.io/badge/SQLi-critical-red) | 9.9 | VULN URL: http://IP/zm/index.php?view=request&request=event&action=removetag&tid=1, VULN PAR: tid |
| CVE-2024-46987 | Path Traversal ![LFI](https://img.shields.io/badge/LFI-high-red) | 7.7 | [Link](https://github.com/owen2345/camaleon-cms/security/advisories/GHSA-cp65-5m9r-vc2c) |

## 🔍 How to Use

1. **Find the CVE** you're interested in from the tables above
2. **Click the PoC link** to access the exploit code or write-up

> **Note:** Most PoCs link to external repositories. When original scripts are included in `/exploits/`.
