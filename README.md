# BTCClipperMalware

<p align="center">
  <img width="150" height="150" src="https://i.imgur.com/Xb2QXp6.png">
</p>

A simple example for a Multi-OS malware that exploits the clipboard using Python 3

This is just a concept for a malware that steals btc.

This is commonly known as clipper malware or a "BTC Clipper"

It functions by checking if the user has a btc address copied and then it will replace the copied address with the users own btc address. 
This causes the person sending btc to unknowingly send the btc to the host's btc address.

Two versions of this program are currently developed. One is standalone and uses no external packages. This version supports Windows / Mac

The Other version uses a package called clipboard (https://pypi.org/project/clipboard/). This version supports Windows / Mac / Linux
(Note since this version uses a dependancy the bundled executable will be larger, OR the infected machine would need to install this package.)

Theoretical real world use would be to use a dropper or embed a compiled exe into something.

<h>Setup / Usage</h>

1) Download source of either version you want
2) Replace "Paste BTC Address Here" with your btc address
3) done.

THIS WAS WRITTEN / MADE TO SPREAD AWARENESS OF THIS ISSUE ASWELL AS HOW A SIMILIAR MALWARE MAY WORK. 
WHATEVER THIS CODE IS USED FOR ISN'T MY PROBLEM. USE AT YOUR OWN DISCRETION.
