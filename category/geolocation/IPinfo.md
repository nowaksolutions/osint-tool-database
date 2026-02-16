# IPinfo

## Category
Geolocation / Network Intelligence

## Purpose
IPinfo provides IP-based geolocation and network intelligence, including ASN, ISP, country, city, and organization data to help attribute infrastructure and understand network ownership.

## Access / Where to Get It
Website: https://ipinfo.io  
API: https://ipinfo.io/developers  

## Input
IP address  
ASN  

## Output
Country  
Region  
City  
Latitude / Longitude  
ISP / Organization  
ASN  
Hostname  
Timezone  

## Strengths
Fast and simple IP enrichment  
Clean API for automation  
Provides ASN and organization context  
Free tier available  
Integrates easily with Maltego  

## Limitations
Free tier has request limits  
Location accuracy varies by ISP  
Does not provide deep historical data  

## Requires Account
No for basic lookups  
Yes for API access  

## Typical Use Case
You receive an IP address from an alert and need quick attribution to determine geographic origin, ISP, and ASN before pivoting into infrastructure analysis.

## Example

Input:  
198.51.100.22  

Output:

Country – United States  
City – Dallas  
ASN – AS12345  
Organization – Example Hosting LLC  

This provides geographic context and hosting attribution.

## Notes
Excellent for quick IP enrichment.  
Often used early in investigations.  
Pairs well with Shodan and SecurityTrails.

## Tags

#geolocation  
#ip  
#asn  
#network  
#osint  
#soc  
