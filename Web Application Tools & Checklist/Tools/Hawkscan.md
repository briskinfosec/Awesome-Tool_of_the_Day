Hawkscan
============
Security Tool for Reconnaissance and Information Gathering on a website.

![Hawkscan](https://www.briskinfosec.com/assets/tooloftheday/HawkScan.png)

Installation
----------------
       $ git clone https://github.com/c0dejump/HawkScan.git && sudo python3 HawkScan/setup.py install
       
       $ pip(3) install -r requirements.txt 
    
       $ python3 -m pip install -r requirements.
       
Special features:
-----------------
Before scan
- Check header information
- Check DNS information
- Check Github
- CMS detection + version and vulns
- Check in waybackmachine
- Check if DataBase firebaseio existe and accessible
- Testing if it's possible scanning with "localhost" host
- Check Google Dork
- Check Host IP
- Check backup domain name (ex: www.domain.com/domain.zip)
- Check socketio connection
- cse google search (buckets...)

During - After scan
- Test backup/old file on all the files found (index.php.bak, index.php~ ...)
- Backup system (if the script stopped, it take again in same place)
- WAF detection and Response error to WAF + Testing bypass it
- Option --exclude to exclude page, code error, bytes
- Option rate-limit if app is unstable (--timesleep)
- Search S3 buckets in source code page
- Try differents bypass for 403/401 code error
- JS parsing and analysis (option --js)
- Auto resize relative to window
- Notify when scan completed (Only work on Linux)
- Multiple output format. Available formats: json, csv, txt
- Multiple website scanning
- Prefix filename (old_, copy of...)
- Detecting potential path disclosure into html webpage


Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=jfYXdeQHbo4 "Video")

Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/Hawkscan "Blog")

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
