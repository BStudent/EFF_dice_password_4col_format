# EFF roll-the-dice passphrase tables, more usable format.

If  you don't know what dice-generated passphrases are, see: https://www.eff.org/dice.  If you try using them more than once, you'll see why having the tables in this format is helpful.

1. These pdf (and word .docx) have four columns per page, which means that _**each page corresponds to the first two rolls**_.
2. Other than the handy format change, content is entirely copied from the `eff_large_wordlist.txt`, available at  https://www.eff.org/dice and included here for reference.  
3. Here is original "diceware" page AFAIK: https://theworld.com/~reinhold/diceware.html - please see changelog below.

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
