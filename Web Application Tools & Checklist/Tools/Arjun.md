Arjun
============
Arjun can find query parameters for URL endpoints. If you don't get what that means, it's okay, read along.
Web applications use parameters (or queries) to accept user input, take the following example into consideration
http://api.example.com/v1/userinfo?id=751634589
This URL seems to load user information for a specific user id, but what if there exists a parameter named admin which when set to True makes the endpoint provide more information about the user? This is what Arjun does, it finds valid HTTP parameters with a huge default dictionary of 10,985 parameter names. The best part? It takes less than 10 seconds to go through this huge list while making just 20-30 requests to the target.


![Webpwn3r](https://briskinfosec.com//assets/tooloftheday/Tool_Of_the_day08.jpg)

Key Features:
-----------------
- Fast web crawling 
- Brute force and parse sitemap.xml 
- Parse robots.txt 
- Generate and verify link from JavaScript files 
- Link Finder 
- Find AWS-S3 from response source 
- Find subdomains from response source 
- Get URLs from Wayback Machine, Common Crawl, Virus Total, Alien Vault 
- Format output easy to Grep 
- Support Burp input 
- Crawl multiple sites in parallel 
- Random mobile/web User-Agent

Installation
----------------
    Install go in your environment and run the below command : 
      $ go get -u github.com/jaeles-project/gospider



# Usage:

Scanning a single URL
-----------------
- To find GET parameters, you can simply do:
- python3 arjun.py -u https://api.example.com/endpoint --get
- Similarly, use --post for POST and --json to look for JSON parameters.

Scanning multiple URLs
-----------------
- A list of URLs stored in a file can be test by using the --urls option as follows
- python3 arjun.py --urls targets.txt --get

Multi-threading
-----------------
- Arjun uses 2 threads by default but you can tune its performance according to your network connection and target allowance.
- python3 arjun.py -u https://api.example.com/endpoint --get -t 22
- Delay between requests
- You can delay the request by using the -d option as follows:
- python3 arjun.py -u https://api.example.com/endpoint --get -d 2

Handling rate limits
-----------------
- --stable switch sets the number of threads to 1 and introduces a random delay of 6 to 12 seconds between requests.
- python3 arjun.py -u https://api.example.com/endpoint --get --stable

Including persistent data
-----------------
- Let's say you have an API key that you need to send with every request, to tell Arjun to do that you can use the --include option as follows:
- python3 arjun.py -u https://api.example.com/endpoint --get --include 'api_key=xxxxx'
OR
- python3 arjun.py -u https://api.example.com/endpoint --get --include '{"api_key":"xxxxx"}'
- To include multiple parameters, use & to seperate them or pass them as a valid json object.

Saving output to a file
-----------------
- You can save the result in a JSON format by using the -o as follows:
- python3 arjun.py -u https://api.example.com/endpoint --get -o result.json


Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=t65Zp-bYBlo "Video")

Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/Arjun-Tool-to-Identifies-hidden-GET-and-POST-Parameters "Blog")

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
