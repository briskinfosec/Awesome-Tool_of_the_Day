Altair Web Security
============
Altair is a Python based tool that does not require any specific packages to be installed as a pre-requisite. The SQLMAP and Lfier tools must be available on the disposal of the tool if the goal is to exploit the (LFI,SQL) vulnerabilities found during the scanning process.

![Altair Web Security](https://www.briskinfosec.com//assets/tooloftheday/Copy_of_Briskinfosec_TOD_Latest_samples_3.jpg)

Installation
----------------
       $ Step 1: git clone https://github.com/evilsocket/altair
       $ Step 2: cd altair
       $ Step 3: ./altair -h

EXAMPLES:
-----------------
- altair --filter=lfi,rfi --url=http://www.somesite.com
- altair --filter=sqli --load-modules=sqlmap --url=http://www.somesite.com

Options:
----------------
|  Command | Description   |
| ------------ | ------------ |
|-h, --help| show this help message and exit |
|-t THREADS, --threads=THREADS | Max simultaneous threads.|
|-e ALLOWEDEXTENSIONS, --ext=ALLOWEDEXTENSIONS | Comma separated allowed extensions.|
|-a USERAGENT, --ua=USERAGENT | Custom user agent. |
|-d, --enable-delay | Enable crawling delay.|
|-s CRAWLDELAY, --crawl-delay=CRAWLDELAY | Crawling delay in ms.|
|-m MAXDIRECTORYDEPTH, --max-depth=MAXDIRECTORYDEPTH | Max directory depth.|
|-p, --enable-proxy | Enable proxy support. |
| -S PROXYSERVER, --proxy-server=PROXYSERVER | Proxy server address.|
|-P PROXYPORT, --proxy-port=PROXYPORT | Proxy server port.|
|-f KBFILTER, --filter=KBFILTER | Comma separated ids of vulnerabilities to test,            default to all, use the --list-ids flag to enumerate available ids.|
|-I, --list-ids | Print a list of available ids in the knowledge base to be used with the --filter flag.|
|-k KBFILE, --kb=KBFILE | Knowledge base file to use, default kb.xml.|
|-L MODULES, --load-modules=MODULES | Comma separated modules names to load or 'all' to load them all, use the --list-modules flag to a list of available modules.|
| -M, --list-modules | Print a list of available modules.|
|-u URL, --url=URL |  Url to test, mandatory.|
|-O OUTFILE, --output=OUTFILE| Output status and result to file.|
| --import-files=IMPORTFILES | Import sensitive files list from this file.|
|--import-dirs=IMPORTDIRS | Import sensitive directories list from this file.|
|--single-mode | Single url mode, scan only this url for vulnerabilities (the URL has to have at least one parameter).|

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=VC_NZCS1kKc&feature=emb_imp_woyt "Video")

Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/Altair "Blog")

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
