ScanT3r
============
Scant3r Scans all URLs with multiple HTTP Methods and Tries to look for bugs with basic exploits as XSS - SQLI - RCE - CRLF -SSTI from Headers and URL Parameters By chaining waybackurls or gau with Scant3r you will have more time to look into functions and get Easy bugs on the way :)

This tool is used to detect these type of vulnerabilities
- Remote Code Execution
- XSS Reflected
- Template Injection
- SQl Injection

![Webpwn3r](https://briskinfosec.com//assets/tooloftheday/127.jpg)

# Installation : 
 open your terminal, enter this command

        $ git clone https://github.com/knassar702/scant3r

        $ cd scant3r

        $ python3 -m pip install -r requirements.txt


# Usage and options:
|  Command | Description   |
| ------------ | ------------ |
| -h, --help                     |    Show help message and exit |
|  --version                     |    Show program's version number and exit |
|  -u URL, --url=URL      |    Target URL (e.g."http://www.target.com/vuln.php?id=1") |
|  --data=DATA               |    Data string to be sent through POST (e.g. "id=1") |
|  --list=FILE                    |    Get All Urls from List |
|  --threads                     |    Max number of concurrent HTTP(s) requests (default 10) |
|  --timeout                    |    Seconds to wait before timeout connection |
|  --proxy                        |    Start The Connection with http(s) proxy |
|  --cookies                    |    HTTP Cookie header value (e.g. "PHPSESSID=a8d127e..") |
|   --encode                    |    How Many encode the payload (default 1) |
|   --allow-redirect        |    Allow the main redirect |
|  --user-agent              |    add custom user-agent |
|  --scan-headers         |    Try to inject payloads in headers not parameters (user-agent,referrer) |
|  --skip-headers          |    Skip The Headers scanning processe |
|  --sleep                       |    Sent one request after some Seconds |
|  --module                   |    add custom module (e.g. "google.py") |
|  --debug                     |    Debugging Mood |

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=vFhsqjKz2F8 "Video")

Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com//assets/tooloftheday/127.jpg "Blog")

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
