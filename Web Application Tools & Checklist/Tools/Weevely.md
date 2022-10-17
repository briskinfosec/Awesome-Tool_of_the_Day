WEEVELY
============
Weevely is a web shell designed for post-exploitation purposes that can be extended over the network at runtime.

![Weevely ](https://www.briskinfosec.com/assets/tooloftheday/147.jpg)


Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name |  WEEVELY |
|  Category | Web Application  |
|  Purpose |   Weevely is a web shell designed for post-exploitation purposes that can be extended over the network at runtime  |
|  License |    Opensource|

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=8FNy9V4Xebk "Video")

Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/Weevely- "Blog")

Installation
----------------


To install weevely in kali linux

Note: its already installed in kali. if not use below command

- apt install weevely

After installation, we can use weevely to generate web shell

- weevely generate -h

We can set password for our web shell so that others can't interact with it

Now we will generate a php web shell and try to upload it to vulnerable web app to genetrate php shell

- weevely generate Password@123 /root/Desktop/agentfile.php


----------------
Features
----------------

- Shell access to the target
- SQL console pivoting on the target
- HTTP/HTTPS proxy to browse through the target
- Upload and download files
- Spawn reverse and direct TCP shells
- Audit remote target security
- Port scan pivoting on target
- Mount the remote filesystem
- Bruteforce SQL accounts pivoting on the target

Links
----------------

 ![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")


 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 

  ![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
