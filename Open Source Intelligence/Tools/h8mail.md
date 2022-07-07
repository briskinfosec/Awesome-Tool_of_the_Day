h8mail
============
h8mail is an email OSINT and breach hunting tool using different breach and reconnaissance , or local breaches such as Troy Hunt's "Collection1" and the infamous "Breach Compilation" torrent. 




![Webpwn3r](https://briskinfosec.com//assets/tooloftheday/Copy_of_Briskinfosec_TOD_Latest_samples_176.jpg)

Details:
============
|  Details | Description   |
| ------------ | ------------ |
|Tool Name:| h8mail |
|Category :| OSINT |
|purpose  :| email OSINT and breach hunting tool using different breach and reconnaissance.  |
|License :| Opensource

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=E4OVQ9PsCo4 "Video")

Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/h8mail- "Blog")

Installation
----------------

Installation of this tool is pretty straight forward.

Install pip3 for python3. By using the pip3 we can install h8mail into our machine.

         pip3 install h8mail  
         
Basic Usecases 
--------------
Query for a single target

            h8mail -t target@example.com

Query for list of targets, indicate config file for API keys, output to pwned_targets.csv

            h8mail -t targets.txt -c config.ini -o pwned_targets.csv 

Query a list of targets against local copy of the Breach

             Compilation, pass API key for snusbase from the command line h8mail -t targets.txt -bc                   

               ../Downloads/BreachCompilation/ -k "snusbase_token=$snusbase_token"

Query without making API calls against local copy of the Breach Compilation

             h8mail -t targets.txt -bc ../Downloads/BreachCompilation/ -sk         

Features 
-------------
Email pattern matching (reg exp), useful for reading fromother tool output.
Loosey patterns for local searchs (“john.smith”, “evilcorp”)
Painless install. Available through pip, only requires  requests
Small and fast Alpine Dockerfile available
CLI or Bulk file-reading for targeting
Output to CSV file
Compatible with the “Breach Compilation” torrent scripts
Search .txt and .gz files locally using multiprocessing *Compatible with “Collection#1”
Get related emails
Chase and target related emails in ongoing search
Supports premium lookup services for advanced users
12 Regroup breach results for all targets and methods 
      
    


     



Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
