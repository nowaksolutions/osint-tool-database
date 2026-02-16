# DorkGPT

## Category
Enrichment / Search Intelligence

## Purpose
DorkGPT uses AI to generate Google dorks and advanced search queries for discovering exposed data, misconfigurations, credentials, documents, and infrastructure indexed by search engines.

It helps analysts craft effective reconnaissance queries without manually building complex operators.

## Access / Where to Get It
Website: https://dorkgpt.com  

## Input
Target domain  
Organization name  
Keyword  
File type  
General reconnaissance prompt  

## Output
Generated Google dorks  
Advanced search operators  
Targeted reconnaissance queries  

## Strengths
Fast automated dork generation  
Beginner-friendly interface  
Useful for recon acceleration  
Free tier available  
No installation required  

## Limitations
Paid version required for full features  
Results depend on search engine indexing  
Requires analyst judgment to avoid noise  
Not a data source itself  

## Requires Account
No for basic usage  
Yes for advanced features  

## Typical Use Case
You are investigating a domain or organization and want to quickly generate effective Google dorks to locate exposed files, login portals, or sensitive documents.

## Example

Input:
example-company.com  

Output:

site:example-company.com filetype:pdf  
site:example-company.com inurl:login  
site:example-company.com ext:xlsx  

These queries help surface publicly exposed assets.

## Notes
Acts as a recon accelerator, not a primary OSINT source.  
Best paired with manual Google searching and domain tools.  
Useful for discovering accidental data exposure.  
Always ensure legal authorization before running queries.

## Tags

#enrichment  
#dorking  
#recon  
#search-intelligence  
#osint  
#free  
#paid  
