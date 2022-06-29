Whatwaf
============
WhatWaf is an advanced firewall detection tool which works by detecting a firewall on a web application, and attempting to detect a bypass for said firewall, on the specified target.


![Whatwaf](https://www.briskinfosec.com//assets/tooloftheday/Copy_of_Copy_of_Briskinfosec_TOD_Latest_samples_197.jpg)

Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name |  Whatwaf |
|  Category | Web Application  |
|  Purpose | advanced firewall detection tool which works by detecting a firewall on a web application|
|  Licence |    Opensource|

Demo Video:
-----------------
Click Here for [Video](https://youtu.be/B-QgSHlSSTM "Video")

Blog: 
--------------
Click Here for [Blog](https://www.briskinfosec.com/tooloftheday/toolofthedaydetail/WhatWaf "Blog")

Usage
----------------
> python3 whatwaf -[u|l|b|g] VALUE|PATH|PATH|PATH [-p|--pl] PAYLOAD,..|PATH [--args]
Options
 
> optional arguments

    -h, --help            show this help message and exit
 
> Mandatory arguments

  > arguments that have to be passed for the program to run

>  -u URL, --url URL     Pass a single URL to detect the protection

>  -l PATH, --list PATH, -f PATH, --file PATH

   >   Pass a file containing URL's (one per line) to detect

      the protection

  >-b FILE-PATH, --burp FILE-PATH

      Pass a Burp Suite request file to perform WAF
      evaluation

>  -g GOOGLER-JSON-FILE, --googler GOOGLER-JSON-FILE

        Pass a JSON file from the Googler CMD line tool (IE

         googler -n 100 --json >> googler.json)
 
>Request arguments

  >arguments that will control your requests

> --pa USER-AGENT       Provide your own personal agent to use it for the HTTP  requests

> --ra                                Use a random user-agent for the HTTP request  (*default=whatwaf/2.0 (Language=2.7.10; Platform=Darwin))

>  -H HEADER=VALUE,HEADER:VALUE.., --headers HEADER=VALUE,HEADER:VALUE..

    Add your own custom headers to the request. To use

    multiple separate headers by comma. Your headers need

     to be exact(IE: Set-Cookie=a345ddsswe,X-Forwarded-

      For:127.0.0.1) (*default=None)

>--proxy PROXY         Provide a proxy to run behind in the format

      type://address:port (IE socks5://10.54.127.4:1080)

      (*default=None)

>  --to use Tor as the proxy to run behind, must have Tor

      installed (*default=False)

>  --check-tor           Check your Tor connection (default=False)

>  -p PAYLOADS, --payloads PAYLOADS

>    Provide your own payloads separated by a comma IE AND

    1=1,AND 2=2

>  --pl PAYLOAD-LIST-PATH

     Provide a file containing a list of payloads 1 per

      line

 > --force-ssl           Force the assignment of HTTPS instead of HTTP while

     processing (*default=HTTP unless otherwise specified by URL)

>  --throttle THROTTLE-TIME (seconds)

    Provide a sleep time per request (*default=0)

>  --timeout TIMEOUT     Control the timeout time of the requests (*default=15)

>  -P, --post            Send a POST request (*default=GET)

>  -D POST-STRING, --data POST-STRING

    Send this data with the POST request (*default=random)

  -t threaded, --threads threaded

    Send requests in parallel (specify number of threads

     (*default=1)

 >  -tP CONFIGTORPORT, --tor-port CONFIGTORPORT

    Change the port that Tor runs on (*default=9050)

>  -T, --test        Test the connection to the website before starting

    (*default=True)

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")



