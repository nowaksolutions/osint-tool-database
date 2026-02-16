# MarineTraffic

## Category
Geolocation / Physical Asset Intelligence

## Purpose
MarineTraffic provides real-time and historical vessel tracking using AIS (Automatic Identification System) data, allowing analysts to monitor ship movements, identify ownership patterns, and correlate maritime activity with geographic locations or events.

It is commonly used for port monitoring, logistics analysis, and physical-world attribution.

## Access / Where to Get It
Website: https://www.marinetraffic.com  
Live Map: https://www.marinetraffic.com/en/ais/home  

## Input
Vessel name  
IMO number  
MMSI  
Geographic area  
Port  

## Output
Real-time vessel position  
Speed and heading  
Voyage history  
Port calls  
Ship type  
Flag state  
Ownership information  

## Strengths
Global AIS coverage  
Historical playback available  
Detailed vessel metadata  
Visual maritime mapping  
API available for automation  

## Limitations
Advanced history requires paid access  
AIS can be spoofed or disabled  
Coverage depends on receiver density  
Some vessel data may be obfuscated  

## Requires Account
No for basic tracking  
Yes for historical data and API access  

## Typical Use Case
You are investigating activity near a port or coastal facility and want to determine whether unusual shipping patterns or vessel arrivals occurred during a specific timeframe.

## Example

Input:  
Port – Savannah, GA  

Output:

Vessel – CMA CGM Example  
Type – Container Ship  
Flag – Panama  
Arrival – 02:14 UTC  
Previous Port – Rotterdam  

This provides maritime movement context and supports physical attribution.

## Notes
Useful for adding maritime awareness to investigations.  
Commonly used by OSINT analysts and journalists.  
Can support situational awareness during incidents.  
Best paired with ADS-B and geolocation tools.

## Tags

#geolocation  
#maritime  
#ais  
#physical-recon  
#osint  
#free  
