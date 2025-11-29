# nmap-recon-project
A hands-on project demonstrating basic reconnaissance using Nmap. Includes scans, explanations, and findings.
 Nmap Recon Project
This project demonstrates basic reconnaissance and scanning techniques using Nmap.
It includes different scan types, explanations, and sample outputs.
Tools Used
Kali Linux
Nmap
Terminal
 Scan 1: Basic Ping Scan
nmap -sn 192.168.1.0/24
Purpose: Discover live hosts on the network.

 Scan 2: Basic Port Scan
nmap 192.168.1.10
Purpose: Identify open ports and services.

 Scan 3: Service & Version Detection
nmap -sV 192.168.1.10
Purpose: See what services and versions are running.

 Scan 4: Aggressive Scan
nmap -A 192.168.1.10
Purpose: OS detection, scripts, traceroute.

 Summary
This repo is part of my cybersecurity learning journey focused on:
Network reconnaissance
Port scanning
Service enumeration
Documenting findings
More advanced scans and write-ups coming soon.
