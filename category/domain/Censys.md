# Censys

## Category
Domain / Infrastructure Intelligence

## Purpose
Censys continuously scans the internet to discover hosts, services, certificates, and infrastructure, enabling analysts to map exposed assets and attacker environments.

## Access / Where to Get It
Website: https://censys.io  
API: https://search.censys.io/api  

## Input
IP address  
Domain  
ASN  
Organization  
Certificate fingerprint  

## Output
Open ports  
Running services  
TLS certificates  
Hosting provider  
Associated infrastructure  
Geolocation  

## Strengths
Excellent certificate-based pivoting  
Clean search syntax  
Strong asset discovery  
API available  
Great for infrastructure attribution  

## Limitations
Free tier is limited  
Advanced queries require paid plan  
No built-in visualization  

## Requires Account
Yes  

## Typical Use Case
You pivot from a suspicious domain to its TLS certificate, then use that certificate to discover additional attacker-controlled infrastructure.

## Example

Input:  
example-phish.com  

Output:

IP – 198.51.100.22  
TLS Cert CN – secure-login.net  
Additional Hosts – update-bank.org  

This reveals shared certificates and campaign infrastructure.

## Notes
Extremely powerful when combined with Maltego.  
Best used for certificate clustering.  
Excellent alternative to Shodan for HTTPS assets.

## Tags

#domain  
#infrastructure  
#certificates  
#pivoting  
#osint  
#soc  
