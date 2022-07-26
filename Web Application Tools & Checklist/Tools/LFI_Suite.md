LFI Suite
============
LFISuite, an open source local file inclusion scanner and exploiter that is coded in Python. It supports multiple attack points and also has TOR proxy support. We all know that Local File Inclusion (also known as LFI) is a process of “including” locally present files, through the exploitation of vulnerable inclusion procedures implemented in the application that accepts un-sanitized input.

![Webpwn3r](https://briskinfosec.com//assets/tooloftheday/145.jpg)

# Installation: 
    Step 1: git clone https://github.com/D35m0nd142/LFISuite
    
    Step 2: cd LFISuite
    
    Step 3: Check for Executable permission
    
    Type ls -la in terminal (in tool location)
    
    Step 4: Type  Chmod +x lfisuite.py   (To grant Execute permission)
    
    Step 5: python lfisuite.py  (To run the tool )

# Commands And Usages :
- python lfisuite.py
    1. Exploiter      
    2. Scanner
- Choose 2 (Scanner) module to scan for LFI Vulnerability.
- Then Enter the Target to start the scan .

Features of LFISuite:
-----------------
- Multi-operating system support – works on Windows, Linux and Mac OS X.
- Automatic configuration.
- Automatic updates.
- Provides 8 different local file inclusion attack 
    - /proc/self/environ
    - php://filter
    - php://input
    - /proc/self/fd
    - access log
    - phpinfo
    - data://
    - expect://
- Provides another option called Auto-Hack, which scans and exploits the target automatically by trying all the attacks one after the other without user interaction.
- TOR proxy support.
- Reverse shell for Windows, Linux and Mac OS X.

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=szFYStQGOw8 "Video")

Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/LFISuite "Blog")

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
