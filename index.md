---
layout: default
---

# Key Projects

## Project 1: Home Network SIEM Setup

I built a secure home network with Access Control Lists (ACLs) and integrated it with a Security Information and Event Management (SIEM) system using Security Onion. This setup involved configuring firewalls and creating custom detection rules to monitor and analyze real-time network traffic, helping to detect and respond to potential threats.

## Project 2: ELK Stack Deployment

Successfully configured and deployed the ELK Stack on a Linux Virtual Machine (VM). This included setting up Elasticsearch, Logstash, and Kibana for log collection, processing, and visualization. The system helps in analyzing security logs from various sources and provides actionable insights.

## Project 3: Cybersecurity Lab Setup (Ongoing)

Currently working on a cybersecurity lab to simulate real-world scenarios involving penetration testing, threat detection, and mitigation using tools such as Nessus, Metasploit, and Kali Linux. The goal is to sharpen my skills in vulnerability scanning and ethical hacking as I prepare for the OSCP and Pentest+ certifications.

# Experiences

With nearly 15 years of experience in Information Technology, I’ve transitioned from IT infrastructure management into the cybersecurity space. My expertise includes setting up SIEM systems, deploying security tools like Nessus, Metasploit, and Kali Linux, and configuring monitoring solutions using the ELK Stack. My experience spans:

- Incident response and real-time monitoring of networks using Security Onion.
- Hands-on experience with PowerShell for automating tasks and security analysis.
- Ongoing development of skills in Python scripting for security automation.

## Certifications & Training
- **Comptia A+ Training** (Completed)
- **CompTIA Security+** (Completed)
- **OSCP** (Planned)
- **Pentest+/CEH** (Planned)
- **Certified Threat Intelligence Analyst (CTIA)** (Planned)

## Roadmap

> "When something is important enough, you do it even if the odds are not in your favor." — Elon Musk

My professional journey is focused on becoming a SOC Analyst and later advancing into a cyber threat intelligence role. I'm actively building skills and planning to take key certifications such as OSCP, Pentest+, and CISSP to bolster my technical expertise.

```js
// Example of code block to automate log analysis in ELK using Python
import requests
import json

def get_logs():
  response = requests.get('http://localhost:9200/_search')
  logs = json.loads(response.text)
  for log in logs['hits']['hits']:
      print(log['_source'])

get_logs()
