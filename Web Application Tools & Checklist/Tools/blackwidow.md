BLACKWIDOW
============

BlackWidow is a python based web application spider to gather subdomains, URL's, dynamic parameters, email addresses and phone numbers from a target website

![Blackwidow ](https://www.briskinfosec.com/assets/tooloftheday/139.jpg)


Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name |  BLACKWIDOW |
|  Category | Web Application  |
|  Purpose | BlackWidow is a python based web application spider to gather subdomains, URL's, dynamic parameters, email addresses and phone numbers from a target website.This project also includes Inject-X fuzzer to scan dynamic URL's for common OWASP vulnerabilities.  |
|  License |    Opensource|

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=-n6VhCCIKWQ  "Video")


Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/BlackWidow "Blog")

Installation
----------------

- git clone https://github.com/1N3/BlackWidow.git
- cd BlackWidow
- sudo bash install.sh



----------------

Usage
----------------
- blackwidow -u https://target.com - crawl target.com with 3 levels of depth.
- blackwidow -d target.com -l 5 -v y - crawl the domain: target.com with 5 levels of depth with verbose logging enabled.
- blackwidow -d target.com -l 5 -c 'test=test' - crawl the domain: target.com with 5 levels of depth using the cookie 'test=test'
- blackwidow -d target.com -l 5 -s y -v y - crawl the domain: target.com with 5 levels of depth and fuzz all unique parameters for OWASP vulnerabilities with verbose logging on.
- injectx.py -u https://test.com/uers.php?user=1&admin=true -v y - Fuzz all GET parameters for common OWASP vulnerabilities with verbose logging enabled.

------------



Features
----------------

1. Automatically collect all URL's from a target website
2. Automatically collect all dynamic URL's and parameters from a target website
3. Automatically collect all subdomains from a target website
4. Automatically collect all phone numbers from a target website
5. Automatically collect all email addresses from a target website
6. Automatically collect all form URL's from a target website
7. Automatically scan/fuzz for common OWASP TOP vulnerabilities
8. Automatically saves all data into sorted text files

------------


Links
----------------

 ![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")


 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 

  ![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
