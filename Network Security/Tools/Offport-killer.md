OFFPORT KILLER
============
The tool aims at automating the identification of potential services running behind ports identified manually either through manual scan or services running locally.

![OFFPORT KILLER](https://www.briskinfosec.com//assets/tooloftheday/Copy_of_Briskinfosec_TOD_Latest_samples.jpg)


Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name | OFFPORT KILLER |
|  Category | Network security  |
|  Purpose | The tool aims at automating the identification of potential services running behind ports identified manually either through manual scan or services running locally. |
|  License |    Opensource |

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=6LH2H59y7qk  "Video")


Blog:
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/OFFPORT-KILLER "Blog")

Installation
----------------

- git clone https://github.com/TH3xACE/OFFPORT_KILLER.git
- cd OFFPORT_KILLER
- ./OFFPORT_KILLER.sh

Usage
----------------
./OFFPORT_KILLER.sh -i inputfile.txt -r report.txt -e /tmp/

Options
----------------

- -i : input file (format IP:PORT)
- -r : report name (save the output)
- -h : help

Steps
----------------

1. Perform a manual port scanning (using nc, tcpdump or whatever) or identify services running locally.

3. Create a file with format IP:PORT (where IP is the target IP address and PORT is a port identified).

5. Run the tool with the file created using the argument -i.

Links
----------------

 ![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")


 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 

  ![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
