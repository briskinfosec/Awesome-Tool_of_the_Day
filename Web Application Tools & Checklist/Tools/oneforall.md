OneForAll
============
OneForAll is a powerful chinese subdomain and dns enumeration tool.When considering about subdomain enumeration, amass might be your first and preferable subdomain emumeration tool in your recon arsenal. You might be wondering what makes OneForAll more soundful comparatively to the tools like amass, OneForAll is a practical supplement to provide an extra edge due to its Chinese context. OneForAll pulls from a multitude of exotic Chinese data sources that other tools typically do not query — FOFA, Baidu Cloud Observation, Gitee, and ChinaZ Alexa, to name a few in it’s collection. This improves your chances of finding unique, previously undiscovered entry points during your recon activities. 

![OneForAll](https://www.briskinfosec.com//assets/tooloftheday/142.jpg)

Details:
============
|  Details | Description |
| ------------ | ------------ |
|Tool Name:| OneForAll |
|Category :| Web Application|
|purpose  :|OneForAll Powerful Sub Domain & DNS Enumeration.|
|License :| Opensource

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=gKs1coddTro "Video")

Blog: 
--------------
Click Here for [Blog](https://www.briskinfosec.com/tooloftheday/toolofthedaydetail/OneForAll "Blog")

Installation
----------------
Clone the OneForAll project repository:

    git clone https://github.com/shmilylty/OneForAll.git
    
Install the required dependencies:

    cd OneForAll

    python3 -m pip install -U pip setuptools wheel

    pip3 install -r requirements.txt

    cd oneforall

    python3 oneforall.py --help
    
Usecases
----------------
Make sure you are in the directory of OneForAll and provide the run argument at the end of command for execution.

    python3 oneforall.py --target run

The command line flags are verbose and redundant at times, such as having to specify run each time. Here are the optional flags for advanced usage:

    --valid None

    --brute True

    --port

    --format

    --dns False

    --req False

    --takeover True

    --show True

    --path 

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
