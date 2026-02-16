# Dork Search Pro

## Category
Domain / Infrastructure Recon

## Purpose
Dork Search Pro is a web-based Google dorking tool that allows analysts to quickly search for exposed files, login portals, directories, and sensitive data indexed by search engines.

It simplifies advanced search operators into an easy interface for domain reconnaissance and exposure discovery.

## Access / Where to Get It
Website: https://dorksearchpro.com  

## Input
Domain name  
Keyword  
File type  
Custom dork query  

## Output
Indexed URLs  
Exposed documents  
Login portals  
Open directories  
Search engine results  

## Strengths
Simple browser-based interface  
Fast dork execution  
No installation required  
Good for quick exposure checks  
Free version available  

## Limitations
Relies on Google indexing  
No API  
Manual validation required  
Advanced features may require payment  

## Requires Account
No for basic usage  
Yes for advanced features  

## Typical Use Case
You are investigating a domain and want to quickly identify publicly indexed PDFs, spreadsheets, admin panels, or directories without manually crafting Google dorks.

## Example

Input:
example-company.com  

Output:

site:example-company.com filetype:xlsx  
site:example-company.com inurl:admin  
site:example-company.com ext:pdf  

These results may reveal accidentally exposed internal documents or portals.

## Notes
Acts as a recon accelerator, not a primary OSINT source.  
Best paired with DNSDumpster and SecurityTrails.  
Useful for shadow IT and data exposure discovery.  
Always ensure legal authorization before querying.

## Tags

#domain  
#dorking  
#recon  
#exposure  
#osint  
#free  
#paid  
