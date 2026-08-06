# Network Security Engineer Roadmap 2026

A free, step-by-step roadmap to go from beginner to job-ready Network Security Engineer. Every resource linked here is free — no paid courses, no gated content.

---

## Why This Roadmap

Network security is the backbone of cybersecurity. Every cloud service, every app, every database sits on a network. If you understand how networks work and how to protect them, you'll always have job opportunities.

This roadmap takes you from zero networking knowledge to being able to design, monitor, and defend enterprise networks. It's structured in 6 phases over 12 months.

---

## Phase 1: Networking Foundations (Months 1-2)

Before you can secure a network, you need to understand how it works.

### What to Learn
1. OSI model and TCP/IP stack
2. IP addressing, subnets, and CIDR
3. DNS, DHCP, and ARP
4. TCP vs UDP — when and why
5. Routing and switching basics
6. NAT and port forwarding

### Free Courses
1. **Cisco Networking Essentials** — Free intro course from Cisco
   https://www.netacad.com/cisco-networking-academy-courses-programming/networking-essentials
2. **Professor Messer Network+ Course** — Full N10-009 video course, completely free
   https://www.professormesser.com/network-plus/n10-009/n10-009-training-course/
3. **Computer Networking: Principles, Protocols, and Practice** — Free textbook (CNLP3)
   https://www.computer-networking.info/
4. **Khan Academy: Internet and Computers** — Short and visual
   https://www.khanacademy.org/computing/code-org/computers-and-internet
5. **PowerCert Animated Videos** — Great visual explanations of networking concepts
   https://www.youtube.com/@PowerCertAnimatedVideos

### Hands-On
1. Install Wireshark and capture traffic on your own network
2. Set up two VMs in VirtualBox and ping between them
3. Build a small lab network in GNS3 (free network simulator)
   https://www.gns3.com/
4. Practice subnetting with this free tool
   https://subnettingpractice.com/

---

## Phase 2: Security Fundamentals (Months 3-4)

Now that you understand networks, learn the security concepts that apply to them.

### What to Learn
1. CIA triad (confidentiality, integrity, availability)
2. AAA framework (authentication, authorization, accounting)
3. Cryptography basics — symmetric vs asymmetric, hashing, PKI
4. Common attacks: MITM, DDoS, ARP spoofing, DNS poisoning, VLAN hopping
5. Defense in depth principle
6. Zero Trust architecture basics

### Free Courses
1. **Professor Messer Security+ Course** — Full SY0-701 video course
   https://www.professormesser.com/security-plus/sy0-701/sy0-701-training-course/
2. **Cybrary: CompTIA Security+** — Free course with labs
   https://www.cybrary.it/course/comptia-security-plus
3. **TryHackMe: Pre-Security Path** — Free interactive modules
   https://tryhackme.com/path/outline/presecurity
4. **Cisco Cyber Threat Management** — Free course
   https://www.netacad.com/cisco-networking-academy-courses-programming/introduction-cybersecurity
5. **NIST Cybersecurity Framework Documentation** — The actual framework docs
   https://www.nist.gov/cyberframework

### Hands-On
1. Set up pfSense firewall in VirtualBox (free firewall distribution)
   https://www.pfsense.org/
2. Perform a MITM attack in your lab using Ettercap (educational, your own network only)
3. Practice DNS spoofing in your isolated lab

---

## Phase 3: Network Security Tools (Months 5-6)

Learn the tools that network security engineers use every day.

### Core Tools to Master

1. **Wireshark** — Packet capture and analysis
   - Free download: https://www.wireshark.org/
   - Free training: https://www.wireshark.org/docs/wsug_html_chunked/
   - Practice: https://www.malware-traffic-analysis.net/ (free pcap files)

2. **Nmap** — Network discovery and security auditing
   - Free download: https://nmap.org/
   - Free book (Nmap Network Scanning): https://nmap.org/book/
   - Nmap tutorial series: https://nmap.org/tutorials/

3. **Suricata** — Open-source IDS/IPS
   - Free download: https://suricata.io/
   - Documentation: https://docs.suricata.io/
   - Free ET Open ruleset: https://rules.emergingthreats.net/

4. **Zeek** — Network security monitoring
   - Free download: https://zeek.org/
   - Documentation: https://docs.zeek.org/
   - Zeek training: https://github.com/zeek/zeek-training

5. **Snort** — Intrusion detection and prevention
   - Free download: https://www.snort.org/
   - Documentation: https://www.snort.org/documents

6. **OpenVAS / Greenbone** — Vulnerability scanning
   - Free download: https://www.openvas.org/

### Other Important Tools
1. **Kali Linux** — Security testing OS (free)
   https://www.kali.org/
2. **Security Onion** — Linux distro for threat hunting and network security monitoring
   https://securityonionsolutions.com/
3. **Elastic Stack (ELK)** — Log analysis and SIEM
   https://www.elastic.co/
4. **pfSense / OPNsense** — Open-source firewalls
   https://www.pfsense.org/ | https://opnsense.org/

---

## Phase 4: Network Architecture and Defense (Months 7-8)

Design and defend enterprise networks.

### What to Learn
1. Network segmentation and VLAN security
2. Firewall design — DMZ, zones, rules
3. VPN technologies — IPsec, SSL/TLS VPN, WireGuard
4. Proxy servers and reverse proxies
5. Load balancers and their security implications
6. Network Access Control (NAC)
7. SD-WAN security
8. Cloud networking — VPCs, security groups, NSGs
9. Microsegmentation in modern data centers

### Free Resources
1. **Cisco CCNA Free Training** — Jeremy's IT Lab (full free course)
   https://www.youtube.com/playlist?list=PLxb9m9P5crAR-N3mQbQT4P0NrTuBPh7zR
2. **AWS Networking Basics** — Free digital training
   https://aws.amazon.com/training/learn-about/networking/
3. **Azure Network Fundamentals** — Free learning path
   https://learn.microsoft.com/en-us/training/paths/azure-networking-fundamentals/
4. **Cloudflare Learning Center** — Free guides on DNS, DDoS, zero trust
   https://www.cloudflare.com/learning/
5. **Zero Trust Architecture (NIST SP 800-207)** — The official document
   https://csrc.nist.gov/publications/detail/sp/800-207/final

### Hands-On Projects
1. Build a segmented network with pfSense (LAN, DMZ, guest)
2. Set up an IPsec VPN between two VMs
3. Configure Suricata on your pfSense box and write custom rules
4. Build a basic SIEM with ELK Stack and feed it network logs
5. Set up a honeypot using Cowrie (free SSH honeypot)
   https://github.com/cowrie/cowrie

---

## Phase 5: Monitoring, Detection, and Incident Response (Months 9-10)

Become the person who finds and stops attacks.

### What to Learn
1. Network traffic analysis (NTA)
2. Log collection and correlation
3. SIEM concepts and implementation
4. Threat hunting on the network
5. Incident response methodology (NIST SP 800-61)
6. Network forensics — pcap analysis, timeline reconstruction
7. MITRE ATT&CK framework for network detection
8. Indicators of compromise (IOCs) and how to use them

### Free Resources
1. **TryHackMe: SOC Level 1 Path** — Free interactive training
   https://tryhackme.com/path/outline/soc-level-1
2. **MITRE ATT&CK Framework** — The full matrix and documentation
   https://attack.mitre.org/
3. **NIST Incident Response Guide (SP 800-61 Rev 2)**
   https://csrc.nist.gov/publications/detail/sp/800-61/rev-2/final
4. **Malware Traffic Analysis** — Free pcap files with solutions
   https://www.malware-traffic-analysis.net/
5. **SANS CyberESI Threat Hunting Materials** — Free papers
   https://www.sans.org/whitepapers/
6. **CyberChef** — Free tool for data transformation and analysis
   https://gchq.github.io/CyberChef/
7. **RITA (Real Intelligence Threat Analytics)** — Free threat hunting tool
   https://github.com/activecm/rita

### Hands-On Projects
1. Download pcap files from malware-traffic-analysis.net and analyze them in Wireshark
2. Build a complete SIEM pipeline: Zeek logs → Filebeat → Elasticsearch → Kibana
3. Write Suricata rules to detect specific attack patterns from MITRE ATT&CK
4. Deploy Cowrie honeypot and analyze the captured attacks
5. Set up Security Onion in a VM and practice network forensics

---

## Phase 6: Advanced Topics and Career Launch (Months 11-12)

Specialize and land the job.

### What to Learn
1. Cloud network security (AWS, Azure, GCP)
2. Container and Kubernetes networking security
3. Automation — Python for network security
4. Infrastructure as Code — Terraform for secure network provisioning
5. Wireless security — WPA3, rogue AP detection
6. IoT network security
7. SASE and secure access service edge

### Free Resources
1. **Python for Network Engineers** — Free course by Kirk Byers
   https://pynaut.com/blog/free-python-course/
2. **Kubernetes Networking** — Free documentation
   https://kubernetes.io/docs/concepts/services-networking/
3. **Terraform Tutorials** — Free interactive
   https://developer.hashicorp.com/terraform/tutorials
4. **AWS VPC Security Best Practices**
   https://docs.aws.amazon.com/vpc/latest/userguide/vpc-security-best-practices.html
5. **OWASP Top 10 for Cloud** — Free guide
   https://owasp.org/www-project-top-10-for-cloud/

---

## Certifications (Free Study Materials Listed Above)

1. **CompTIA Network+** — Networking fundamentals (Professor Messer videos are free)
2. **CompTIA Security+** — Security basics (Professor Messer videos are free)
3. **Cisco CCNA** — Networking deep dive (Jeremy's IT Lab is free)
4. **Cisco CyberOps Associate** — Security operations focus
5. **Fortinet NSE 4** — Firewall-specific
6. **Practical Network Defense (PND)** — Practical certification

---

## Portfolio Projects (Build These as You Learn)

1. **Home Lab Network** — Build a segmented network with pfSense, a DMZ, and logging
2. **Network Scanner** — Python script that scans subnets and reports findings
3. **SIEM Dashboard** — ELK Stack with network log ingestion and alerts
4. **Suricata Rule Pack** — Custom detection rules for common attacks
5. **Traffic Analysis Report** — Download pcaps, analyze attacks, write a report
6. **Honeypot Deployment** — Deploy Cowrie, collect data, write a threat report
7. **Zero Trust Proof of Concept** — Implement basic ZT principles in a lab
8. **VPN Setup Guide** — Document IPsec/WireGuard VPN setup with diagrams
9. **Network Hardening Checklist** — Create and publish a hardening guide
10. **Automated Monitoring Script** — Python script that checks firewall rules and alerts

---

## Key Tools Summary

| Tool | Purpose | Cost |
|------|---------|------|
| Wireshark | Packet analysis | Free |
| Nmap | Network scanning | Free |
| Suricata | IDS/IPS | Free |
| Zeek | Network monitoring | Free |
| Snort | Intrusion detection | Free |
| pfSense | Firewall | Free |
| ELK Stack | SIEM and log analysis | Free |
| GNS3 | Network simulation | Free |
| VirtualBox | Virtual machines | Free |
| Kali Linux | Security testing OS | Free |
| Security Onion | Full NSM platform | Free |
| CyberChef | Data analysis | Free |

---

## Communities to Join

1. **r/AskNetsec** — Reddit network security community
   https://www.reddit.com/r/AskNetsec/
2. **r/networking** — Reddit networking community
   https://www.reddit.com/r/networking/
3. **OWASP Slack** — Free Slack community
   https://owasp.org/slack/
4. **CIS Community** — Center for Internet Security
   https://www.cisecurity.org/
5. **SANS Community** — Free webcasts and papers
   https://www.sans.org/community/

---

## How to Use This Roadmap

1. Don't skip phases — each builds on the last
2. Do every hands-on project, don't just watch videos
3. Document what you learn (blog, GitHub, notes)
4. Join communities and ask questions
5. Build your lab early — you can do most projects with just VirtualBox and free tools
6. Spend at least 50% of your time on hands-on practice, not just theory
7. Consistency beats intensity — 1 hour daily is better than 7 hours on Sunday

---

## License

MIT — Free to use, share, and modify. No restrictions.

---

*Created by BlackPanda999 — more free roadmaps and security projects at https://github.com/BlackPanda999*

<!-- roadmap v1.0 -->
