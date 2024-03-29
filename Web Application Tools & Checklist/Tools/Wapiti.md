Wapiti
============

![Wapiti](https://www.briskinfosec.com/assets/tooloftheday/122.jpg)

# Requirements
In order to work correctly, Wapiti needs :
- Python 3.x where x is >= 8 (3.8, 3.9, 3.10...)
- httpx ( https://www.python-httpx.org/ )
- BeautifulSoup ( http://www.crummy.com/software/BeautifulSoup/ )
- yaswfp ( https://github.com/facundobatista/yaswfp )
- tld ( https://github.com/barseghyanartur/tld )
- Mako ( https://www.makotemplates.org/ )

# How it works:
Wapiti works as a "black-box" vulnerability scanner, that means it won't study the source code of web applications but will work like a fuzzer, scanning the pages of the deployed web application, extracting links and forms and attacking the scripts, sending payloads and looking for error messages, special strings or abnormal behaviors.

# General features:
- Generates vulnerability reports in various formats (HTML, XML, JSON, TXT, CSV).
- Can suspend and resume a scan or an attack (session mechanism using sqlite3 databases).
- Can give you colors in the terminal to highlight vulnerabilities.
- Different levels of verbosity.
- Fast and easy way to activate/deactivate attack modules.
- Adding a payload can be as easy as adding a line to a text file.
- Configurable number of concurrent tasks to perform HTTP requests.

# Browsing features:
- Support HTTP, HTTPS and SOCKS5 proxies.
- Authentication on the target via several methods : Basic, Digest, NTLM or GET/POST on login forms.
- Ability to restrain the scope of the scan (domain, folder, page, url).
- Automatic removal of one or more parameters in URLs.
- Multiple safeguards against scan endless-loops (for example, limit of values for a parameter).
- Possibility to set the first URLs to explore (even if not in scope).
- Can exclude some URLs of the scan and attacks (eg: logout URL).
- Import cookies from your Chrome or Firefox browser or using the wapiti-getcookie tool.
- Can activate / deactivate SSL certificates verification.
- Extract URLs from Flash SWF files.
- Try to extract URLs from javascript (very basic JS interpreter).
- HTML5 aware (understand recent HTML tags).
- Several options to control the crawler behavior and limits.
- Skipping some parameter names during attack.
- Setting a maximum time for the scan process.
- Adding some custom HTTP headers or setting a custom User-Agent

# Supported attacks:
- SQL Injections (Error based, boolean based, time based) and XPath Injections
- Cross Site Scripting (XSS) reflected and permanent
- File disclosure detection (local and remote include, require, fopen, readfile...)
- Command Execution detection (eval(), system(), passtru()...)
- XXE (Xml eXternal Entity) injection
- CRLF Injection
- Search for potentially dangerous files on the server (thank to the Nikto db)
- Bypass of weak htaccess configurations
- Search for copies (backup) of scripts on the server
- Shellshock
- Folder and file enumeration (DirBuster like)
- Server Side Request Forgery (through use of an external Wapiti website)
- Open Redirects
- Detection of uncommon HTTP methods (like PUT)
- Basic CSP Evaluator
- Brute Force login form (using a dictionary list)
- Checking HTTP security headers
- Checking cookie security flags (secure and httponly flags)
- Cross Site Request Forgery (CSRF) basic detection
- Fingerprinting of web applications using the Wappalyzer database
- Enumeration of Wordpress and Drupal modules
- Subdomain takeovers detection
- Log4Shell (CVE-2021-44228) detection

# Module names:
- backup (Search copies of scripts and archives on the web server)
- brute_login_form (Brute Force login form using a dictionary list)
- buster (DirBuster like module)
- cookieflags (Checks Secure and HttpOnly flags)
- crlf (CR-LF injection in HTTP headers)
- csp (Detect lack of CSP or weak CSP configuration)
- csrf (Detects forms not protected against CSRF or using weak anti-CSRF tokens)
- drupal_enum (Detect version of Drupal)
- exec (Code execution or command injection)
- file (Path traversal, file inclusion, etc)
- htaccess (Misconfigured htaccess restrictions)
- http_header (Check HTTP security headers)
- log4shell (Detects websites vulnerable to CVE-2021-44228)
- methods (Look for uncommon availables HTTP methods like PUT)
- nikto (Look for known vulnerabilities by testing URL existence and checking responses)
- permanentxss (Rescan the whole target after the xss module execution looking for previously tainted payloads)
- redirect (Open Redirects)
- shellshock (Test Shellshock attack, see Wikipedia)
- sql (Error-based and boolean-based SQL injection detection)
- ssrf (Server Side Request Forgery)
- takeover (Subdomain takeover)
- timesql (SQL injection vulnerabilities detected with time-based methodology)
- wapp (Not an attack module, retrieves web technologies with versions and categories in use on the target)
- wp_enum (Enumerate plugins and themes on a Wordpress website)
- xss (XSS injection module)
- xxe (XML External Entity attack)

# How to get the best results:
To find more vulnerabilities (as some attacks are error-based), you can modify your webserver configurations.
For example, you can set the following values in your PHP configuration :

    safe_mode = Off
    display_errors = On (recommended)
    magic_quotes_gpc = Off
    allow_url_fopen = On
    mysql.trace_mode = On


Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=VSYHkepm_JM "Video")

Blog: 
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/Wapiti-Tool-for-web-application-security-auditor "Blog")

Links
----------------
![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")
 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 
![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")
