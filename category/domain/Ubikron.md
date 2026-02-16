# Ubikron

## Category
Domain / Infrastructure Recon

## Purpose
Ubikron is an OSINT reconnaissance platform used to map domain infrastructure, discover subdomains, identify exposed services, and analyze an organization’s external attack surface.

It helps analysts quickly build an infrastructure overview from a single domain or company name.

## Access / Where to Get It
Website: https://ubikron.com  

## Input
Domain name  
Organization name  

## Output
Subdomains  
Associated IP addresses  
Exposed services  
Technology fingerprints  
Infrastructure relationships  

## Strengths
Fast domain footprinting  
Visual asset mapping  
Good attack-surface overview  
Web-based interface  
Useful for initial recon  

## Limitations
Free tier is limited  
No public API  
Results depend on passive data sources  
Requires manual validation  

## Requires Account
Yes  

## Typical Use Case
You start with a target domain and want a quick snapshot of its external infrastructure before pivoting into deeper DNS, certificate, or exposure analysis.

## Example

Input:
example-company.com  

Output:

Subdomain – portal.example-company.com  
IP – 198.51.100.22  
Service – HTTPS  
Technology – nginx  

This provides a starting point for infrastructure mapping and exposure discovery.

## Notes
Great for early-stage attack surface discovery.  
Pairs well with SecurityTrails, Censys, and DNSDumpster.  
Useful before deeper certificate or directory analysis.  
Best treated as reconnaissance enrichment, not authoritative source.

## Tags

#domain  
#infrastructure  
#attack-surface  
#recon  
#osint  
#free  
#paid  
