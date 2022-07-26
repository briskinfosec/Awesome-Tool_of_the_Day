Rapid Scan
============
RapidScan is a python based scanning tool used for analyzing vulnerabilities in web applications. The tool is equipped with scanning utilities, such as Nmap, Golismero, Nikto, Uniscan, and Dnsrecon.

The tool runs these utilities to find vulnerabilities in web applications. Some well-known checks performed by the tool include XSS, SQLi, DNS zone transfer, Local File Inclusing (LFI), Remote File Inclusion (RFI), Open directory vulnerabilities, open ports, and SSL related vulnerabilities. The tool not only finds out the vulnerabilities but also classifies them into low, medium, high, and critical categories according to the risk definition.

![Webpwn3r](https://briskinfosec.com//assets/tooloftheday/Tool_Of_the_day09.jpg)

# How to Install The Tool: 
Installation of RapidScan is a straightforward process. The tool can be installed by cloning the Github repository using the following command.The tool requires minimum python 2.7
 - git clone https://github.com/skavngr/rapidscan.git

# How to Scan with RapidScan:
Once the tool is installed, it can be launched using the following command.
- ./rapidscan.py

Features:
-----------------
- one-step installation.
- executes a multitude of security scanning tools, does other custom coded checks and prints the results spontaneously.
- some of the tools include nmap, dnsrecon, wafw00f, uniscan, sslyze, fierce, lbd, theharvester, dnswalk, golismero etc executes under one entity.
- critical, high, medium, low and informational classification of vulnerabilities.
- remediations tells you how to plug/fix the found vulnerability.


Vulnerability Checks:
----------------
- DNS/HTTP Load Balancers & Web Application Firewalls.
- Checks for Joomla, WordPress and Drupal
- SSL related Vulnerabilities (HEARTBLEED, FREAK, POODLE, CCS Injection, LOGJAM, OCSP Stapling).
- Commonly Opened Ports.
- DNS Zone Transfers using multiple tools (Fierce, DNSWalk, DNSRecon, DNSEnum).Sub-Domains Brute Forcing.
- Open Directory/File Brute Forcing.
- Shallow XSS, SQLi and BSQLi Banners.
- Slow-Loris DoS Attack, LFI (Local File Inclusion), RFI (Remote File Inclusion) & RCE (Remote Code Execution).

Output:
-----------------
![Webpwn3r](https://www.briskinfosec.com/themes/new_theme/ckeditor/plugins/imageuploader/uploads/5076691cf.png)

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=rpnXFmn6n68 "Video")

Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/Rapid-Scan-Tool-to-Identifies-vulnerabilities-in-web-applications "Blog")

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
