# Phishing URL Detection & Investigation Tool

## Project Overview

This project demonstrates the development of a Python-based phishing detection tool designed to identify suspicious URLs and simulate the type of analysis performed by a Security Operations Center (SOC) analyst during phishing investigations.

The tool analyzes URLs for common phishing indicators such as suspicious keywords, insecure protocols, URL shorteners, IP-based domains, and newly registered domains.

This project was intentionally developed in stages to demonstrate how a simple security script can evolve into a more robust investigation tool.

---

## Project Evolution

The phishing detection tool was built incrementally to reflect how security tools are often developed and improved in real-world environments.

| Version | Script | Description |
|-------|-------|-------------|
| Version 1 | `phishing_detector.py` | Basic phishing detection script that identifies suspicious keywords, HTTP usage, URL shorteners, and IP-based URLs. |
| Version 2 | `phishing_detector_expanded.py` | Expanded version that includes domain intelligence using WHOIS lookups and structured investigation output. |
| Version 3 | `phishing_investigation_tool.py`| Full SOC-style investigation tool with advanced detection capabilities (planned). |

Phishing Detector [Version 1](phishing_detector.py) 

Phishing Detector Expanded [Version 2](phishing_detector_expanded.py)

Phishing Investigation Tool [Version 3](phishing_investigation_tool.py) 

---

## Version 1: Basic Phishing URL Detector

Script:

`phishing_detector.py` [Linked Script](phishing_detector.py)

This version performs basic URL analysis and flags common phishing indicators.

Detection checks include:

- Suspicious keywords (login, verify, account, secure)
- URLs using HTTP instead of HTTPS
- URL shorteners
- IP address-based URLs

---

## Version 2: Expanded Phishing Investigation Tool

Script:

`phishing_detector_expanded.py` [Linked Script](phishing_detector_expanded.py)

The expanded version introduces additional analysis capabilities and produces structured investigation output.

New capabilities include:

- Domain intelligence using WHOIS data
- Detection of newly registered domains
- Structured investigation report output
- Improved phishing indicator analysis

### Example Investigation Output

Target URL: hxxp://paypa1-login-secure.com

Domain: paypa1-login-secure.com

[Base Output Example](python_output_example.png)

[URL Investigation Output Example](phishing_url_investigation_outcome.png)

---

## Skills Demonstrated

- Python scripting
- Cybersecurity automation
- URL and domain analysis
- Domain intelligence investigation (WHOIS)
- Security detection logic development

---

## Future Improvements

Planned enhancements include:

- Phishing brand impersonation detection (typosquatting)
- Threat intelligence enrichment
- Automated risk scoring model
- Bulk URL analysis capability
- Exportable investigation reports
