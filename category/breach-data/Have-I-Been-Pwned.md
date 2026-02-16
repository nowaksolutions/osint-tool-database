# Have I Been Pwned (HIBP)

## Category
Breach Data / Credential Exposure

## Purpose
Checks whether an email address, username, or password has appeared in known data breaches and paste dumps.

## Access / Where to Get It
Web Interface: https://haveibeenpwned.com  
API Access: https://haveibeenpwned.com/API/v3  

Provided by :contentReference[oaicite:0]{index=0}

## Input
Email address  
Username  
Password (via k-Anonymity hash method)

## Output
List of breaches associated with the input, including breach name, date, exposed data types, and breach description.

## Strengths
Authoritative and widely trusted data source  
Large and frequently updated breach database  
Passive reconnaissance  
Clear breach context and metadata  
API available for automation  

## Limitations
Full details require paid API access  
Does not prove account ownership  
Some breaches only show partial exposure  
Password checks do not reveal exact password matches  

## Requires Account
No for basic searches  
Yes for API access

## Typical Use Case
You are investigating a phishing incident or compromised account and need to determine whether an email address or username has been exposed in previous breaches to assess credential reuse risk.

## Example

Input: user@example.com

Output:

Adobe – Email addresses, password hints

LinkedIn – Emails, hashed passwords

Collection #1 – Emails, passwords

This confirms prior exposure and supports credential-reset and monitoring actions.

## Notes
One of the first tools used during account compromise investigations.  
Excellent for assessing credential stuffing risk.  
API access makes this tool valuable for SOC automation and alert enrichment.  
Always combine with username and domain OSINT for context.

## Tags

#breach-data  
#credentials  
#passive  
#free  
#api  
#soc  
