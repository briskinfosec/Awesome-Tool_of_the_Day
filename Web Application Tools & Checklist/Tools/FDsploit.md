FDsploit
============
File Inclusion & Directory Traversal fuzzing, enumeration & exploitation tool. 

![FDsploit](https://www.briskinfosec.com//assets/tooloftheday/FDsploit.png)

Features:
-----------------
- The LFI-shell interface provides only the output of the file readed or the command issued and not all the html code.
- 3 different types of LFI-shells can be specified.
- Both GET/POST requests are supported.
- Automatic detection of GET parameters.
- Certain parameters can be specified for testing using wildcards (*).
- Optional session cookies can be specified and used.
- Automatic check for RCE using PHP functions can be performed.
- Additional use of sha-256 hash is used to identify the potential vulnerabilities.
- base64/urlencoding support.

# Some Examples
# Directory traversal vulnerability discovery:
From the below output it seems that the directory parameter is probably vulnerable to directory traversal vulnerability since every request with ../ as payload produces a different sha-256 hash. Also the content-length is different for every request:

-  ./fdsploit.py -u 'http://127.0.0.1:8888/test/bWAPP/bWAPP/directory_traversal_2.php?directory=documents' -c 'PHPSESSID=7acf1c5311fee614d0eb40d7f3473087; security_level=0' -d 8

# LFI vulnerability discovery:
Again, the language parameter seems vulnerable to LFI since using ../etc/passwd etc.. as payload, every request being colored with green produces a different hash, a different content-length from the initial, and the keyword specified is found in the response:

- ./fdsploit.py -u 'http://127.0.0.1:8888/test/bWAPP/bWAPP/rlfi.php?language=*&action=go' -c 'PHPSESSID=7acf1c5311fee614d0eb40d7f3473087; security_level=0' -d 7 -k root -p /etc/passwd

# Notes
- When POST verb is used, --params option must also be specified.
- To test for Directory Traversal vulnerability the --payload option must be left to default value (None).
- When --file options is used for multiple-urls testing, then only GET request is supported.
- When both --file & --cookie options are set then since only one cookie can be specified each time - the urls must refer on the same domain or be accessible without a cookie (that's is going to be fixed in a future update).
- input shell is not compatible with POST verb.

Requirements
----------------
    Note: To install the requirements:
       $ pip install -r requirements.txt --upgrade --user

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=iuEPmgUM_Jc "Video")

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
