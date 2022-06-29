RACCOON 
============
A high performance offensive security tool for reconnaissance and vulnerability scanning

![ ](https://briskinfosec.com//assets/tooloftheday/Tool_Of_the_day_103.jpg)


Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name | RACCOON |
|  Category | OSINT |
|  Purpose |  A high performance offensive security tool for reconnaissance and vulnerability scanning  |
|  License |    Opensource |

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=GAEluJsQusg "Video")

Blog:
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/Raccoon-Scanner-for-Information-Gathering- "Blog")

Installation
----------------
**For the latest stable version:**

- pip install raccoon-scanner

To run:

- raccoon [OPTIONS]

Please note Raccoon requires Python3.5+ so may need to use pip3 install raccoon-scanner.
You can also clone the GitHub repository for the latest features and changes:

- git clone https://github.com/evyatarmeged/Raccoon.git
- cd Raccoon
- python setup.py install # Subsequent changes to the source code will not be reflected in calls to raccoon when this is used
(Or)
- python setup.py develop # Changes to code will be reflected in calls to raccoon. This can be undone by using python setup.py develop --uninstall
(Finally)
- raccoon [OPTIONS] [TARGET]

Usage
----------------
**Working:**

raccoon-scanner

raccoon-scanner -d -sC

-d, --dns-records TEXT         Comma separated DNS records to query.

-sc, --scripts                 Run Nmap scan with -sC flag

--skip-health-check            Do not test for target host availability

--skip-nmap-scan               Do not perform a Nmap scan

Features
----------------

- DNS details
- DNS visual mapping using DNS dumpster
- WHOIS information
- TLS Data - supported ciphers, TLS versions, certificate details and SANs
- Port Scan
- Services and scripts scan
- URL fuzzing and dir/file detection
- Subdomain enumeration - uses Google dorking, DNS dumpster queries, SAN discovery and bruteforce
- Web application data retrieval:
-  CMS detection
- Web server info and X-Powered-By
- robots.txt and sitemap extraction
- Cookie inspection
- Extracts all fuzzable URLs
- Discovers HTML forms
- Retrieves all Email addresses
- Scans target for vulnerable S3 buckets and enumerates them for sensitive files
- Detects known WAFs
- Supports anonymous routing through Tor/Proxies
- Uses asyncio for improved performance
- Saves output to files - separates targets by folders and modules by files


Links
----------------

 ![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")


 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 

  ![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")