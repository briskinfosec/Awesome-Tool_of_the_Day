 A2SV
============
Auto Scanning to SSL Vulnerability

![BYP4XX](https://www.briskinfosec.com//assets/tooloftheday/Copy_of_Briskinfosec_TOD_Latest_samples_189.jpg)


Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name |  A2SV |
|  Category | Network Security  |
|  Purpose | Automated SSL Vulnerability Scanner that checks for TLS/SSL misconfiguration  |
|  Licence |    Opensource|

Demo Video:
-----------------
Click Here for [Video](https://youtu.be/oyBZ6WRKpys "Video")

Blog: 
--------------
Click Here for [Blog](https://www.briskinfosec.com/tooloftheday/toolofthedaydetail/A2SV "Blog")

Installation
----------------
A. Download(clone) & Unpack A2SV

    git clone https://github.com/hahwul/a2sv.git
    cd a2sv
	chmod +x massbleed.sh

B. Install Python Package / OpenSSL

    pip install argparse
    pip install netaddr
	apt-get install openssl

C. Run A2SV

    pip python a2sv.py -h

Usage
------------

>  usage: a2sv [-h] [-t TARGET] [-tf TARGETFILE] [-p PORT] [-m MODULE] [-d DISPLAY] [-u] [-v]

> optional arguments:
  -h, --helpshow this help message and exit
  -t TARGET, --target TARGET
Target URL and IP Address
 $ e.g -t 127.0.0.1
  -tf TARGETFILE, --targetfile TARGETFILE
Target file(list) URL and IP Address
 $ e.g -tf ./target.list
  -p PORT, --port PORT  Custom Port / Default: 443
 $ e.g -p 8080
  -m MODULE, --module MODULE
Check SSL Vuln with one module
> [anonymous]: Anonymous Cipher
> [crime]: Crime(SPDY)
> [heart]: HeartBleed
> [ccs]: CCS Injection
> [poodle]: SSLv3 POODLE
> [freak]: OpenSSL FREAK
> [logjam]: OpenSSL LOGJAM
> [drown]: SSLv2 DROWN
  -d DISPLAY, --display DISPLAY
Display output
[Y,y] Show output
[N,n] Hide output
  -o OUT, --out OUT Result write to file
 $ e.g -o /home/yourdir/result.txt
  -u, --update  Update A2SV (GIT)
  -v, --version Show Version


**Example**

> $ python a2sv.py -t 127.0.0.1

> $ python a2sv.py -t 127.0.0.1 -m heartbleed

> $ python a2sv.py -t 127.0.0.1 -d n

> $ python a2sv.py -t 127.0.0.1 -p 8111

> $ python a2sv.py -tf target_list.txt

**To Update A2SV**
> $ python a2sv.py -u

> $ python a2sv.py --update


SUPPORT VULNERABILITIES
--------------------

- CVE-2007-1858] Anonymous Cipher
- CVE-2012-4929] CRIME(SPDY)
- CVE-2014-0160] CCS Injection
- CVE-2014-0224] HeartBleed
- CVE-2014-3566] SSLv3 POODLE
- CVE-2015-0204] FREAK Attack
- CVE-2015-4000] LOGJAM Attack
- CVE-2016-0800] SSLv2 DROWN

Links
----------------
:fa-youtube-play:  [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")

:fa-github:  [Github](https://github.com/briskinfosec "Github") 

:fa-globe: [Our Website](https://www.briskinfosec.com/ "Our Website")