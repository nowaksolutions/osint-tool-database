# ODCrawler

## Category
Domain / Infrastructure Recon

## Purpose
ODCrawler is a web-based open directory crawler that searches for publicly accessible directories and files indexed by search engines. It helps analysts identify exposed folders, documents, media files, and misconfigured web servers tied to a domain or IP.

It is commonly used for exposure discovery and shadow IT identification.

## Access / Where to Get It
Website: https://odcrawler.xyz  

## Input
Domain name  
IP address  
Keyword  
File type  

## Output
Open directory listings  
Indexed file paths  
Downloadable documents  
Media files  
Exposed folders  

## Strengths
Fast open-directory discovery  
Simple browser-based interface  
No installation required  
Useful for finding accidental data exposure  
Free access available  

## Limitations
No API  
Manual validation required  
Relies on search engine indexing  
Results may include false positives  

## Requires Account
No  

## Typical Use Case
You are investigating a domain and want to determine whether it hosts publicly accessible directories containing sensitive files such as PDFs, backups, or spreadsheets.

## Example

Input:
example-company.com  

Output:

/uploads/finance.xlsx  
/backups/config.zip  
/docs/internal.pdf  

These findings may indicate accidental data exposure.

## Notes
Excellent companion to DorkGPT and Dork Search Pro.  
Useful for shadow IT discovery.  
Best paired with DNSDumpster and SecurityTrails.  
Always ensure legal authorization before accessing exposed content.

## Tags

#domain  
#open-directories  
#exposure  
#recon  
#osint  
#free  
