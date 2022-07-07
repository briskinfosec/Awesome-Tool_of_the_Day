FINALRECON
============
FinalRecon is a fast and simple python script for web reconnaissance. It follows a modular structure so in future new modules can be added with ease.

![Finalrecon](https://www.briskinfosec.com//assets/tooloftheday/Copy_of_Briskinfosec_TOD_Latest_samples_187.jpg)

Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name |FinalRecon   |
|  Category | Web Application  |
|  Purpose |  Python Script for Web Reconnaissance |
|  Licence |    Opensource|

Demo Video:
-----------------
Click Here for [Video](https://youtu.be/o-oOwMcmZ7E)

Blog: 
--------------
Click Here for [Blog](https://www.briskinfosec.com/tooloftheday/toolofthedaydetail/FinalRecon)

Installation
----------------

    git clone https://github.com/thewhiteh4t/FinalRecon.git
	
    cd FinalRecon
	
    pip3 install -r requirements.txt

Usage
---------
> python3 finalrecon.py -h

> usage: finalrecon.py [-h] [--headers] [--sslinfo] [--whois] [--crawl] [--dns] [--sub]
                     [--trace] [--dir] [--ps] [--full] [-t T] [-T T] [-w W] [-r] [-s]
                     [-sp SP] [-d D] [-e E] [-m M] [-p P] [-tt TT] [-o O]
                     url

> FinalRecon - The Last Web Recon Tool You Will Need | v1.1.0

> positional arguments:
  url         Target URL

> optional arguments:
  -h, --help  show this help message and exit
  --headers   Header Information
  --sslinfo   SSL Certificate Information
  --whois     Whois Lookup
  --crawl     Crawl Target
  --dns       DNS Enumeration
  --sub       Sub-Domain Enumeration
  --trace     Traceroute
  --dir       Directory Search
  --ps        Fast Port Scan
  --full      Full Recon

>  Extra Options:
  -t T        Number of Threads [ Default : 30 ]
  -T T        Request Timeout [ Default : 30.0 ]
  -w W        Path to Wordlist [ Default : wordlists/dirb_common.txt ]
  -r          Allow Redirect [ Default : False ]
  -s          Toggle SSL Verification [ Default : True ]
  -sp SP      Specify SSL Port [ Default : 443 ]
  -d D        Custom DNS Servers [ Default : 1.1.1.1 ]
  -e E        File Extensions [ Example : txt, xml, php ]
  -m M        Traceroute Mode [ Default : UDP ] [ Available : TCP, ICMP ]
  -p P        Port for Traceroute [ Default : 80 / 33434 ]
  -tt TT      Traceroute Timeout [ Default : 1.0 ]
  -o O        Export Output [ Default : txt ] [ Available : xml, csv ]

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")


 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 

  ![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")

