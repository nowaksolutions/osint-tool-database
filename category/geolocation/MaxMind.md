# MaxMind GeoIP

## Category
Geolocation / Network Intelligence

## Purpose
MaxMind GeoIP provides IP geolocation databases used to map IP addresses to physical locations, ISPs, and autonomous systems for attribution and threat analysis.

## Access / Where to Get It
Website: https://www.maxmind.com  
Downloads: https://dev.maxmind.com/geoip  

## Input
IP address  

## Output
Country  
Region  
City  
Latitude / Longitude  
ISP  
ASN  

## Strengths
Industry-standard geolocation database  
Offline database support  
High accuracy at country and region level  
Commonly integrated into SOC tools  
Free GeoLite version available  

## Limitations
City-level accuracy is approximate  
Requires periodic database updates  
Full datasets require paid license  

## Requires Account
Yes to download databases  

## Typical Use Case
You are enriching firewall or SIEM logs and need offline geolocation data to identify where traffic originates from and flag suspicious regions.

## Example

Input:  
203.0.113.45  

Output:

Country – Germany  
City – Frankfurt  
ASN – AS67890  
ISP – Cloud Provider X  

This supports regional threat analysis and alert prioritization.

## Notes
Widely used in SIEM pipelines.  
Excellent for bulk log enrichment.  
Often paired with IPinfo or Shodan for live context.

## Tags

#geolocation  
#geoip  
#network  
#siem  
#osint  
#soc  
