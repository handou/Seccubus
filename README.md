Seccubus V2 Read Me
===================
Seccubus automates regular vulnerability scans with vrious tools and aids 
security people in the fast analysis of its output, both on the first scan and 
on repeated scans.

On repeated scan delta reporting ensures that findings only need to be judged 
when they first appear in the scan results or when their output changes.

Seccubus 2.x is the only actively developed and maintained branch and all support 
for Seccubus V1 has officially been dropped. 

Seccubus V2 works with the following scanners:
* Nessus 4.x and 5.x (professional and home feed)
* Skipfish
* OpenVAS
* Medusa (local and remote)
* Nikto (local and remote)
* NMap (local and remote)
* SSLyze
* Medusa
* Burp Suite
* Qualys SSL labs

For more information visit [www.seccubus.com]

---

Release notes
=============

24-02-2015 - 2.14 - SSL labs API
================================
* #211 - Host filter now splits on / as well as . 

Bug Fixes
=========
* #205 - SSLlabs test uses the dev version of the API by default in stead of the prod version
* #206 - SSLlabs scanner does not honor coolOff period
* #207 - ssllabs - poodleTLS is incorrecly stating vuln status
* #208 - SSLlabs script uses wrong bitwise and operator :(
* #209 - SSLlabs scanner does not attach results bug
* #210 - SSLlabs scanner did not call process results bug
