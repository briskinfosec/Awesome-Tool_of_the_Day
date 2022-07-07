PARTH
============
Parth is a Heuristic Vulnerable Parameter Scanner. Some HTTP parameter names are more commonly associated with one functionality than the others. For example, the parameter ?url= usually contains URLs as the value and hence often falls victim to file inclusion, open redirect and SSRF attacks. Parth can go through your burp history, a list of URLs or it's own disocovered URLs to find such parameter names and the risks commonly associated with them. Parth is designed to aid web security testing by helping in prioritization of components for testing. 

![Parth](https://www.briskinfosec.com//assets/tooloftheday/Copy_of_Briskinfosec_TOD_Latest_samples_185.jpg)

Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name |  Parth |
|  Category | Web Application  |
|  Purpose | Heuristic Vulnerable Parameter Scanner  |
|  License |Opensource|

Demo Video:
-----------------
Click Here for [Video](https://youtu.be/3ZCaeak_OH4 "Video")

Blog: 
--------------
Click Here for [Blog](https://www.briskinfosec.com/tooloftheday/toolofthedaydetail/Parth "Blog")


Installation
----------------
    pip3 install parth
 
Usage
---------
Import targets from a file 
This option works for all 3 supported import types: Burp Suite history, newline delimited text file or a HTTP request text file. python3 parth.py -i example.history

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
