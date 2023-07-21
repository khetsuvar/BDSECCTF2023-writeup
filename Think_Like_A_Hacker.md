## Think Like A Hacker
One of our contributors has created a promo video for BDSec CTF 2023.<br>
He sent me a zip file containing the promo video and a readme.txt file.<br>
He told me, if I think like a hacker, I'll find something cool! Can you think like a hacker?

Download Link : https://drive.google.com/file/d/1uFt2lNK5d4vb6CpixnWJPHugF6uYhMv5/view?usp=sharing

**Flag Format : BDSEC{flag_here}**

_Author : NomanProdhan_

## How to Get the flag?

1. There wasn't anything in Video so I ran `strings` command.<br>
  * ```
    ┌──(khetsu㉿khetsu)-[~/Desktop] 
    └─$ strings BDSecCTF_2023_Promo.mp4
    ```
  * after some time i got this strings :
    ```
    "Hacking is not about breaking into something; it's about bending reality." - Frank Abagnale
    OQFRP{
    OQFrp_
    PGS_
    2023_
    Ce0z0_
    I1Q30_
    sY4T}
    "The best way to predict the future is to create it." - Peter Drucker
    "Hacking involves a different way of looking at problems that no one's thought of." - Walter O'Brien
    ```
  * ' OQFRP{OQFrp_PGS_2023_Ce0z0_I1Q30_sY4T} ' was the flag but encripted in ROT 13.
2. Decrypting Flag
 * When i found out that flag was ecrrypted in rot 13 i decripted it. <br>
   ![Decrypting Flag](https://imgur.com/OvcGiga.png)


_**FLAG : BDSEC{BDSec_CTF_2023_Pr0m0_V1D30_fL4G}**_
