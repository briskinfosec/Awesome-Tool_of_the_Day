Turbolist3r
============
Turbolist3r is a fork of the sublist3r subdomain discovery tool. In addition to the original OSINT capabilties of sublist3r, turbolist3r automates some analysis of the results, with a focus on subdomain takeover. Turbolist3r queries public DNS servers for each discovered subdomain. If the subdomain exists (i.e. the resolver replied with an address), the answer is categorized as CNAME or A record. By examining A records, it is possible to discover potential penetration testing targets for a given domain. Likewise, the process of looking for subdomain takeovers is simple; view the discovered CNAME records and investigate any that point to applicable cloud services.

![Turbolist3r](https://www.briskinfosec.com//assets/tooloftheday/123.jpg)

Details:
============
|  Details | Description   |
| ------------ | ------------ |
|Tool Name:| Turbolist3r |
|Category :| Web Application|
|purpose  :| Turbolist3r is a fork of the sublist3r subdomain discovery tool. In addition to the original OSINT capabilties of sublist3r, turbolist3r automates some analysis of the results, with a focus on subdomain takeover.|
|License :| Opensource

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=VIou77qo4zk "Video")

Blog: 
--------------
Click Here for [Blog](https://www.briskinfosec.com/tooloftheday/toolofthedaydetail/Turbolist3r-Tool-Web-Application-Subdomain-Discover "Blog")

Installation
----------------
    Step 1: git clone https://github.com/fleetcaptain/Turbolist3r

    Step 2: cd Turbolist3r

    Step 3: pip install requirements.txt

    Step 4: python turbolist3r.py -d 
    
Usage:
----------------
    python turbolist3r.py -d vulnweb.com 

Commands And Usages
----------------
    d  --domain        Domain name to enumerate subdomains of
    -b --bruteforce    Enable the subbrute bruteforce module
    -p --ports         Scan the found subdomains against specific tcp ports
    -v --verbose       Enable the verbose mode and display results in realtime
    -t --threads       Number of threads to use for subbrute bruteforce
    -e --engines       Specify a comma-separated list of search engines
    -o --output        Save discovered domain names to specified text file
    -h --help          show the help message and exit
    -a --analyze        Do reverse DNS analysis and output results
    (none) --saverdns   Save reverse DNS analysis to specified file
    (none) --inputfile  Read domains from specified file, and use them for analysis
    (none) --debug      Print debug information during the analysis module (-a). Prints mostly raw DNS data, familarity with the DIG Linux DNS utility and it's output is helpful to interpret the debug output
    -r --resolvers     File with DNS servers to populate as resolvers. File must have only one server IP address per line and only IP addresses are accepted
    -q --quiet         Only print found domains and/or CNAME mappings. Note errors may be printed as well

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")