# Web-Multi-Scan
**running multiple scanning tools to discover vulnerabilities, effectively judge false-positives, collectively correlate results** and **saves precious time**
#  _The Multi-Tool Web Vulnerability Scanner_
Download and use it if you still haven't upgraded to Python 3. Kindly note that the v1.1 (Python2.7) will not be enhanced further._

## Evolution:
> It is quite a fuss for a pentester to perform _**binge-tool-scanning**_ (_running security scanning tools one after the other_) sans automation. Unless you are a pro at automating stuff, it is a herculean task to perform binge-scan for each and every engagement. The ultimate goal of this program is to solve this problem through automation; viz. **running multiple scanning tools to discover vulnerabilities, effectively judge false-positives, collectively correlate results** and **saves precious time**; all these under one roof.<p>Enter **RapidScan**.

## Features
- **one-step installation**.
- **executes a multitude of security scanning tools**, does other **custom coded checks** and **prints the results spontaneously**.
- some of the tools include `nmap, dnsrecon, wafw00f, uniscan, sslyze, fierce, lbd, theharvester, amass, nikto` etc executes under one entity.
- saves a lot of time, **indeed a lot time!**.
- **checks for same vulnerabilities with multiple tools** to help you **zero-in on false positives** effectively.
- **extremely light-weight and not process intensive.**
- **legends** to help you understand which tests may take longer time, so you can `Ctrl+C` to skip if needed.
- **association with OWASP Top 10 & CWE 25** on the list of vulnerabilities discovered. (_**under development**_)
- **critical, high, medium, low and informational** classification of vulnerabilities.
- **vulnerability definitions** guides you what the vulnerability actually is and the threat it can pose.
- **remediation** tells you how to plug/fix the found vulnerability.
- **executive summary** gives you an overall context of the scan performed with critical, high, low and informational issues discovered.
- **artificial intelligence** to deploy tools automatically depending upon the issues found. for eg; automates the launch of `wpscan` and `plecost` tools when a wordpress installation is found. (_**under development**_)
- **detailed comprehensive report** in a portable document format (*.pdf) with complete details of the scans and tools used. (_**under development**_)
- **on the run metasploit auxilliary modules** to discover more vulnerabilities. (_**under development**_)
