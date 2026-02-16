# Downdetector

## Category
Enrichment / Service Availability Intelligence

## Purpose
Downdetector monitors real-time outages and service disruptions based on user reports and telemetry, allowing analysts to confirm whether issues are widespread or isolated to a specific environment.

It is commonly used to validate incidents, reduce false positives, and add operational context during investigations.

## Access / Where to Get It
Website: https://downdetector.com  

## Input
Service name  
Geographic region  

## Output
Current outage status  
Incident timelines  
User-reported impact  
Regional heatmaps  
Historical availability trends  

## Strengths
Fast real-time visibility  
Covers major platforms and ISPs  
Visual outage mapping  
No account required  
Excellent for incident validation  

## Limitations
Crowdsourced data may be noisy  
No API on free tier  
Limited technical detail  
Not suitable for root-cause analysis  

## Requires Account
No  

## Typical Use Case
You receive alerts indicating connectivity issues with Microsoft, AWS, or an ISP and need to determine whether the problem is global or isolated before escalating internally.

## Example

Input:
Service – Microsoft Teams  

Output:

Status – Major outage reported  
Affected Regions – US East, Central Europe  
Spike detected in user reports  

This confirms a platform-wide incident rather than an internal failure.

## Notes
Useful for first-level incident triage.  
Helps reduce unnecessary escalations.  
Pairs well with SIEM alerts and infrastructure monitoring.  
Best used as situational context, not technical evidence.

## Tags

#enrichment  
#availability  
#outage  
#incident-response  
#soc  
#free  
