# Web Application Penetration Testing

## Introduction

This repository provides a comprehensive guide to performing web application penetration testing, covering various stages from information gathering to exploiting vulnerabilities. Whether you're a cybersecurity enthusiast or a professional, this guide aims to equip you with the necessary tools and techniques to assess the security of web applications effectively.

## Table of Contents

1. [Information Gathering: Mapping the Application and Attack Surface](#information-gathering-mapping-the-application-and-attack-surface)
    1.1 [Scanning and Search Tools](#scanning-and-search-tools)
    1.2 [Web Application Firewall Fingerprinting](#web-application-firewall-fingerprinting)
    1.3 [Discovering Hidden Directories](#discovering-hidden-directories)
    1.4 [Discovering Sub-Domains](#discovering-sub-domains)
2. [Understanding Exploits](#understanding-exploits)
    2.1 [CVE Tools](#cve-tools)
3. [Exploiting OWASP Vulnerabilities](#exploiting-owasp-vulnerabilities)
    3.1 [Vulnerabilities Scanners](#vulnerabilities-scanners)
    3.2 [Penetration Test Tools](#penetration-test-tools)

---

## Information Gathering: Mapping the Application and Attack Surface

### Scanning and Search Tools

- [Nessus](https://www.tenable.com/): A comprehensive vulnerability scanner used to detect potential vulnerabilities in the network and systems.
- [Nmap](https://nmap.org/): A network discovery and security auditing tool used for network inventory, managing service upgrade schedules, and monitoring host or service uptime.
- [Shodan](https://www.shodan.io/): A search engine for discovering Internet-connected devices and systems, often used for network reconnaissance and security research.
- [FOFA](https://en.fofa.info/): A search engine for discovering Internet-connected devices and services, providing detailed information about them.
- [Censys](https://search.censys.io/): Another search engine focused on providing up-to-date information about Internet infrastructure.
- [DNSdumpster](https://dnsdumpster.com/): A tool used for DNS reconnaissance, gathering information about a target domain such as DNS records, subdomains, and associated IP addresses.
- [Hunter.io](https://hunter.io/email-finder): A tool used for gathering email addresses associated with a particular domain.

### Web Application Firewall Fingerprinting

- [Wafw00f](https://www.kali.org/tools/wafw00f/): A tool to identify and fingerprint Web Application Firewall (WAF) products protecting a website.

### Discovering Hidden Directories

- [Gobuster](https://www.kali.org/tools/gobuster/): A tool used to brute-force URIs (directories and files) in web sites and DNS subdomains.
- [Dirbuster](https://www.kali.org/tools/dirbuster/): A multi-threaded java application designed to brute force directories and files names on web/application servers.

### Discovering Sub-Domains

- [Sublist3r](https://www.kali.org/tools/sublist3r/): A tool designed to enumerate subdomains of websites using OSINT.

---

## Understanding Exploits

### CVE Tools

- [Exploit-db](https://www.exploit-db.com/searchsploit): A non-profit project provided as a public service by Offensive Security to assist with security vulnerability research and the CVE process.

---

## Exploiting OWASP Vulnerabilities

### Vulnerabilities Scanners

- [Vega Vulnerability Scanner](https://subgraph.com/vega/): An open-source web security scanner and web security testing platform.
- [OWASP ZAP (Zed Attack Proxy)](https://www.zaproxy.org/): An open-source web application security scanner.
- [Nessus](https://www.tenable.com/products/nessus): Reiterated from section 1.1 for its dual role in both reconnaissance and vulnerability exploitation phases.

### Penetration Test Tools

- [Burp Suite](https://portswigger.net/burp/communitydownload): An integrated platform for performing security testing of web applications.

---

## Contribution

Contributions are welcome! If you have additional tools or resources that could benefit this guide, feel free to open a pull request.
