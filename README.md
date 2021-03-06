# Strapi v4.1.12

### Vulnerability Explanation:
Strapi v4.1.12 has an Unrestricted File Upload vulnerability that allows an attacker to successfully upload files containing malicious content to the system and execute.

### Payload :
https://github.com/bypazs/GrimTheRipper/blob/main/GrimTheRipperTeam.pdf

### Steps to attack:
1. Log in with a user that has permission to upload files.
2. Click on the "Media Library" menu, then click on "+ Add new assets".
3. Click on the "Browse files: button, and then select the prepared file containing malicious content.
4. Then click on the "Upload 1 asset to the library" button to upload the file to the system.
5. Click edit in the corner of the file and click copy link.
6. Paste the link to a new tab, it will show that the payload XSS was executed.

### Tested on:
1.  Strapi Version 4.1.12
2.  Google Chrome Version 102.0.5005.61 (Official Build) (64-bit)

### Author:
Grim The Ripper Team by SOSECURE Thailand
