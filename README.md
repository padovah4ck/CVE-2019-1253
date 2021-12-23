# CVE-2019-1253
Original Poc sent to MSRC.   
This issue has been fixed with September 2019 "Tuesday" regular update.   
Assigned to CVE-2019-1253 - Windows Elevation of Privilege Vulnerability.  

https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2019-1253  

There are two PoCs: the one that I've originally sent to MSRC is under "AppxExploit_Edge" directory.    
AppxExploit_Edge PoC works very well but only for Windows 10 (all versions) that are not patched with September (2019) update.

The other PoC is based on Cortana, under "AppxExploit_Cortana" directory, and it was experimentally and never sent to MSRC.  
However, the interesting thing about this, is that it does work with Windows Server 2019 and this one gives USER FULL access, although is a little bit unstable due to a race condition but it usually always works at first time.    

Read the README inside the directory project, it should be self explanatory.  
I suggest you to use VS2017 (or whatever you like).  

There is also a DOS version of the Windows 10 exploit based on Edge, courtesy of [@decoder-it](https://github.com/decoder-it)

Attached a couple of images 

![Screenshot](eop_1.JPG?raw=true)

![Screenshot](eop_2.JPG?raw=true)

---

![Beer](https://icons.iconarchive.com/icons/flat-icons.com/flat/48/Beer-icon.png)  [Buy me a beer if you like ;-)](https://www.buymeacoffee.com/padovah4ck)
