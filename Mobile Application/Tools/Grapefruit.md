Grapefruit
============
Grapefruit is a runtime Application Instruments for iOS application and previously it was known by passionfruit. It is used in runtime analysis, which can able to get iOS app details like binary information,listing classes, methods, browsing application’s files in real-time, etc..   


![Webpwn3r](https://briskinfosec.com//assets/tooloftheday/Copy_of_Briskinfosec_TOD_Latest_samples_177.jpg)

Details:
============
|  Details | Description   |
| ------------ | ------------ |
|Tool Name:| Grapefruit |
|Category :| Mobile Application|
|purpose  :| Used in runtime analysis, which can able to get iOS app details like binary information,listing classes, methods, browsing application’s files in real-time, etc..    |
|License :| Opensource

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=QtvZY2xOODY "Video")

Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/Grapefruit "Blog")

Installation
----------------


Git clone

     git clone --recurse-submodules https://github.com/ChiChou/Grapefruit
     
Install dependencies

     node.js v12.x 
     tmux (or Windows Terminal on Windows) 
     Install frida in iphone and in laptop, 

Refer the blog for frida installation 
 https://www.briskinfosec.com/blogs/blogsdetail/Getting-Started-with-Frida 

Install npm packages: 

      npm install 
      
Start development server: 

      npm start 

Default webpack url is http://localhost:8080 

Features 
--------------
1. Cross plarform web GUI!
Also supports non-jailbroken device (patching IPA with frida).
List all url schemes.
Check signature entitlements.
List human readable app meta info (Info.plist).
Capture screenshot.
Checksec: see if target app is encrypted, and has enabled PIE, ARC and stack canary.

2. App sandbox file browser. Directly preview images, SQLite databases and plist files on device. You can always download the file for further investigation.

 3. Check the loaded frameworks. Hook exported native functions from these dylib to print the arguments and stack trace.

Log SQLite operations.
--------------

4. List Objective-C classes from app, hook the methods and inspect the  arguments and stack trace.
Dump KeyChain, BinaryCookies and UserDefaults.

Usages
--------------
Basic, Checksec, url schemes
Storage, Inspector
File browser with hex viewer, image viewer, plist viewer and SQLite database reader.
Objective C classes and methods. 

For more details :  https://github.com/chaitin/passionfruit 
     
     



Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
