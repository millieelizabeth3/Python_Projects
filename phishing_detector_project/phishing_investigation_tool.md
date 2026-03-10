## Expanded Version: Domain Intelligence & Investigation Output

The expanded version of the phishing detection tool enhances the original script by incorporating additional analysis capabilities and structured investigation output.

This version simulates the type of analysis a SOC (Security Operations Center) analyst might perform when investigating suspicious URLs.

### New Capabilities

Compared to the base version, the expanded tool introduces:

* **Domain intelligence analysis**

  * Checks domain registration age using WHOIS data
  * Flags newly registered domains often associated with phishing campaigns

* **Structured investigation output**

  * Generates a formatted investigation report
  * Displays target URL, extracted domain, detected indicators, and risk assessment

* **Improved phishing indicator detection**

  * Suspicious keywords commonly used in phishing attacks
  * Insecure HTTP protocol detection
  * URL shortener identification
  * IP address-based domains

### Example Investigation Output

Target URL: hxxps://bit.ly/free-gift

[Example output](phishing_url_investigation_outcome.png)

### Script File

[Phishing Investigation Tool](phishing_investigation_tool.py)

### Skills Demonstrated

* Python scripting
*URL parsing and analysis
* Domain intelligence investigation
* Security automation concepts
* Phishing threat detection techniques
