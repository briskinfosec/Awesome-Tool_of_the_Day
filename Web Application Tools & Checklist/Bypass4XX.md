BYP4XX 
============
Python script for 40X responses bypassing. Methods from #bugbountytips, headers, verb tampering and user agents.

![BYP4XX](https://www.briskinfosec.com//assets/tooloftheday/Copy_of_Briskinfosec_TOD_Latest_samples_195.jpg)


Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name |  BYP4XX |
|  Category | Web Application  |
|  Purpose | Script to bypass "403 Forbidden" responses with well-known methods  |
|  License |    Opensource|

Demo Video:
-----------------
Click Here for [Video](https://youtu.be/YuMOg-MnGEE "Video")

Blog: 
--------------
Click Here for [Blog](https://www.briskinfosec.com/tooloftheday/toolofthedaydetail/Byp4xx "Blog")

Installation
----------------

    git clone https://github.com/lobuhi/byp4xx.git
    cd byp4xx
    chmod u+x byp4xx.sh

Usage
------------
> Start URL with http or https.

> ./byp4xx.sh [OPTIONS] http(s)://url/path

> Options

>   -c Return the entire curl command if response is 200

>   -r Redirects if the response is 3XX

**Example**

> ./byp4xx.sh https://www.google.es/test

Features 

- Multiple HTTP verbs/methods

- Multiple methods mentioned in #bugbountytips

- Multiple headers: Referer, X-Custom-IP-Authorization...

- Allow redirects

- Return the entire curl command if response is 200

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
 ![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
