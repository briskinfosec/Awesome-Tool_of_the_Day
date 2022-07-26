CMSeeK
============
CMS Detection and Exploitation suite - Scan WordPress, Joomla, Drupal and over 180 other CMSs.

What is a CMS?
==============
A content management system (CMS) manages the creation and modification of digital content. It typically supports multiple users in a collaborative environment. Some noteable examples are: WordPress, Joomla, Drupal etc.

Key Features:
-----------------
- Basic CMS Detection of over 170 CMS
- Drupal version detection
- Advanced Wordpress Scans
        Detects Version
        User Enumeration
        Plugins Enumeration
        Theme Enumeration
        Detects Users (3 Detection Methods)
        Looks for Version Vulnerabilities and much more!
- Advanced Joomla 
        Version detection
        Backup files finder
        Admin page finder
        Core vulnerability detection
        Directory listing check
        Config leak detection
        Various other checks
- Modular bruteforce system
        Use pre made bruteforce modules or create your own and integrate with it


Installation
----------------
      $ git clone https://github.com/Tuhinshubhra/CMSeeK
      $ cd CMSeeK
      $ pip/pip3 install -r requirements.txt
      $ python3 cmseek.py

# Detection Methods:
CMSeek detects CMS via the following:
- HTTP Headers
- Generator meta tag
- Page source code
- robots.txt

# Bruteforce Modules:
CMSeek has a modular bruteforce system meaning you can add your custom made bruteforce modules to work with cmseek. A proper documentation for creating modules will be created shortly but in case you already figured out how to (pretty easy once you analyze the pre-made modules) all you need to do is this:
-  Add a comment exactly like this # <Name Of The CMS> Bruteforce module. This will help CMSeeK to know the name of the CMS using regex
- Add another comment ### cmseekbruteforcemodule, this will help CMSeeK to know it is a module
- Copy and paste the module in the brutecms directory under CMSeeK's directory
- Open CMSeeK and Rebuild Cache using R as the input in the first menu.
- If everything is done right you'll see something like this (refer to screenshot below) and your module will be listed in bruteforce menu the next time you open CMSeeK.


Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=H5EwPKA_sBI "Video")

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
