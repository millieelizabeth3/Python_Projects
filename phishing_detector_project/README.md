# Phishing Detection & URL Risk Analysis Tool

## Overview
A Python-based tool that analyzes URLs for common phishing indicators such as:
- Suspicious keywords
- URL shorteners
- Insecure protocols (HTTP)
- IP addresses in URLs

The tool assigns a risk score and highlights potential threats.

## Skills Demonstrated
- Python programming
- Cybersecurity threat detection
- URL parsing and analysis

## Example Output
Analyzing URL: http://paypa1-login-secure.com

⚠️ Suspicious keyword found: login
⚠️ URL uses HTTP instead of HTTPS
🚨 HIGH PHISHING RISK

## Future Improvements
- Check domain age using WHOIS
- Integrate VirusTotal API for live URL threat intelligence
- Add email header analysis
- Build a GUI or web dashboard
