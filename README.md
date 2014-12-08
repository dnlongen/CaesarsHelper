CaesarsHelper
=============

Simple Caesar Cipher decoder

Written by my 11-year-old daughter and I as a learning project. A Caesar Cipher is a simple method of encoding a message by substituting a different letter for each letter in the original message. The cipher is formed by rotating the alphabet a certain number of places to the right or the left - A is replaced with Z, B with A, C with B, and so forth.

The simplest use is <i>caesar.py message</i>, which will show every possible shift. Optionally, if you know the number of spaces to shift the alphabet, you can use the -r argument to show only that output. Since a substitution cipher is reversible, this program can also be used to tage a cleartext message and encode it.

See http://dnlongen.blogspot.com/2014/12/a-little-python-in-morning.html for more information

Requirements:
=============

* argparse

Usage: 
=============

```
caesar.py [-h] [-r ROT] ciphertext

Decode a message hidden by a Caesar cipher.

positional arguments:
  ciphertext

optional arguments:<br>
  -h, --help         show this help message and exit<br>
  -r ROT, --rot ROT  Number of places to rotate the alphabet (-13 to +13)
```

Example:
=============

```
# caesar.py FGETARV-QPNA
Rotating FGETARV-QPNA

-13 ==> STRGNEI-DCAN
-12 ==> TUSHOFJ-EDBO
-11 ==> UVTIPGK-FECP
-10 ==> VWUJQHL-GFDQ
 -9 ==> WXVKRIM-HGER
 -8 ==> XYWLSJN-IHFS
 -7 ==> YZXMTKO-JIGT
 -6 ==> ZAYNULP-KJHU
 -5 ==> ABZOVMQ-LKIV
 -4 ==> BCAPWNR-MLJW
 -3 ==> CDBQXOS-NMKX
 -2 ==> DECRYPT-ONLY
 -1 ==> EFDSZQU-POMZ
 +0 ==> FGETARV-QPNA
 +1 ==> GHFUBSW-RQOB
 +2 ==> HIGVCTX-SRPC
 +3 ==> IJHWDUY-TSQD
 +4 ==> JKIXEVZ-UTRE
 +5 ==> KLJYFWA-VUSF
 +6 ==> LMKZGXB-WVTG
 +7 ==> MNLAHYC-XWUH
 +8 ==> NOMBIZD-YXVI
 +9 ==> OPNCJAE-ZYWJ
+10 ==> PQODKBF-AZXK
+11 ==> QRPELCG-BAYL
+12 ==> RSQFMDH-CBZM
+13 ==> STRGNEI-DCAN
```
