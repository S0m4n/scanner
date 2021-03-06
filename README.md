# Evolution:
It is quite a fuss for a pentester to perform binge-tool-scanning (running security scanning tools one after the other) sans automation. Unless you are a pro at automating stuff, it is a herculean task to perform binge-scan for each and every engagement. The ultimate goal of this program is to solve this problem through automation; viz. running multiple scanning tools to discover vulnerabilities, effectively judge false-positives, collectively correlate results and saves precious time; all these under one roof.
# Features
one-step installation.

executes a multitude of security scanning tools, does other custom coded checks and prints the results spontaneously.

some of the tools include nmap, dnsrecon, wafw00f, uniscan, sslyze, fierce, lbd, theharvester, amass, nikto etc executes under one entity.

saves a lot of time, indeed a lot time!.

checks for same vulnerabilities with multiple tools to help you zero-in on false positives effectively.

extremely light-weight and not process intensive.

legends to help you understand which tests may take longer time, so you can Ctrl+C to skip if needed.

association with OWASP Top 10 & CWE 25 on the list of vulnerabilities discovered. (under development)

critical, high, medium, low and informational classification of vulnerabilities.

vulnerability definitions guides you what the vulnerability actually is and the threat it can pose.

remediation tells you how to plug/fix the found vulnerability.

executive summary gives you an overall context of the scan performed with critical, high, low and informational issues discovered.

artificial intelligence to deploy tools automatically depending upon the issues found. for eg; automates the launch of wpscan and plecost tools when a wordpress installation is found. (under development)

detailed comprehensive report in a portable document format (*.pdf) with complete details of the scans and tools used. (under development)

on the run metasploit auxilliary modules to discover more vulnerabilities. (under development)

# FYI:
my tool is  under development, works and currently supports 80 vulnerability tests.

# Vulnerability Checks
heavy_check_mark DNS/HTTP Load Balancers & Web Application Firewalls.

heavy_check_mark Checks for Joomla, WordPress and Drupal

heavy_check_mark SSL related Vulnerabilities (HEARTBLEED, FREAK, POODLE, CCS Injection, LOGJAM, OCSP Stapling).

heavy_check_mark Commonly Opened Ports.

heavy_check_mark DNS Zone Transfers using multiple tools (Fierce, DNSWalk, DNSRecon, DNSEnum).

heavy_check_mark Sub-Domains Brute Forcing (DNSMap, amass, nikto)

heavy_check_mark Open Directory/File Brute Forcing.

heavy_check_mark Shallow XSS, SQLi and BSQLi Banners.

heavy_check_mark Slow-Loris DoS Attack, LFI (Local File Inclusion), RFI (Remote File Inclusion) & RCE (Remote Code Execution).

& more coming up..

# Requirements
Python 3

Kali OS (Preferred, as it is shipped with almost all the tools)
