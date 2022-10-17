 SSLyze
============
SSLyze can analyze the SSL/TLS configuration of a server by connecting to it, in order to ensure that it uses strong encryption settings (certificate, cipher suites, elliptic curves, etc.), and that it is not vulnerable to known TLS attacks (Heartbleed, ROBOT, OpenSSL CCS injection, etc.).

![SSLyze](https://www.briskinfosec.com//assets/tooloftheday/Copy_of_Briskinfosec_TOD_Latest_samples_179.jpg)


Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name |  SSLYZE |
|  Category | Network Security  |
|  Purpose | SSLyze is a fast and powerful SSL/TLS scanning tool and Python library  |
|  Licence |    Opensource|

Demo Video:
-----------------
Click Here for [Video](https://youtu.be/hxPW8Wg38DM "Video")

Blog: 
--------------
Click Here for [Blog](https://www.briskinfosec.com/tooloftheday/toolofthedaydetail/SSLYZE "Blog")

Quick Start:
----------------
On Windows, Linux (x86 or x64) and macOS, SSLyze can be installed directly via pip:

```python
$ pip install --upgrade pip setuptools wheel
$ pip install --upgrade sslyze
$ python -m sslyze www.yahoo.com www.google.com "[2607:f8b0:400a:807::2004]:443"
```

It can also be used via Docker:

```
$ docker run --rm -it nablac0d3/sslyze:5.0.0 www.google.com
```


Usage
------------
By default, SSLyze will check the server's scan results against Mozilla's recommended "intermediate" TLS configuration, and will return a non-zero exit code if the server is not compliant.

>$ python -m sslyze mozilla.com


**Key Features:**

- Focus on speed and reliability: SSLyze is a battle-tested tool that is used to reliably scan hundreds of thousands of servers every day.
- Easy to operationalize: SSLyze can be directly run from CI/CD, in order to continuously check a server against Mozilla's recommended TLS configuration.
- Fully documented Python API to run scans directly from any Python application, such as a function deployed to AWS Lambda.
- Support for scanning non-HTTP servers including SMTP, XMPP, LDAP, POP, IMAP, RDP, Postgres and FTP servers.
- Results of a scan can easily be saved to a JSON file for later processing.
- And much more!.

Links
----------------
:fa-youtube-play:  [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")

:fa-github:  [Github](https://github.com/briskinfosec "Github") 

:fa-globe: [Our Website](https://www.briskinfosec.com/ "Our Website")
