## Operation Cyber Pursuit 0x01 
```
Operation Cyber Pursuit continues with a new mission that will push your skills to the limit.
The Detective Branch (DB) of the Bangladesh Police has received critical information from a trusted
source within the Rapid Action Battalion (RAB). It has come to light that Hax0r BD, the elusive cybercriminal,
has successfully exploited a government website, resulting in a massive data breach. As a highly skilled OSINT investigator,
your task is to uncover the specific vulnerability that Hax0r BD exploited, plunging into the depths of the digital world with an air of thrilling urgency.

In a confidential meeting, Detective Selina of the DB conveys the gravity of the situation.
"We have received a crucial intel from an officer in the RAB," she reveals.
"Hax0r BD managed to breach a highly secured government website, compromising its data.
The RAB officer confirmed that the website was vulnerable to a known CVE exploit."

Task : Find the CVE
```
Flag Format : _**BDSEC{CVE-XXXX-XXXXX}**_

Note: This is an OSINT challenge, you don't have to compromise any website :P

Author : NomanProdhan

## How to get the flag?
1. Search for data dumps from this person on google,brave,duckduckgo and more (I searched **Hax0r_BD Dumped Data**)
2. try to find on websites where they can host text. (for example : _pastebin_)
while I was searching on duckduckgo I found Paste on pastebin named **Dumped Data**. Here is the link ![link](https://pastebin.com/b4XVaF9j)
Text there was `Gov sites sucks CVE-2023-23752 rocks 😋` . so CVE would be CVE-2023-23752

Flag: _**BDSEC{CVE-2023-23752}**_
