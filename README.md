## Burp Suite - Secret Finder (beta v0.1)

A Burp Suite extension to help pentesters to discover a apikeys,accesstoken and more sensitive data using a regolar expressions. SecretFinder process any HTTP response (support javascript file) and support Passive and Active scan. This extension has been developed by M'hamed Outaadi (@m4ll0k).

Add RegEx
---
- Download SecretFinder and Open it with any editor

![img](https://i.imgur.com/LBtfhkt.png)

Example
---

![main](https://i.imgur.com/unM06Hg.png)


Install
--

- download `SecretFinder`

`wget https://raw.githubusercontent.com/m4ll0k/BurpSuite-Secret_Finder/master/SecretFinder.py`

or

`git clone https://github.com/m4ll0k/BurpSuite-Secret_Finder.git`

- now open `Burp > Extender > Extensions > Add > set python and select file (SecretFinder.py)`

Requirements
--
- jython
- burpsuite
