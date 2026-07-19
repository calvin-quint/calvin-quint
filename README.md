# Calvin Quint

**Detection Engineer** — KQL · Microsoft Sentinel · DFIR · M365 Security

Blue team is where I've built depth, not where I'm stopping. I write and maintain detection logic across Sentinel/Defender as code — Bicep-managed, version-controlled, not click-ops — handle identity security across Entra ID and Intune, and work on certificate-based network access (RADIUS, IPsec VPN architecture). The day-to-day is less "the tool flagged it" and more: write the detection, know exactly why it fires, know exactly what it'd miss.

---

## Where this is headed

Blue team engineering is the foundation for a broader security engineering track, not a fixed lane. Right now that means closing specific gaps rather than collecting certifications for their own sake:

- **Python fluency** — writing tools from scratch, not gluing scripts together to clear a ticket
- **OSCP** — offensive fundamentals, on the theory that you understand detection better once you've built the thing it's supposed to catch
- **AWS security** — cloud is where the next tier of detection and security engineering work actually lives
- **First-principles depth over tool-naming** — "EDR flagged an anomalous process" is a start, not an answer; the goal is explaining what's happening at the process/kernel/API level underneath the alert

## Core stack

| Area | Tools |
|---|---|
| Detection & SIEM | Microsoft Sentinel, KQL, Defender (XDR/Endpoint/Identity) |
| Identity & Endpoint | Entra ID, Intune, Conditional Access |
| Infrastructure as Code | Bicep, ARM |
| Network & Identity Security | RADIUS (EZRADIUS), IPsec VPN architecture, PKI/cert-based auth |
| Scripting / Automation | PowerShell, Python (actively deepening) |
| In progress | AWS security, OSCP / offensive fundamentals |

## What I'm building

- **`security-tools`** — original CLI tools (log parsers, recon utilities) with real structure: argument parsing, proper error handling, a README that explains the design tradeoffs — not a folder of one-off scripts
- **`htb-writeups`** — structured writeups of retired HTB/TryHackMe machines: recon process, exploitation path, and what I'd do differently next time
- **`vuln-research`** — bug bounty and vulnerability research methodology, tooling, and post-disclosure writeups
- **`detection-engineering-translated`** — real detection logic reimplemented against a generic log format in Python, with ATT&CK mapping, so the underlying thinking is legible without knowing what Sentinel is

## Currently following

Recent CVE/KEV activity, detection engineering community work (SigmaHQ, detection.fyi), and Windows/Linux process internals — the layer that explains *why* a detection fires, not just that it did.

---

## GitHub activity

![Calvin's GitHub stats](https://github-readme-stats.vercel.app/api?username=calvin-quint&show_icons=true&hide_title=true&hide_border=true&count_private=true)

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=calvin-quint&layout=compact&hide_border=true)

---

Open to conversations about detection engineering, cloud security, and the blue-team-to-broader-security-engineering path.
