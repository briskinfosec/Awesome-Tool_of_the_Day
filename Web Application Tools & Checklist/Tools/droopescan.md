DROOPESCAN
============
Usage of droopescan for attacking targets without prior mutual consent is illegal. It is the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program. Please note that while droopescan outputs the most CMS likely version installed on the remote host, any correlation between version numbers and vulnerabilities must be done manually by the user

![Webpwn3r](https://www.briskinfosec.com//assets/tooloftheday/143.jpg)

Details:
============
|  Details | Description   |
| ------------ | ------------ |
|Tool Name:| DROOPESCAN |
|Category :| Web Application |
|purpose  :| Plugin Based Scanner that Identify issues with Several CMS. |
|License :| Opensource

Demo Video:
-----------------
Click Here for [Video](https://youtu.be/x3LieAkeePM"Video")

Blog: 
--------------
Click Here for [Blog](https://www.briskinfosec.com/tooloftheday/toolofthedaydetail/DROOPESCAN-Plugin-Based-Scanner "Blog")

Installation
----------------
     git clone https://github.com/droope/droopescan.git

     cd droopescan

     pip install -r requirements.txt

     ./droopescan scan --help
 usage
 ---------------
 
    You can specify a particular host to scan by passing the -u or --url parameter:

    droopescan scan drupal -u example.org

    You can also omit the drupal argument. This will trigger “CMS identification”, like so:

    droopescan scan -u example.org

    Multiple URLs may be scanned utilising the -U or --url-file parameter. This parameter should be set to the path of a file which contains a list of URLs.

    droopescan scan drupal -U list_of_urls.txt

    The drupal parameter may also be ommited in this example. For each site, it will make several GET requests in order to perform CMS identification, and if the site is deemed to be a supported CMS, it is scanned and added to the output list. This can be useful, for example, to run droopescan across all your organisation's sites.
    
    droopescan scan -U list_of_urls.txt
    
Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
