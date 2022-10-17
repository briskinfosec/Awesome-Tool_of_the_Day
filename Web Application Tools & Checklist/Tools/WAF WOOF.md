WAF WOOF
============
 WAF W00F allows one to identify and fingerprint Web Application Firewall (WAF) products protecting a website.

![WAF WOOF ](https://www.briskinfosec.com/assets/tooloftheday/115.jpg)


Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name |  WAF WOOF |
|  Category | Web Application  |
|  Purpose |   WAFW00F allows one to identify and fingerprint Web Application Firewall (WAF) products protecting a website.   |
|  License |    Opensource|

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=fpQRjOjh-4Q "Video")

Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/WafW00f-Tool-to-Fingerprint-and-identify-Web-Application-Firewall "Blog")

Installation
----------------


Step 1: git clone https://github.com/EnableSecurity/wafw00f.git

Step 2: cd wafw00f

Step 3: Type ‘make’ to install required files, tools to be installed automatically 

Step 4: Type chmod +x setup.py   to grant Execute permission 

Step 5: python setup.py install

------------


Example
----------------

>wafw00f http://example.com

----------------

What does it detect?
----------------

It detects a number of WAFs. To view which WAFs it is able to detect run WAFW00F with the -l option. At the time of writing the output is as follows:

- Anquanbao
- Juniper WebApp Secure
- IBM Web Application Security
- Cisco ACE XML Gateway
- F5 BIG-IP APM
- 360WangZhanBao
- ModSecurity (OWASP CRS)
- PowerCDN
- Safedog
- F5 FirePass
- DenyALL WAF
- Trustwave ModSecurity
- CloudFlare
- Imperva SecureSphere
- Incapsula WAF
- Citrix NetScaler
- F5 BIG-IP LTM
- Art of Defence HyperGuard
- Aqtronix WebKnight
- Teros WAF
- eEye Digital Security SecureIIS
- BinarySec
- IBM DataPower
- Microsoft ISA Server
- NetContinuum
- NSFocus
- ChinaCache-CDN
- West263CDN
- InfoGuard Airlock
- Barracuda Application Firewall
- F5 BIG-IP ASM
- Profense
- Mission Control Application Shield
- Microsoft URLScan
- Applicure dotDefender
- USP Secure Entry Server
- F5 Trafficshield

Links
----------------

 ![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")

 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 

  ![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
