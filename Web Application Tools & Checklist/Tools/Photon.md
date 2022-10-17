Photon Tool
============
Photon is a incredibly fast crawler designed for automating OSINT(Open Source Intelligence). This tool designed with the simple command line interface consists with multiple options and flags to perform the specific passive reconnaissance operation on our target url or domain name. This tool is written in Python 3x, by s0md3v. You can also install this as a python module by using pip. Photon basically acts as the web crawler which can able to extract the urls and parameters in web application automatically by spidering. Also able to fuzz them and finding the secret auth keys, fetching the previous information about the website from wayback archive so on. Flexibility is one of the main advantage in Photon you can control timeouts, delays and also add seeds, excluding the urls matching the regex pattern. This tool let’s you crawl the web exactly the way you want.
 
![photon](https://www.briskinfosec.com/assets/tooloftheday/130.jpg)

Key Features:
-----------------
Photon can extract the following data while crawling:
- URLs (in-scope & out-of-scope)
- URLs with parameters (example.com/gallery.php?id=2)
- Intel (emails, social media accounts, amazon buckets etc.)
- Files (pdf, png, xml etc.)
- Secret keys (auth/API keys & hashes)
- JavaScript files & Endpoints present in them
- Strings matching custom regex pattern
- Subdomains & DNS related data

The extracted information is saved in an organized manner or can be exported as json.

Flexible
----------------
Control timeout, delay, add seeds, exclude URLs matching a regex pattern and other cool stuff. The extensive range of options provided by Photon lets you crawl the web exactly the way you want.

# Genius
Photon's smart thread management & refined logic gives you top notch performance.
Still, crawling can be resource intensive but Photon has some tricks up it's sleeves. You can fetch URLs archived by archive.org to be used as seeds by using --wayback option.

# Plugins
- Wayback
- dnsdumpster
- Exporter

# Docker

    Photon can be launched using a lightweight Python-Alpine (103 MB) Docker image.
        $ git clone https://github.com/s0md3v/Photon.git
        $ cd Photon
        $ docker build -t photon .
        $ docker run -it --name photon photon:latest -u google.com
    
    To view results, you can either head over to the local docker volume, which you can find by running docker inspect photon or by mounting the target loot folder:
    
        $ docker run -it --name photon -v "$PWD:/Photon/google.com" photon:latest -u google.com


Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=GHwi4S89KW0 "Video")

Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/Incredibly-fast-crawler-designed-for-OSINT. "Blog")

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
