# Shodan

## Category
Domain / Infrastructure Intelligence

## Purpose
Shodan is an internet-wide scanning engine that indexes exposed services, devices, servers, and infrastructure to identify vulnerabilities and attacker surface area.

## Access / Where to Get It
Website: https://www.shodan.io  
API: https://developer.shodan.io  

## Input
IP address  
Domain name  
ASN  
Organization  
Port  

## Output
Open ports  
Running services  
SSL certificates  
Device banners  
Vulnerabilities (CVEs)  
Hosting information  
Geolocation  

## Strengths
Real-time exposure visibility  
Excellent for infrastructure discovery  
Identifies vulnerable services  
Supports automation via API  
Widely used in SOC environments  

## Limitations
Free tier is limited  
Advanced filters require paid plan  
Can surface noisy results  

## Requires Account
Yes for advanced searches and API  

## Typical Use Case
You pivot from a malicious IP to discover exposed services and associated infrastructure to assess attack surface and identify additional targets in the same network.

## Example

Input:  
198.51.100.22  

Output:

Port 22 – OpenSSH  
Port 80 – Apache  
SSL Cert – suspiciousdomain.com  
Organization – Unknown Hosting  

This confirms exposed services and supports infrastructure mapping.

## Notes
Excellent for perimeter discovery.  
Pairs well with Maltego transforms.  
Useful for vulnerability triage and threat hunting.

## Tags

#domain  
#infrastructure  
#exposure  
#shodan  
#threat-hunting  
#osint  
