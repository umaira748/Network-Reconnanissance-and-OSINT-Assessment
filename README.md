<div align="center">
  <img src="evidence/zenmap-local-host-discovery-redacted.jpg" alt="Redacted Zenmap local network discovery evidence" width="900" />
</div>

<div align="center">

# Network Reconnaissance & OSINT Assessment

### Cybersecurity Internship Practical Work | NetworkWalks | Batch 2084

[![Cybersecurity](https://img.shields.io/badge/Focus-Cybersecurity-0A66C2?style=for-the-badge)](https://github.com/topics/cybersecurity)
[![Network Recon](https://img.shields.io/badge/Project-Network%20Reconnaissance-167D9A?style=for-the-badge)](https://github.com/topics/network-reconnaissance)
[![OSINT](https://img.shields.io/badge/Area-OSINT-5B6C8F?style=for-the-badge)](https://github.com/topics/osint)
[![Batch](https://img.shields.io/badge/Batch-2084-333333?style=for-the-badge)](#)

<img src="https://skillicons.dev/icons?i=linux,bash,windows" alt="Linux, Bash and Windows" />

</div>

---

## Project Overview

This repository documents practical reconnaissance and network-discovery exercises completed as part of my cybersecurity internship at **NetworkWalks**. The work covers local host discovery, domain registration review, DNS enumeration, web technology fingerprinting, HTTP response inspection, WAF identification, and relationship visualization.

The repository includes an editable assessment report and screenshot-based evidence for the tasks performed. It is a record of reconnaissance and learning activities—not a claim of successful exploitation or a comprehensive penetration test.


## Assessment Report

The complete report is included in both editable Word and PDF formats:

- **[Open / download the PDF report](NetworkWalks_Public_Security_Reconnaissance_Report.pdf)**
- **[Download the editable Word report](NetworkWalks_Public_Security_Reconnaissance_Report.docx)**

The report contains the scope, authorization disclaimer, methodology, tool-wise observations, findings, limitations, recommendations, evidence appendix, and review/sign-off section.

---

## Technologies & Tools

| Tool | Practical use in this assessment |
|---|---|
| **Zenmap / Nmap** | Ping scan and live-host discovery on my own local network |
| **Whois** | Domain registration and registrar information review |
| **WhatWeb** | Publicly observable web technology fingerprinting |
| **Nslookup** | Domain name resolution |
| **cURL** | HTTP response status and header inspection |
| **Wafw00f** | Web application firewall identification |
| **DNSRecon** | DNS record enumeration |
| **Maltego** | Domain-to-email relationship visualization |
| **theHarvester** | Public-source OSINT collection task attempt |

---

## Tasks & Practical Work

### 1. Local Network Discovery — Zenmap

- Scan profile: **Ping Scan**
- Scope: **My own local network**
- Result shown in the captured scan: **9 hosts up**
- Address space scanned: **256 IP addresses**
- Duration: **9.65 seconds**

The screenshot above is a privacy-redacted copy. The exact subnet, individual device IP addresses, hostnames, and MAC addresses have been hidden. This scan was performed on my own local network; it was **not** a scan of NetworkWalks' corporate network.

### 2. Domain Reconnaissance — `networkwalks.com`

The supplied practical evidence covers:

- Whois registration information
- WhatWeb technology fingerprinting
- Nslookup DNS resolution
- cURL HTTP response and header review
- Wafw00f WAF identification
- DNSRecon DNS record enumeration
- Maltego domain-to-email relationship visualization

These are point-in-time tool observations. A technology fingerprint or WAF identification result does not, by itself, prove that a vulnerability exists or that a security control is effective.

### 3. theHarvester Task Attempt — `microsoft.com`

The screenshot records a theHarvester command attempt with a limit of 50 and the all-sources option. The visible output reports missing API keys for several data sources. The supplied screenshot does not show a completed collection summary; therefore, this repository does not claim successful email enumeration from that run.

---

## Evidence Gallery

The following screenshots are included as practical proof of the activities recorded in the report. Click any image to view it at full size.

### Evidence 01 — Zenmap: Local Host Discovery

[![Redacted Zenmap scan](evidence/zenmap-local-host-discovery-redacted.jpg)](evidence/zenmap-local-host-discovery-redacted.jpg)

*The public copy masks local device identifiers and the exact private subnet.*

### Evidence 02 — Whois: Domain Registration Review

[![Whois output](evidence/whois-domain-registration.jpg)](evidence/whois-domain-registration.jpg)

### Evidence 03 — WhatWeb, Nslookup & cURL

[![Web fingerprinting, DNS resolution and HTTP headers](evidence/whatweb-nslookup-curl-redacted.jpg)](evidence/whatweb-nslookup-curl-redacted.jpg)

*The cURL cookie value has been redacted in the public evidence copy.*

### Evidence 04 — Wafw00f & DNSRecon

[![WAF identification and DNS enumeration](evidence/wafw00f-dnsrecon.jpg)](evidence/wafw00f-dnsrecon.jpg)

### Evidence 05 — Maltego: Relationship Graph

[![Maltego relationship graph](evidence/maltego-relationship-graph.jpg)](evidence/maltego-relationship-graph.jpg)

### Evidence 06 — theHarvester: Task Attempt

[![theHarvester output](evidence/theharvester-attempt.jpg)](evidence/theharvester-attempt.jpg)

*The screenshot shows missing API-key notices; it is documented as an attempt, not a completed result.*

---

## Key Observations & Limitations

- Zenmap reported nine responding hosts on my own local network during the captured ping scan.
- Whois, DNS, web fingerprinting, HTTP header, WAF, and Maltego outputs provide reconnaissance observations only.
- DNS and web service information can change after the time of collection.
- Wafw00f identification does not validate WAF effectiveness.
- No exploitable vulnerability is confirmed by the supplied screenshots.
- No exploitation, authenticated testing, or remediation retest is claimed.
- theHarvester evidence is incomplete and does not establish successful collection.

## Recommendations

1. Maintain an approved inventory of network-connected devices.
2. Review public DNS records periodically and remove obsolete records through the authorized administrator.
3. Keep public-facing web technologies supported and updated.
4. Review HTTP security headers against an approved security baseline.
5. Maintain WAF rules, monitoring, and logging through the responsible security team.
6. Protect organizational email accounts with appropriate email-security controls.
7. Store original evidence securely and redact sensitive information before sharing.
8. Perform additional testing only with explicit written authorization and a defined scope.

## Security & Ethical Use

This repository is intended for educational and professional portfolio documentation. The local network scan shown here was performed on my own network. Any domain-related activity must remain within the exact scope and permissions approved by the relevant organization or asset owner.

- Do not scan, probe, access, or disrupt systems without explicit authorization.
- Do not treat reconnaissance output as proof of a vulnerability.
- Do not publish internal IP addresses, MAC addresses, hostnames, cookies, credentials, or other sensitive data.
- The presence of an internship recommendation letter does not itself authorize public disclosure of an organization's technical information.

**Publication note:** Obtain NetworkWalks' approval before making this repository public because it contains organization-related reconnaissance evidence. Keep it private until publication is approved.

---

## Author

**Umaira Asghar**  
Cybersecurity Intern — NetworkWalks  
Linkedln:https://www.linkedin.com/in/umaira-asghar-825894371

---

<div align="center">

### LEARN • EXPLORE • PRACTICE • SECURE

*Documenting practical learning through responsible cybersecurity.*

</div>
