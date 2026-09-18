# 🕵️ Week 2 Project Module: Reconnaissance & Footprinting Report

## Overview

This project focused on performing reconnaissance and footprinting activities using various open-source intelligence (OSINT) and network enumeration tools. The objective was to gather publicly available information about target organizations, understand their external attack surface, and practice information-gathering techniques commonly used during the early stages of a penetration test.

Throughout this project, I explored domain information, DNS records, web technologies, web application firewalls, hosts, IP addresses, and network mapping using industry-standard tools.

---

# Objectives

- Perform passive and active footprinting.
- Gather publicly available information about target domains.
- Identify DNS records and network infrastructure.
- Detect web technologies and security controls.
- Visualize relationships between discovered assets.
- Practice local network discovery and mapping.

---

# Tools Used

| Tool | Purpose |
|--------|---------|
| Whois | Domain registration information gathering |
| nslookup | DNS record lookup |
| DNSRecon | DNS enumeration |
| WhatWeb | Web technology fingerprinting |
| WAFW00F | Web Application Firewall detection |
| Maltego | OSINT and relationship mapping |
| theHarvester | Email, host, and IP harvesting |
| Zenmap | Network discovery and visualization |

---

# Task 1: Footprinting NetworkWalks.com

## Tools Used

- Whois
- nslookup
- DNSRecon
- WhatWeb
- WAFW00F

## Activities Performed

### Whois Enumeration

Used Whois to gather:

- Domain registration details
- Registrar information
- Domain creation and expiration dates
- Nameserver information

### DNS Enumeration

Used nslookup and DNSRecon to identify:

- A records
- MX records
- NS records
- DNS infrastructure
- Additional DNS-related information

### Technology Fingerprinting

Using WhatWeb, I identified technologies and services running on the target website, including:

- Web server technologies
- Framework indicators
- Security-related headers
- Other publicly visible web technologies

### WAF Detection

Using WAFW00F, I checked whether the website was protected by a Web Application Firewall (WAF).

This activity demonstrated how organizations deploy defensive technologies to protect web applications from malicious traffic and attacks.

---

# Task 2: Maltego Analysis of NetworkWalks

## Tool Used

- Maltego

## Activities Performed

A Maltego graph was created to visualize relationships associated with the NetworkWalks domain.

The graph helped identify:

- Domain relationships
- DNS infrastructure
- Associated entities
- Publicly available information linked to the target

## Learning Outcome

Maltego demonstrated how information from multiple sources can be correlated and visualized to build a comprehensive view of a target's online presence.

---

# Task 3: Information Gathering on Microsoft.com

## Tool Used

- theHarvester

## Commands Used

```bash
theHarvester -d microsoft.com -l 1000 -b baidu
```

```bash
theHarvester -d microsoft.com -l 50 -b all
```

### Command Explanation

| Option | Description |
|----------|-------------|
| `-d microsoft.com` | Target domain |
| `-l 1000` | Limit results to 1000 entries |
| `-l 50` | Limit results to 50 entries |
| `-b baidu` | Use Baidu as the data source |
| `-b all` | Query all available data sources |


## Activities Performed

theHarvester was used against Microsoft.com to collect publicly available information including:

- Email addresses
- Hostnames
- IP addresses
- Additional publicly accessible assets

Several hosts and IP addresses associated with the domain were successfully identified.

The exercise demonstrated how attackers and security professionals can gather valuable reconnaissance information from public sources without directly interacting with the target's infrastructure.

## Risk Considerations

Information discovered through harvesting may contribute to:

- User enumeration
- Phishing attacks
- Social engineering
- Attack surface mapping
- Further reconnaissance activities

---

# Task 4: Local Network Mapping

## Tool Used

- Zenmap

## Activities Performed

Zenmap was used to discover and map devices on the local network.

The scan helped identify:

- Active hosts
- IP addresses
- Open services
- Network topology information

## Learning Outcome

This activity provided practical experience in network discovery and demonstrated how network administrators and security professionals can identify assets connected to a network.

---

# Key Skills Developed

- Open Source Intelligence (OSINT)
- Domain Footprinting
- DNS Enumeration
- Technology Fingerprinting
- WAF Detection
- Asset Discovery
- Network Reconnaissance
- Information Gathering
- Host Enumeration
- Attack Surface Mapping
- Network Visualization

---

# Key Takeaways

- Publicly available information can reveal significant details about an organization.
- DNS records provide valuable insights into network infrastructure.
- Technology fingerprinting helps identify potential attack vectors.
- Web Application Firewalls play an important role in protecting web applications.
- Maltego enables efficient visualization of relationships between assets.
- theHarvester can uncover hosts, IP addresses, and email addresses from public sources.
- Zenmap provides an effective way to discover and visualize network assets.
- Reconnaissance is a critical first phase of any penetration testing engagement.

---

# Project Summary

During this Week 2 project module, I performed reconnaissance and footprinting activities using multiple OSINT and network enumeration tools. I gathered information from NetworkWalks.com and Microsoft.com, visualized relationships using Maltego, harvested public information using theHarvester, and mapped local network assets using Zenmap.

This project strengthened my understanding of information gathering methodologies and provided hands-on experience with tools commonly used by penetration testers, security analysts, and red team professionals.

---

## Status

✅ Completed

## Module

Week 2 Project Module: Reconnaissance & Footprinting

## Platform

Network Walks Cybersecurity Internship

---

*Report created as part of my cybersecurity learning journey and practical reconnaissance training.*
