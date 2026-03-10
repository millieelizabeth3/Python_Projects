# Phishing Detection & URL Risk Analysis Tool
← Back to [Python Security Projects](../)

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
Analyzing URL: hxxp://paypa1-login-secure.com

⚠️ Suspicious keyword found: login

⚠️ URL uses HTTP instead of HTTPS

🚨 HIGH PHISHING RISK

[Example Image](./phihing_detector_output_example.png/)

## Future Improvements
- Check domain age using WHOIS
- Integrate VirusTotal API for live URL threat intelligence
- Add email header analysis
- Build a GUI or web dashboard

## Expanded Version - Domain age using WHOIS

An expanded version of the phishing detection tool was developed to include domain intelligence using WHOIS data.

Additional detection capabilities include:

* Domain registration age analysis
* Enhanced phishing risk scoring
* Improved domain parsing

[Script File](./phishing_detector_expanded.py)
