OWASP AMASS TOOL
============

The OWASP Amass Project performs network mapping of attack surfaces and external asset discovery using open source information gathering and active reconnaissance techniques.

![ ](https://briskinfosec.com//assets/tooloftheday/119.jpg)


Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name | OWASP AMASS TOOL |
|  Category | Network security  |
|  Purpose |  The OWASP Amass Project is written in go which is much faster than python and it performs network mapping of attack surfaces and external asset discovery using open source information gathering and active reconnaissance techniques.You can also perform scripting with the amass engine for greater control over the enumeration process.You can perform in-depth DNS, ASN numbers and subdomain enumeration and also other assets owned by an organization using amass.  |
|  License |    Opensource |

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=TYP07_34PXo "Video")


Blog:
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/OWASP-Amass-Tool-for-Network-Mapping-of-Attack-Surface "Blog")

Installation
----------------

If you are in ubuntu system for installation:

-  snap install amass

For any other debian distribution:

 - apt-get install amass

You can see here for the installation instructions :

    https://github.com/OWASP/Amass/blob/master/doc/install.md

Usecases
----------------

Type **amass -h** for help

In general amass comes with 5-sub commands. They are:

- **amass intel** - Discover targets for enumerations
- **amass enum**  - Perform enumerations and network mapping
- **amass viz**   - Visualize enumeration results
- **amass track** - Track differences between enumerations
- **amass db**    - Manipulate the Amass graph database
- **amass dns**   - Resolve DNS names at high performance

Supports 55 sources, such as APIs and websites, at the time of writing as part of its subdomain discovery and information gathering techniques. These can be listed using the following command:

- **amass enum -list**

Then, it will list the sources for gathering the information.

**Amass intel**
------------

The intel subcommand can help you discover additional root domain names associated with the organization you are investigating. The data source sections of the configuration file are utilized by this subcommand in order to obtain passive intelligence, such as reverse whois information.

- **Amass intel -h**

Amass enum
------------

This subcommand will perform DNS enumeration and network mapping while populating the selected graph database. All the setting available in the configuration file are relevant to this subcommand.

Amass viz
------------

create enlightening network graph visualizations that add structure to the information gathered. This subcommand only leverages the 'output_directory' and remote graph database settings from the configuration file.

The files generated for visualization are created in the current working directory and named amass_TYPE

This sub-command will represent the DNS and Infrastructure findings in graph view like the maltego tool.

Amass track
------------

Shows differences between enumerations that included the same target(s) for monitoring a target's attack surface. This subcommand only leverages the 'output_directory' and remote graph database settings from the configuration file.

Amass db
------------


Performs viewing and manipulation of the graph database. This subcommand only leverages the 'output_directory' and remote graph database settings from the configuration file.

Amass has several files that it outputs during an enumeration (e.g. the log file). If you are not using a database server to store the network graph information, then Amass creates a file based graph database in the output directory. These files are used again during future enumerations, and when leveraging features like tracking and visualization.

By default, the output directory is created in the operating system default root directory to use for user-specific configuration data and named amass. If this is not suitable for your needs, then the subcommands can be instructed to create the output directory in an alternative location using the '-dir' flag.

If you decide to use an Amass configuration file, it will be automatically discovered when put in the output directory and named config.ini.

**A brief user guide and tutorial of amass :**

https://github.com/OWASP/Amass/blob/master/doc/user_guide.md

https://github.com/OWASP/Amass/blob/master/doc/tutorial.md


Links
----------------

 ![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")


 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 

  ![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")