# EFF dice password lookup in more-usable 4-column format.

This is the word list for EFF.org diceware-style passwords, reformatted:

1. These pdf (and word .docx) have four columnd per page, so that _**each page corresponds to the first two rolls**_.
2. Other than the handy format change, content is entirely copied from: https://www.eff.org/dice (as of 2020).  
3. If you don't know what dice / diceware passwords are, see the above at EFF or the original here:
	1. Original diceware page, AFAIK: https://theworld.com/~reinhold/diceware.html (see update/changelog at end!)

## Contents

1. EFF_dice_large_wordlist_4col.docx 
2. EFF_dice_large_wordlist_4col.pdf

Both of the above files were generated/checked by me in 2020 and re-scanned on https://virustotal.com asof 2023/09/16.  

SECURITY 101: Just because I posted a thing on github and said "it's all good" doesn't mean you can trust me.

## CHANGELOG: UPDATED 20230916

1. REMOVED: `diceware_special_characters.pdf` included from theworld.com/~reinhold/diceware.html in 2020
2. REASON: Behavioral analysis triggered one low-level IDS rule:
```
Matches rule ET INFO Observed Google DNS over HTTPS Domain (dns .google in TLS SNI) at Proofpoint Emerging Threats Open
Misc activity
```
