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

| # | Host/Service | Finding | Risk Level | Recommendation |
|---|---------------|---------|------------|-----------------|
| 1 | e.g. Router (192.168.1.1) | e.g. Telnet port open | High | Disable Telnet, use SSH instead |
| 2 | | | | |
| 3 | | | | |
| 4 | | | | |
| 5 | | | | |

*(Fill in 3–5 real findings from your scan. Risk levels: Low / Medium / High / Critical.)*

## Screenshots
Add screenshots of your scan output here, e.g.:

```
![Nmap scan results](screenshots/nmap-scan.png)
![OpenVAS findings](screenshots/openvas-report.png)
```

## What I Learned
A few sentences on what this taught you — e.g. how scan results translate into
real risk, how to prioritise findings, anything that surprised you.

## Disclaimer
This scan was performed only against devices and networks I own or have
explicit permission to test.
