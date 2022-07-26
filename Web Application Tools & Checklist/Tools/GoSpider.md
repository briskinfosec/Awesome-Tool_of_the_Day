GoSpider
============
GoSpider is a Fast web spider written in Go. It has lot of features to find the subdomains, JS files, AWS details, etc. 

![Webpwn3r](https://briskinfosec.com//assets/tooloftheday/Copy_of_Briskinfosec_TOD_Latest_samples_184.jpg)

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



Usage:
-----------------
     Basic Commands: 
     Run with single site  
     gospider -s "https://google.com/" -o output -c 10 -d 1 
     
     Run with site list  
     gospider -S sites.txt -o output -c 10 -d 1 
     
     For More details: https://github.com/jaeles-project/gospider  

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=uziU0QVH9To "Video")

Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/GoSpider "Blog")

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
