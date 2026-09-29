# Security-Projects
Hands-on cybersecurity work by Gayathri Ramesh: a vulnerability assessment of an intentionally vulnerable lab machine, and write-ups of Capture The Flag (CTF) challenges. I'm a Computer Science graduate with a Data Science background, building practical security skills.

## What's inside

### `vulnerability-assessment/`
A vulnerability assessment of Metasploitable2, run in an isolated home lab (Kali Linux attacker VM and Metasploitable2 target on a host-only network, no external systems involved).

- 5 findings, including 3 rated Critical: an unauthenticated root shell (port 1524), the vsftpd 2.3.4 backdoor (CVE-2011-2523), and Samba remote command execution (CVE-2007-2447)
- Each finding covers severity, description, evidence, impact and remediation
- Every finding was verified manually rather than relying on scanner output alone
- Tools used: nmap, searchsploit, smbclient, netcat

### `picoctf-writeups/`
Write-ups of CTF challenges from CyLab Security Academy (Carnegie Mellon's picoCTF platform), covering:

- **General Skills:** SSH (`01_superSSH_generalskills`), binary inspection with `strings` (`04_stringsit_generalskills`)
- **Cryptography:** ROT13 (`02_mod26_cryptography`)
- **Web Exploitation:** locating a flag split across HTML, CSS and JS via View Source and DevTools (`03_inspector_webexploitation`), finding a hidden path via `robots.txt` (`05_wherearetherobots_webexploitation`)
- **Forensics:** extracting a flag hidden in the text elements of an SVG image file by reading its raw XML content (`06_enhance_forensics`)

Each write-up includes the approach taken, difficulties faced along the way, tools used, and what I learned.

## Tools and platforms
Kali Linux, VirtualBox, nmap, searchsploit, smbclient, netcat, CyberChef, CyLab Security Academy

## Note
All testing was done in my own isolated home lab or on platforms built for legal practice. Nothing here targets real systems.

