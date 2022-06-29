ENTROPY
============
This tool  is use to find the default Ip cameras passwords over different vendors

![ ](https://briskinfosec.com//assets/tooloftheday/113.jpg)


Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name | ENTROPY |
|  Category | Network security  |
|  Purpose |  This tool  is use to find the default Ip cameras passwords over different vendors |
|  License |    Opensource |

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=wXo8zWkv3u4  "Video")


Blog:
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/Entropy-to-find-default-IP-cameras-password "Blog")

Installation
----------------
Clone the repository
- git clone https://github.com/entynetproject/entropy
Run the install file using
- ./install.sh
Type entropy to get help menus
- entropy -h

Usecases
----------------
Entropy Toolkit examples

Example of attacking a single webcam

    entropy -b 1 -i 192.168.1.100:80 -v

Example of attacking webcams from a file

    entropy -b 2 -l iplist.txt -v

Example of attacking webcams through Shodan

    entropy -b 2 -v --shodan PSKINdQe1GyxGgecYz2191H2JoS9qvgD

Links
----------------

 ![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")


 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 

  ![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")