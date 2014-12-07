CaesarsHelper
=============

Simple Caesar Cipher decoder

Optionally shows a rotation of a specified number of characters (ROT13 for example), or every possible shift.

Usage: 

usage: caesar.py [-h] [-r ROT] ciphertext

Decode a message hidden by a Caesar cipher.

positional arguments:
  ciphertext

optional arguments:
  -h, --help         show this help message and exit
  -r ROT, --rot ROT  Number of places to rotate the alphabet (-13 to +13)

See http://dnlongen.blogspot.com/2014/12/a-little-python-in-morning.html for more information
