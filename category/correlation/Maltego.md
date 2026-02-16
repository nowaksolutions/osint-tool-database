# VirusTotal

## Category
Malware Intelligence / Threat Reputation

## Purpose
Analyzes files, IP addresses, domains, and URLs using multiple antivirus engines and threat intelligence sources to identify malicious indicators.

## Access / Where to Get It
Web Interface: https://www.virustotal.com  
API Access: https://developers.virustotal.com  

## Input
File hash (MD5 / SHA1 / SHA256)  
IP address  
Domain name  
URL  

## Output
Detection results from multiple security vendors  
Malware classification  
Threat reputation score  
Associated domains and IPs  
Historical analysis data  

## Strengths
Aggregates results from dozens of AV engines  
Excellent for IOC enrichment  
Fast reputation checking  
Historical scan data available  
API supports automation and SOC pipelines  

## Limitations
Free tier has strict rate limits  
Does not perform live malware detonation (static unless paid)  
False positives may occur  
Advanced features require premium subscription  

## Requires Account
No for basic searches  
Yes for API access and automation  

## Typical Use Case
You receive a suspicious file hash or domain from an alert and need rapid validation across multiple security engines to determine if it’s malicious before escalating or isolating systems.

## Example

Input:  
d41d8cd98f00b204e9800998ecf8427e  

Output:

Microsoft – Trojan:Win32  
Kaspersky – HEUR:Backdoor  
CrowdStrike – Suspicious  
Community Score: Malicious  

This confirms the artifact is malicious and supports incident containment and IOC pivoting.

## Notes
Common first-stop tool for SOC analysts.  
Pairs well with Maltego transforms for infrastructure mapping.  
Useful for confirming alerts before initiating response actions.  
Best used alongside sandboxing and EDR telemetry.

## Tags

#malware  
#ioc  
#threat-intel  
#passive  
#api  
#soc  
