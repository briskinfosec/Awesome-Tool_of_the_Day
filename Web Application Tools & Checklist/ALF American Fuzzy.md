AFL American Fuzzy
============
 American fuzzy lop is security-oriented brute force fuzzer which performs a kind of complile-time instrumentation and genetic algorithms to automatically find the interesting test cases that trigger a new internal states in targeted binary programs. afl-fuzz will do the fuzzing operations automatically on the targeted binary program and it provides the interface in terminal which shows us how many crashes and hangs occurs and it will also expose some more interesting paths of the programs in run-time state while performing the automated security testing. 
 
![AFL American Fuzzy](https://www.briskinfosec.com//assets/tooloftheday/Tool_Of_the_day10.jpg)

Details:
============
|  Details | Description   |
| ------------ | ------------ |
|Tool Name:| AFL American Fuzzy|
|Category :| Web Application|
|purpose  : |Identifies bad exception handling, incorrect null handling etc.|
|License :| Opensource|

Demo Video:
-----------------
Click Here for [Video](https://youtu.be/NPylt5st7tw?list=PLOEp8ZXsJlIqqeyj3X5U2gr9OTFDA-TcC "Video")

Blog: 
--------------
Click Here for [Blog](https://www.briskinfosec.com/tooloftheday/toolofthedaydetail/AFL-American-Fuzzy-LOP-Tool-to--Identifies-bad-exception-handling-and-Incorrect-null-handling "Blog")

Installation
----------------
    apt-get install afl
 
Usage
---------
> If the target source file is available means we can compile the source with the binary instrumentation built-in for that we need to set the environment variables in our shell below with afl.

>Set gcc to compile the c source files and g++ for cpp source files.

    CC=afl-gcc

    CXX=afl-g++

>we need to create some directories for input dictionaries and output for the results of crashes, hangs and some interesting information leads to potential bugs from the binary programs.

     mkdir input output

>Put the dictionary file in input directory and the test results will be stored in output directory.

    afl-fuzz -i input -o output /path/to/binary_file @@

>@@ is a placeholder used by afl to insert the mutated payloads into the binary program.

>Perhaps if the source of binary is not available to compile afl offers experimental support for fast, on-the-fly instrumentation black-box binaries. In qemu_mode by providing -Q flag with afl-fuzz.

>You can use -t and -m to override the default timeout and memory limit for the executed process; rare examples of targets that may need these settings touched include compilers and video decoders.
Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
