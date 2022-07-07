CIPHERSCAN
============

A very simple way to find out which SSL ciphersuites are supported by a target.

![ ](https://briskinfosec.com//assets/tooloftheday/Copy_of_Briskinfosec_TOD_Latest_samples_2.jpg)


Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name |  Cipher scan |
|  Category | Network security  |
|  Purpose | A very simple way to find out which SSL ciphersuites are supported by a target. |
|  License |    Opensource|

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=VBoDiKlPWW8 "Video")


Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/CIPHERSCAN "Blog")

Installation
----------------

- git clone https://github.com/mozilla/cipherscan.git
- cd cipherscan
- ./cipherscan google.com


Purpose
----------------
- Cipherscan tests the ordering of the SSL/TLS ciphers on a given target, for all major versions of SSL and TLS.
- It also extracts some certificates informations, TLS options, OCSP stapling and more. Cipherscan is a wrapper above the openssl s_client command line.
- Cipherscan is meant to run on all flavors of unix. 
- It ships with its own built of OpenSSL for Linux/64 and Darwin/64.
- On other platform, it will use the openssl version provided by the operating system (which may have limited ciphers support), or your own version provided in the -o command line flag


Links
----------------

 ![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")


 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 

  ![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")