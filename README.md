# Network-Analysis: Local Network Security Assessment & Vulnerability Reporting

This project conducts a comprehensive security assessment of a local network using industry-standard tools like Nmap, Nikto, Zenmap, Wireshark, and Netcat. The goal is to identify vulnerabilities, map network topology, and provide actionable recommendations to enhance security posture.

---

## 🛠 Tools & Techniques Utilized

| Tool / Technique             | Purpose / Security Functionality                                         |
|------------------------------|---------------------------------------------------------------------------|
| **Nmap**                     | Network discovery, port scanning, OS fingerprinting                       |
| **Zenmap**                   | GUI frontend for Nmap, visual network mapping                             |
| **Nikto**                    | Web server scanning for vulnerabilities                                   |
| **Wireshark**                | Deep packet inspection, traffic analysis                                  |
| **Netcat**                   | Banner grabbing, port scanning, network diagnostics                       |
| **ifconfig**                 | Network interface configuration and monitoring                            |

---

## 🎯 Assessment Objectives & Key Findings

| Objective                                  | Methodology & Tools Employed                                      | Outcome / Recommendations                                           |
|--------------------------------------------|-------------------------------------------------------------------|----------------------------------------------------------------------|
| **Network Discovery**                      | Utilized `ifconfig` and `nmap` for host and port identification   | Mapped active devices and open ports                                 |
| **Vulnerability Scanning**                 | Deployed `nikto` and `nmap --script vuln`              | Identified outdated services, missing patches, and misconfigurations |
| **Traffic Analysis**                       | Analyzed traffic patterns using `wireshark`                        | Detected unencrypted protocols and potential data leaks              |
| **Service Enumeration**                    | Employed `netcat` for banner grabbing                              | Discovered services with known vulnerabilities                        |
| **Reporting & Documentation**              | Compiled findings into a comprehensive PDF report                  | Provided actionable steps for remediation and hardening               |
