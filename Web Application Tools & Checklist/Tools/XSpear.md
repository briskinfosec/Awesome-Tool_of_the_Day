XSpear
============
XSpear is XSS Scanner tool which is written in ruby gems. It can be useful for detecting the XSS vulnerability with different level of payloads.

![Webpwn3r](https://briskinfosec.com//assets/tooloftheday/Copy_of_Briskinfosec_TOD_Latest_samples_6.jpg)

Features:
-----------------
- Pattern matching based XSS scanning
- Detect alert confirm prompt event on headless browser
- Testing request/response for XSS protection bypass and reflected(or all) params
- Scanning from Raw file(Burp suite, ZAP Request)
- Testing at selected parameters
- Support output format cli json html
- Support Verbose level (0~3)


Installation
----------------
       $ git clone https://github.com/hahwul/XSpear.git
       You can also install using “gem install XSpear” 
       $ gem install XSpear-{version}.gem


Usage:
-----------------
     xspear -u "http://testphp.vulnweb.com/listproducts.php?cat=123" -v 0
     V 0: quite mode(show only result)
     V 1: show progress bar (default)
     V 2: show scanning logs
     V 3: show scanning detail logs
     
     Scanning XSS
     $ xspear -u "http://testphp.vulnweb.com/search.php?test=query" -d "searchFor=yy"
     
     Only JSON output
     $ xspear -u "http://testphp.vulnweb.com/search.php?test=query" -d "searchFor=yy" -o json -v 0
     
     Set scanning thread
     $ xspear -u "http://testphp.vulnweb.com/search.php?test=query" -t 30
     
     Testing at selected parameters
     $ xspear -u "http://testphp.vulnweb.com/search.php?test=query&cat=123&ppl=1fhhahwul" -p cat,test
     
     Testing at all parameters (This option is tested with or without reflection.)
     $ xspear -u "http://testphp.vulnweb.com/search.php?test=query&cat=123&ppl=1fhhahwul" -a
     
     Testing Only parameter analysis (aka no-xss mode)
     $ xspear -u "http://testphp.vulnweb.com/search.php?test=query&cat=123&ppl=1fhhahwul" --no-xss
     
     Testing blind xss(all params)
     $ xspear -u "http://testphp.vulnweb.com/search.php?test=query" -b "https://hahwul.xss.ht" -a


Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=bmN0ZF9ejCc "Video")

Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/XSpear "Blog")

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
