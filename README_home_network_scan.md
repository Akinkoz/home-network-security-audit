# Home Network Vulnerability Assessment

## Overview
A short paragraph explaining what this project is and why you did it.
Example: "This project involved scanning my home network to identify open ports,
running services, and potential vulnerabilities, then documenting findings and
remediation recommendations — as practice for real-world vulnerability assessment work."

## Objectives
- Enumerate live hosts and open ports on the network
- Identify running services and their versions
- Run a vulnerability scan against key hosts
- Document findings with risk ratings and remediation steps

## Tools Used
- **Nmap** — host discovery, port scanning, service/version detection
- **OpenVAS (Greenbone)** / **Nessus Essentials** — vulnerability scanning
- (Add anything else you used — e.g. Wireshark, a VM, specific OS)

## Methodology
1. Ran `nmap -sV -O 192.168.1.0/24` to discover live hosts and identify open ports, services, and versions.
2. Selected the most interesting hosts (router, laptop, IoT devices) for deeper scanning.
3. Ran OpenVAS/Nessus against those hosts to identify known vulnerabilities.
4. Reviewed and prioritised findings by severity.

> Replace the command above with whatever you actually ran, including any flags you used.

## Findings

<img width="1269" height="579" alt="d1b50bfa-efb5-40bb-aec6-3002b9ffd4bf" src="https://github.com/user-attachments/assets/e5af24f7-aa1e-476c-b576-f54e9ad46cfc" />



## Screenshots
Add screenshots of your scan output here, e.g.:

```
```
<img width="1269" height="952" alt="image" src="https://github.com/user-attachments/assets/39ea0d22-a3a9-4470-98ea-75c6eb110930" />
<img width="1269" height="579" alt="d1b50bfa-efb5-40bb-aec6-3002b9ffd4bf" src="https://github.com/user-attachments/assets/e5af24f7-aa1e-476c-b576-f54e9ad46cfc" />


## What I Learned
A few sentences on what this taught you — e.g. how scan results translate into
real risk, how to prioritise findings, anything that surprised you.

## Disclaimer
This scan was performed only against devices and networks I own or have
explicit permission to test.
