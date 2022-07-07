SCILLA
============
Information Gathering tool - DNS / Subdomains / Ports / Directories enumeration 

![ ]()


Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name | SCILLA |
|  Category | OSINT |
|  Purpose |  Information Gathering tool - DNS / Subdomains / Ports / Directories enumeration  |
|  License |    Opensource |

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=kKFz_MG1aX4  "Video")


Blog:
--------------
Click Here for [Blog]( "Blog")

Installation
----------------
**Using Docker**

- docker build -t scilla .
- docker run scilla help

**Building from source**

------------
**Linux**

- git clone https://github.com/edoardottt/scilla.git
- cd scilla
- go get
- make linux (to install)
- Edit the ~/.config/scilla/keys.yaml file if you want to use api keys
- make unlinux (to uninstall)

**Windows** (executable works only in scilla folder. Alias?)
- git clone https://github.com/edoardottt/scilla.git
- cd scilla
- go get
- .\make.bat windows (to install)
- Create a keys.yaml file if you want to use api keys
- .\make.bat unwindows (to uninstall)


Examples
----------------
**DNS enumeration:**
- scilla dns -target target.domain
- scilla dns -oj output -target target.domain
- scilla dns -oh output -target target.domain
- scilla dns -ot output -target target.domain
- scilla dns -plain -target target.domain

**Subdomains enumeration:**
- scilla subdomain -target target.domain
- scilla subdomain -w wordlist.txt -target target.domain
- scilla subdomain -oj output -target target.domain
- scilla subdomain -oh output -target target.domain
- scilla subdomain -ot output -target target.domain
- scilla subdomain -i 400 -target target.domain
- scilla subdomain -i 4** -target target.domain
- scilla subdomain -c -target target.domain
- scilla subdomain -db -target target.domain
- scilla subdomain -plain -target target.domain
- scilla subdomain -db -no-check -target target.domain
- scilla subdomain -db -spyse -target target.domain
- scilla subdomain -db -vt -target target.domain

**Directories enumeration:**
- scilla dir -target target.domain
- scilla dir -w wordlist.txt -target target.domain
- scilla dir -oj output -target target.domain
- scilla dir -oh output -target target.domain
- scilla dir -ot output -target target.domain
- scilla dir -i 500,401 -target target.domain
- scilla dir -i 5**,401 -target target.domain
- scilla dir -c -target target.domain
- scilla dir -plain -target target.domain
- scilla dir -nr -target target.domain

**Ports enumeration:**
- Default (all ports, so 1-65635) scilla port -target target.domain
- Specifying ports range scilla port -p 20-90 -target target.domain
- Specifying starting port (until the last one) scilla port -p 20- -target target.domain
- Specifying ending port (from the first one) scilla port -p -90 -target target.domain
- Specifying single port scilla port -p 80 -target target.domain
- Specifying output format (json)scilla port -oj output -target target.domain
- Specifying output format (html)scilla port -oh output -target target.domain
- Specifying output format (txt)scilla port -ot output -target target.domain
- Specifying multiple ports scilla port -p 21,25,80 -target target.domain
- Specifying common ports scilla port -common -target target.domain
- Print only results scilla port -plain -target target.domain

**Full report:**
- Default (all ports, so 1-65635) scilla report -target target.domain
- Specifying ports range scilla report -p 20-90 -target target.domain
- Specifying starting port (until the last one) scilla report -p 20- -target target.domain
- Specifying ending port (from the first one) scilla report -p -90 -target target.domain
- Specifying single port scilla report -p 80 -target target.domain
- Specifying output format (json)scilla report -oj output -target target.domain
- Specifying output format (html)scilla report -oh output -target target.domain
- Specifying output format (txt)scilla report -ot output -target target.domain
- Specifying directories wordlist scilla report -wd dirs.txt -target target.domain
- Specifying subdomains wordlist scilla report -ws subdomains.txt -target target.domain
- Specifying status codes to be ignored in directories scanning scilla report -id 500,501,502 -target target.domain
- Specifying status codes to be ignored in subdomains scanning scilla report -is 500,501,502 -target target.domain
- Specifying status codes classes to be ignored in directories scanning scilla report -id 5**,4** -target target.domain
- Specifying status codes classes to be ignored in subdomains scanning scilla report -is 5**,4** -target target.domain
- Use also a web crawler for directories enumeration scilla report -cd -target target.domain
- Use also a web crawler for subdomains enumeration scilla report -cs -target target.domain
- Use also a public database for subdomains enumeration scilla report -db -target target.domain
- Specifying multiple ports scilla report -p 21,25,80 -target target.domain
- Specifying common ports scilla report -common -target target.domain
- No follow redirects scilla report -nr -target target.domain
- Use Spyse as subdomains source scilla report -db -spyse -target target.domain
- Use VirusTotal as subdomains source scilla report -db -vt -target target.domain


Links
----------------

 ![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")


 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 

  ![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")