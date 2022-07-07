Fuzz Faster U Fool
============
 Ffuf – Fuzz Faster U Fool is a great tool used for fuzzing. It has become really popular lately with bug bounty hunters. Ffuf is used for fuzzing Get and Post data but can also be used for finding hidden files, directories or subdomains.

![Webpwn3r](https://www.briskinfosec.com//assets/tooloftheday/117.jpg)

Details:
============
|  Details | Description   |
| ------------ | ------------ |
|Tool Name:| Fuzz Faster U Fool Tool |
|Category :| Web Application|
|purpose  :| Fuzzing Get and Post data  |
|License  :| Opensource

Demo Video:
-----------------
Click Here for [Video]https://youtu.be/j1D8xPi0nxg"Video")

Blog: 
--------------
Click Here for [Blog](https://www.briskinfosec.com/tooloftheday/toolofthedaydetail/Fuzz-Faster-U-Fool-Tool-to-Fuzzing-Get-and-Post-data"Blog")

Installation
----------------

    Clone the github repository and change the current directory

    Install golang

    Run the script with the FUZZ word, url and a wordlist at least

Then you can run a directory discovery which finishes the whole 200k wordlists under 30 seconds which is an impressive performance:

    go run main.go -u http://testphp.vulnweb.com/ -w /usr/share/dirb/wordlists/common.txt
     
Usage
---------------
o define the test case for ffuf, use the keyword FUZZ anywhere in the URL (-u), headers (-H), or POST data (-d).

Fuzz Faster U Fool - v1.0

HTTP OPTIONS:

      -H               Header `"Name: Value"`, separated by colon. Multiple -H flags are accepted.

      -X               HTTP method to use (default: GET)

      -b               Cookie data `"NAME1=VALUE1; NAME2=VALUE2"` for copy as curl functionality.

      -d               POST data

      -r               Follow redirects (default: false)

      -recursion       Scan recursively. Only FUZZ keyword is supported, and URL (-u) has to end in it. (default: false)

      -recursion-depth Maximum recursion depth. (default: 0)

      -replay-proxy    Replay matched requests using this proxy.

      -timeout         HTTP request timeout in seconds. (default: 10)

      -u               Target URL

      -x               HTTP Proxy URL

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
