# 🚢 shipcrawler.oversight.ee

**Maritime OSINT Attack Surface Assessment — Demo Dashboard**

Public-facing demonstration of maritime cybersecurity OSINT capabilities built with [Shipcrawler](https://github.com/ahmdngi/shipcrawler) (IEEE Access 2026).

## MV EXAMPLE (IMO 9999999)

Fictional Panamax bulk carrier used to showcase:

- **8 Red-Team Attack Vectors** — Crew phishing, AIS/GPS spoofing, VSAT interception, ECDIS manipulation, USB drop, ransomware, supply chain compromise
- **7 Vulnerabilities** — Default ECDIS credentials, flat IT/OT network, unpatched VSAT firmware, and more
- **15 Detection Indicators** — Mapped to MITRE ATT&CK for ICS
- **Elastic SIEM Rules & Zeek Scripts** — Production-ready detection logic
- **Interactive Global Map** — MilitaryMap component with mouse-zoom and drag-to-pan

> ⚠️ **All data on this site is fictional.** Built for portfolio/presentation purposes only.

## Stack

- **Framework:** Next.js 16 + Tailwind CSS v4
- **Map:** Framer MilitaryMap with tactical dark theme
- **Export:** Static HTML — zero server dependencies
- **OSINT Engine:** Shipcrawler v6.3 — Maritime OSINT Framework

## Related

- [Shipcrawler](https://github.com/ahmdngi/shipcrawler) — Maritime OSINT framework
- [Project Haris](https://github.com/ahmdngi) — Maritime cybersecurity edge platform
