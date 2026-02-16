# Username OSINT Tools
## WhatsMyName

## Category
Username Enumeration

## Purpose
Checks whether a specific username exists across hundreds of websites and online platforms.

## Input
Single username (example: johndoe123)

## Output
List of platforms where the username appears, including direct profile links and HTTP validation.

## Strengths
Fast passive reconnaissance  
Large maintained site database  
No account required  
Excellent for initial footprint mapping  

## Limitations
Only works with usernames  
Possible false positives  
Does not provide enrichment (email, real name, etc.)  

## Requires Account
No

## Typical Use Case
You obtain a username from a forum post or alert and want to quickly identify what other platforms that same handle appears on before pivoting deeper.

## Example

Input:
swoledeer
Output:
GitHub – found
Reddit – found
X/Twitter – found
Instagram – not found
Pastebin – found

## Notes

Best used early in investigations.  
Always manually verify results before attribution.  
Pair with people and breach-data OSINT after discovery.

## Tags

#username  
#passive  
#free  
#recon  
#people-osint  
