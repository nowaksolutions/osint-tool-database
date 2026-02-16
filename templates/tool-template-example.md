# ShadowTrace

## Category
Domain & Infrastructure Recon

## Purpose
Collects domain metadata, historical DNS records, and associated IP infrastructure for reconnaissance and threat analysis.

## Input
Domain name (example.com)  
IP address

## Output
WHOIS data  
DNS history  
Associated IP ranges  
Hosting provider  
Geolocation

## Strengths
Fast passive reconnaissance  
Good visualization of infrastructure relationships  
No scanning required  
Helpful for early investigation stages  

## Limitations
Free tier is limited  
Some data delayed by 24–48 hours  
Does not provide breach or people data  

## Requires Account
Yes (free tier available)

## Typical Use Case
You receive a suspicious domain from a phishing email and want to quickly identify hosting provider, IP ranges, and related infrastructure before pivoting deeper.

## Example

Input: evil-domain.com

Output: 
Hosting: Vultr
IP: 192.168.1.22
ASN: AS20473
Country: Netherlands
Related domains: evil-login.com, secure-portal.net

## Notes

Best used early in investigations.  
Pair with username and email OSINT tools after domain discovery.  
Always manually verify results before attribution.

## Tags

#domains  
#passive  
#recon  
#free-tier  
#infrastructure  
