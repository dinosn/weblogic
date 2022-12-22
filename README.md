## Weblogic exploits

A collection of some working exploits for weblogic envvironments. 
All work is based on http://tttang.com/archive/1768/ series with modifications to make the code working and tested. 

### T3.py
T3.py is CVE-2015-4582 and will work on 

* 10.3.6.0
* 12.1.2.0
* 12.1.3.0

Tested working, you need to modify YSO_PATH, ip and your cmd (base64 encode). Based on your ysoserial you might want to use Java < 12 as Java >=12 does not allow access to private fields of certain sensitive classes [https://github.com/frohoff/ysoserial/issues/136]. 
