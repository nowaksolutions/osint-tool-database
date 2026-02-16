# Maltego

## Category
OSINT / Link Analysis / Threat Intelligence Platform

## Purpose
Maltego is a link analysis and data mining tool used to gather, correlate, and visualize relationships between people, domains, IP addresses, companies, infrastructure, and other entities during investigations.

## Access / Where to Get It
Website: https://www.maltego.com  
Download: https://www.maltego.com/downloads/  

## Input
Domain name  
IP address  
Email address  
Username  
Person name  
Company name  
URL  
Hash  

## Output
Entity relationship graphs  
Linked infrastructure mapping  
WHOIS data  
DNS records  
Social media associations  
Breach correlations  
Technology fingerprinting  
Visual investigation reports  

## Strengths
Powerful visual link analysis  
Supports automation via transforms  
Integrates with many OSINT data sources  
Excellent for infrastructure pivoting  
Used in SOC, threat hunting, fraud, and investigations  
Supports custom transform development  

## Limitations
Many data sources require paid subscriptions  
Can become noisy without proper scoping  
Requires investigation planning to avoid data overload  
API limits apply depending on data provider  

## Requires Account
Yes (Community Edition available, but limited)  
Full functionality requires paid license  

## Typical Use Case
You are investigating a suspicious domain involved in phishing. You use Maltego to pivot from the domain to its IP address, then to other hosted domains, registrant information, and related email addresses to uncover attacker infrastructure.

## Example

Input:  
example-phish.com  

Output:

IP Address – 192.0.2.10  
ASN – Hosting Provider X  
Registrant Email – attacker@email.com  
Additional Domains – fake-login.net, secure-update.org  

This reveals shared infrastructure and potential campaign clustering.

## Notes
Widely used in OSINT and cyber investigations.  
Best used with a defined investigative objective.  
Supports custom transforms for automation and enrichment.  
Often paired with VirusTotal, Shodan, and HIBP for enrichment workflows.  

## Tags

#osint  
#link-analysis  
#maltego  
#threat-intel  
#investigation  
#soc  
