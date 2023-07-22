## Operation Cyber Pursuit 0x04
```
A pivotal update surfaces in the investigation.
Cyber intelligence OSINT expert, Ishtiaq,
reveals Hax0r BD's recent arrival in Dhaka. Your mission:
pinpoint the exact date and hotel where the hacker stayed.
As an investigator, your expertise in OSINT will be paramount
in unraveling the cybercriminal's movements. Time is of the essence,
as the nation awaits your insights to intercept and bring Hax0r BD to justice.
The clock is ticking as you dive into the digital trails left behind, determined
to unmask the truth behind the hacker's arrival.
```
**Flag Format : BDSEC{DD_MM_YYYY_Hotel_Name}**

Example Flag : BDSEC{20_07_2023_KS_Hotel)

_*If there is any space in the hotel name, replace that with underscore.*_

Author : NomanProdhan


## How to get the flag?

In the ![0x03](https://github.com/KH3TSU/BDSECCTF2023-writeup/blob/main/Operation_Cyber_Pursuit_0x03.md) We got Hackers Instagram Account.

While analyzing photos I found ![This image](https://www.instagram.com/p/CuxeON6hDnC/) with this in descripton:

` After a long journey, checked in here yesterday,
one of the best five star hotel in Dhaka`

I saw that date was 16.07.2023 and After that I reverse image searched and found out that hotel name was : ` InterContinental Dhaka `

_**FLAG : BDSEC{16_07_2023_InterContinental}**_
