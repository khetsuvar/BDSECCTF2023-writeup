## Old Client Area
Our sponsor NS TechValley recently changed their billing system and they moved the 
billing/client area to a new domain/sub-domain. Can you find the old billing area domain/sub-domain?
If the old billing/client area domain/sub-domain is https://login.nstechvalley.com then the flag will be:
_**BDSEC{login.nstechvalley.com}**_

Author : NomanProdhan

## How To Get The flag?
1. I searched for NStechValey on google and I found : https://my.nstechvalley.com/ .
   there was the post about new billing system. so i knew that old subdomain would redirect me to this one.
2. I started google dorking to find subdomains : `inurl:nstechvaley.com `.
   and I found this subdomain : https://clients.nstechvalley.com
   and when i clicked me it redirected to https://my.nstechvalley.com.

FLAG _**BDSEC{clients.nstechvalley.com}**_
