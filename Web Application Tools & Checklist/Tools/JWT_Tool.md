JWT_Tool
============
A toolkit for testing, tweaking and cracking JSON Web Tokens  

![JWT_Tool](https://www.briskinfosec.com//assets/tooloftheday/TOD_2441.png)

Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name |  JWT_Tool |
|  Category | Web Application Security |
|  Purpose | A toolkit for testing, tweaking and cracking JSON Web Tokens |
|  License |  Opensource |

Demo Video:
-----------------
Click Here for [Video](https://youtu.be/Ak9JkvpbvCc "Video")

Blog: 
--------------
Click Here for [Blog](https://www.briskinfosec.com/tooloftheday/toolofthedaydetail/JWT_Tool "Blog")

Installation
----------------
Installation is just a case of downloading the jwt_tool.py file (or git clone the repo).
(chmod the file too if you want to add it to your $PATH and call it from anywhere.)

   git clone https://github.com/ticarpi/jwt_tool
   
   python3 -m pip install termcolor cprint pycryptodomex requests
   
 On first run the tool will generate a config file, some utility files, logfile, and a set of Public and Private keys in various formats.  
   
Usage
------------
The first argument should be the JWT itself (unless providing this in a header or cookie value). Providing no additional arguments will show you the decoded token values for review.

 python3 jwt_tool.py <JWT>
 
The toolkit will validate the token and list the header and payload values
   
Features
--------------

    Checking the validity of a token
   
    Testing for known exploits:
   
        (CVE-2015-2951) The alg=none signature-bypass vulnerability
   
        (CVE-2016-10555) The RS/HS256 public key mismatch vulnerability
   
        (CVE-2018-0114) Key injection vulnerability
   
        (CVE-2019-20933/CVE-2020-28637) Blank password vulnerability
   
        (CVE-2020-28042) Null signature vulnerability
   
    Scanning for misconfigurations or known weaknesses
   
    Fuzzing claim values to provoke unexpected behaviours
   
    Testing the validity of a secret/key file/Public Key/JWKS key
   
    Identifying weak keys via a High-speed Dictionary Attack
   
    Forging new token header and payload contents and creating a new signature with the key or via another attack method
   
    Timestamp tampering
   
    RSA and ECDSA key generation, and reconstruction (from JWKS files)
   
    ...and lots more!
  
    
Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
 ![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
