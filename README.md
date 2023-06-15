# PoC for CVE-2023-22960 
[![Python](https://img.shields.io/badge/Python-%E2%89%A5%203.6-yellow.svg)](https://www.python.org/) 
<img src="https://img.shields.io/badge/Developed%20on-kali%20linux-blueviolet">
[![License](https://img.shields.io/badge/license-MIT-red.svg)](https://github.com/t3l3machus/CVE-2023-22960/blob/main/LICENSE) 
## Details
PoC for CVE-2023-22960 that I discovered. This vulnerability allows an attacker to bypass the credentials brute-force prevention mechanism of the Embedded Web Server interface of all Lexmark printer models that have a firmware version released before 01/2023. This issue affects both username-password and PIN authentication.

**Official security advisory** -> https://publications.lexmark.com/publications/security-alerts/CVE-2023-22960.pdf

**PoC tested against**:
 - Lexmark MX622adhe 
 - Lexmark CX735adse 
 - Lexmark MX521ade

#### Video Presentation
In this video I demonstrate the issue as well as how to write an http(s) login bruteforce script with Python.  
https://www.youtube.com/watch?v=HuAqTScr_3s

## Preview

Without the brute-force prevention bypass:  
![image](https://user-images.githubusercontent.com/75489922/214288009-d0cda79b-e604-478a-9bbc-39175c20a6ab.png)


Applying the brute-force prevention bypass:  
![image](https://user-images.githubusercontent.com/75489922/214286428-fb2cc7b3-9c58-4aed-a343-2d66610ca407.png)

