![visitor badge](https://visitor-badge.glitch.me/badge?page_id=shreyaschavhan.oscp-pre-preparation-plan-and-notes&left_text=Views)

`Note: These are my notes for personal reference!`

# 𝐎𝐒𝐂𝐏 𝐏𝐫𝐞-𝐏𝐫𝐞𝐩𝐚𝐫𝐚𝐭𝐢𝐨𝐧 𝐏𝐥𝐚𝐧 𝐚𝐧𝐝 𝐍𝐨𝐭𝐞𝐬



> - `21st March 2022` : Start Date
> - `19th Sept 2022` : Expected End Date
> - `180 days` : Goal

---
<img src="https://user-images.githubusercontent.com/68887544/159728391-b9c52bda-b711-4c63-aa52-3886a7ab54c1.png">

## ⁍ 𝐓𝐚𝐛𝐥𝐞 𝐨𝐟 𝐂𝐨𝐧𝐭𝐞𝐧𝐭𝐬

- Resources:
> - [Pre-requisites](#𝐏𝐫𝐞-𝐫𝐞𝐪𝐮𝐢𝐬𝐢𝐭𝐞𝐬)
> - [Getting Comfortable with Kali Linux](#𝐆𝐞𝐭𝐭𝐢𝐧𝐠-𝐂𝐨𝐦𝐟𝐨𝐫𝐭𝐚𝐛𝐥𝐞-𝐰𝐢𝐭𝐡-𝐊𝐚𝐥𝐢-𝐋𝐢𝐧𝐮𝐱)
> - [Command Line Fun](#𝐂𝐨𝐦𝐦𝐚𝐧𝐝-𝐋𝐢𝐧𝐞-𝐅𝐮𝐧)
> - [Practical Tools](#𝐏𝐫𝐚𝐜𝐭𝐢𝐜𝐚𝐥-𝐓𝐨𝐨𝐥𝐬)
> - [Bash Scripting](#𝐁𝐚𝐬𝐡-𝐒𝐜𝐫𝐢𝐩𝐭𝐢𝐧𝐠)
> - [Passive Information Gathering](#𝐏𝐚𝐬𝐬𝐢𝐯𝐞-𝐈𝐧𝐟𝐨𝐫𝐦𝐚𝐭𝐢𝐨𝐧-𝐆𝐚𝐭𝐡𝐞𝐫𝐢𝐧𝐠)
> - [Active Information Gathering](#𝐀𝐜𝐭𝐢𝐯𝐞-𝐈𝐧𝐟𝐨𝐫𝐦𝐚𝐭𝐢𝐨𝐧-𝐆𝐚𝐭𝐡𝐞𝐫𝐢𝐧𝐠)
> - [Vulnerability Scanning](#𝐕𝐮𝐥𝐧𝐞𝐫𝐚𝐛𝐢𝐥𝐢𝐭𝐲-𝐒𝐜𝐚𝐧𝐧𝐢𝐧𝐠)
> - [Web Application Attacks](#𝐖𝐞𝐛-𝐀𝐩𝐩𝐥𝐢𝐜𝐚𝐭𝐢𝐨𝐧-𝐀𝐭𝐭𝐚𝐜𝐤𝐬)
> - [Buffer Overflow](#𝐁𝐮𝐟𝐟𝐞𝐫-𝐎𝐯𝐞𝐫𝐟𝐥𝐨𝐰)
> - [Client-side Attacks](#𝐂𝐥𝐢𝐞𝐧𝐭-𝐬𝐢𝐝𝐞-𝐀𝐭𝐭𝐚𝐜𝐤𝐬)
> - [Locating Public Exploits](#𝐋𝐨𝐜𝐚𝐭𝐢𝐧𝐠-𝐏𝐮𝐛𝐥𝐢𝐜-𝐄𝐱𝐩𝐥𝐨𝐢𝐭𝐬)
> - [Antivirus Evasion](#𝐀𝐧𝐭𝐢𝐯𝐢𝐫𝐮𝐬-𝐄𝐯𝐚𝐬𝐢𝐨𝐧)
> - [Privilege Escalation](#𝐏𝐫𝐢𝐯𝐢𝐥𝐞𝐠𝐞-𝐄𝐬𝐜𝐚𝐥𝐚𝐭𝐢𝐨𝐧)
> - [Password Attacks](#𝐏𝐚𝐬𝐬𝐰𝐨𝐫𝐝-𝐀𝐭𝐭𝐚𝐜𝐤𝐬)
> - [Port Redirection and Tunneling](#𝐏𝐨𝐫𝐭-𝐑𝐞𝐝𝐢𝐫𝐞𝐜𝐭𝐢𝐨𝐧-𝐚𝐧𝐝-𝐓𝐮𝐧𝐧𝐞𝐥𝐢𝐧𝐠)
> - [Active Directory Attacks](#𝐀𝐜𝐭𝐢𝐯𝐞-𝐃𝐢𝐫𝐞𝐜𝐭𝐨𝐫𝐲-𝐀𝐭𝐭𝐚𝐜𝐤𝐬)
> - [The Metasploit Framework](#𝐓𝐡𝐞-𝐌𝐞𝐭𝐚𝐬𝐩𝐥𝐨𝐢𝐭-𝐅𝐫𝐚𝐦𝐞𝐰𝐨𝐫𝐤)
> - [Powershell Empire](#𝐏𝐨𝐰𝐞𝐫𝐬𝐡𝐞𝐥𝐥-𝐄𝐦𝐩𝐢𝐫𝐞)
> - [Trying Harder: The Labs](#𝐓𝐫𝐲𝐢𝐧𝐠-𝐇𝐚𝐫𝐝𝐞𝐫-𝐓𝐡𝐞-𝐋𝐚𝐛𝐬)

- [Strategy](#𝐒𝐭𝐫𝐚𝐭𝐞𝐠𝐲)  


## 𝐏𝐫𝐞-𝐫𝐞𝐪𝐮𝐢𝐬𝐢𝐭𝐞𝐬

> - Solid understanding of TCP/IP networking
>   - TCP/IP Fundamentals 
>     - [Part I](https://youtu.be/xdQ9sgpkrX8)
>     - [Part II](https://youtu.be/NdvWI6RH1eo)
> - Familiarity with basic Bash and/or Python scripting
>   - Python Books:
>     - [Learn Python 3 the hard way](https://g.co/kgs/dtmGpu) 
>     - [Learn More Python 3 the hard way](https://g.co/kgs/iqHMau)
>     - [Black Hat Python](https://g.co/kgs/xmdQNE)
>     - [Violent Python](https://g.co/kgs/vJfCsm)
>       - [Violent Python Codes in Python 3](https://github.com/EONRaider/violent-python3)
>   - Vidoes: 
>     - [The Complete Python Hacking Course: Beginner To Advance! (2021)](https://youtu.be/0NQ2aMxBYNE)
>       - Broken Link Update : [Access it here](https://web.archive.org/web/20210222183051/https://www.youtube.com/watch?v=0NQ2aMxBYNE&feature=youtu.be)
>     - [The Complete Python Hacking Course Playlist](https://youtube.com/playlist?list=PL9bcYdRTwTIme7BckMbAd55KdwEzeSe9m)
>   
- [Python Notes for OSCP](https://github.com/shreyaschavhan/python-for-oscp)

```
Update (16th Oct 2022): 

One of the above python course wasn't available anymore. But you can use waybackmachine to access it again.

A quick tip for any broken link that might exist here in this repository:
- Use Wayback machine
```

```
Thoughts:

`Learn python 3 the hard way` is the best book for python according to me!
```

```
Estimated Time: 24 hours
```

## 𝐆𝐞𝐭𝐭𝐢𝐧𝐠 𝐂𝐨𝐦𝐟𝐨𝐫𝐭𝐚𝐛𝐥𝐞 𝐰𝐢𝐭𝐡 𝐊𝐚𝐥𝐢 𝐋𝐢𝐧𝐮𝐱

> - [Installing Kali Linux on VMware](https://youtu.be/UbGYDDnFAEg)
> - [Kali Linux on Windows in 5 mins](https://youtu.be/AfVH54edAHU)
> - [Linux for Hackers by NetworkChuck](https://youtube.com/playlist?list=PLIhvC56v63IJIujb5cyE13oLuyORZpdkL)
> - [Linux for beginners (Hindi) by Codewithharry](https://youtu.be/_tCY-c-sPZc)
> - [Linux for Hackers (Kali Linux Tutorial)](https://youtu.be/lZAoFs75_cs)
> - [Kali Linux Training](https://kali.training/)
> - [Linux Commands cheatsheet](https://github.com/shreyaschavhan/linux-commands-cheatsheet)


- Should learn `(imp)`: 
```
- man
- apropos
- ls
- cd
- pwd
- mkdir
- rm
- which
- locate
- find
- ssh
- grep
- apt

```

```
Estimated Time: 8 hours
```

## 𝐂𝐨𝐦𝐦𝐚𝐧𝐝 𝐋𝐢𝐧𝐞 𝐅𝐮𝐧

> - [Linux Commands cheatsheet](https://github.com/shreyaschavhan/linux-commands-cheatsheet)
> - Book: [The Linux Command Line](https://g.co/kgs/7gC3DZ)
> - Practice:
>   - [Overthewire Bandit](https://overthewire.org/wargames/bandit/)
>   - [Cmdchallenge](https://cmdchallenge.com/)
> - Vim Tutorial: https://youtu.be/IiwGbcd8S7I


- Should learn:
```
- Environment Variables in Bash
- grep
- awk
- cut
- sed
- comm
- diff
- vimdiff
- ping
- bg
- fg
- jobs
- kill
- ps
- wget
- curl
- axel
```

- Text Editors you should be familiar with:
```
- nano
- vi(m)
```

```
Excepted time (without practice): 12 hours 
```

## 𝐏𝐫𝐚𝐜𝐭𝐢𝐜𝐚𝐥 𝐓𝐨𝐨𝐥𝐬

- Official Syllabus Tools

```
- Netcat
- Socat
- Powershell
- Powercat
- Wireshark
- Tcpdump
```

- Enumeration

```
AutoRecon — https://github.com/Tib3rius/AutoRecon
nmapAutomator — https://github.com/21y4d/nmapAutomator
Reconbot — https://github.com/Apathly/Reconbot
Raccoon — https://github.com/evyatarmeged/Raccoon
RustScan — https://github.com/RustScan/RustScan
BashScan — https://github.com/astryzia/BashScan
```

- Web Related

```
Dirsearch — https://github.com/maurosoria/dirsearch
GoBuster — https://github.com/OJ/gobuster
Recursive GoBuster — https://github.com/epi052/recursive-gobuster
wfuzz — https://github.com/xmendez/wfuzz
goWAPT — https://github.com/dzonerzy/goWAPT
ffuf — https://github.com/ffuf/ffuf
Nikto — https://github.com/sullo/nikto
dirb — https://tools.kali.org/web-applications/dirb
dirbuster — https://tools.kali.org/web-applications/dirbuster
feroxbuster — https://github.com/epi052/feroxbuster
FinalRecon — https://github.com/thewhiteh4t/FinalRecon
```

- Network tools:
```
Impacket (SMB, psexec, etc) — https://github.com/SecureAuthCorp/impacket
```

- File Transfers:
```
updog — https://github.com/sc0tfree/updog
```

- Wordlists:

```
SecLists — https://github.com/danielmiessler/SecLists
```

- Payload Generators:

```
Reverse Shell Generator — https://github.com/cwinfosec/revshellgen
Windows Reverse Shell Generator — https://github.com/thosearetheguise/rev
MSFVenom Payload Creator — https://github.com/g0tmi1k/msfpc
```

- Php reverse shell:

```
Windows PHP Reverse Shell — https://github.com/Dhayalanb/windows-php-reverse-shell
PenTestMonkey Unix PHP Reverse Shell — http://pentestmonkey.net/tools/web-shells/php-reverse-shell
```

- Terminal Related:

```
tmux — https://tmuxcheatsheet.com/ (cheat sheet)
tmux-logging — https://github.com/tmux-plugins/tmux-logging
Oh My Tmux — https://github.com/devzspy/.tmux
screen — https://gist.github.com/jctosta/af918e1618682638aa82 (cheat sheet)
Terminator — http://www.linuxandubuntu.com/home/terminator-a-linux-terminal-emulator-with-multiple-terminals-in-one-window
vim-windir — https://github.com/jtpereyda/vim-windir
```

- Exploits:
```
Exploit-DB — https://www.exploit-db.com/
Windows Kernel Exploits — https://github.com/SecWiki/windows-kernel-exploits
AutoNSE — https://github.com/m4ll0k/AutoNSE
Linux Kernel Exploits — https://github.com/lucyoa/kernel-exploits
```

- Password Brute Forcer:

```
BruteX — https://github.com/1N3/BruteX
Hashcat — https://hashcat.net/hashcat/
John the Ripper — https://www.openwall.com/john/
```

- Post Exploitation / Privilege Escalation

```
LinEnum — https://github.com/rebootuser/LinEnum
linprivchecker —https://www.securitysift.com/download/linuxprivchecker.py
Powerless — https://github.com/M4ximuss/Powerless
PowerUp — https://github.com/HarmJ0y/PowerUp
Linux Exploit Suggester — https://github.com/mzet-/linux-exploit-suggester
Windows Exploit Suggester — https://github.com/bitsadmin/wesng
Windows Privilege Escalation Awesome Scripts (WinPEAS) — https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite/tree/master/winPEAS
CHECK THE VERSION NUMBER!!! Linux Privilege Escalation Awesome Script (LinPEAS) — https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite/tree/master/linPEAS
GTFOBins (Bypass local restrictions) — https://gtfobins.github.io/
Get GTFOBins — https://github.com/CristinaSolana/ggtfobins
sudo_killer — https://github.com/TH3xACE/SUDO_KILLER
WADComs — https://wadcoms.github.io/
LOLBAS — https://lolbas-project.github.io/
```

- Buffer Overflow Practice
```
Vulnserver for Windows — https://github.com/stephenbradshaw/vulnserver
Vulnserver for Linux — https://github.com/ins1gn1a/VulnServer-Linux
Tib3rius TryHackMe BOF — https://tryhackme.com/jr/bufferoverflowprep
```

- Privilege Escalation Practice
```
Local Privilege Escalation Workshop — https://github.com/sagishahar/lpeworkshop
Linux Privilege Escalation — https://www.udemy.com/course/linux-privilege-escalation/
Windows Privilege Escalation — https://www.udemy.com/course/windows-privilege-escalation/
```


> - Netcat 
>   - [Netcat tutorial by networkchuk](https://youtu.be/bXCeFPNWjsM)
> - [PowerShell Learning Resources](https://docs.microsoft.com/en-us/powershell/scripting/learn/more-powershell-learning?view=powershell-7)
> - [PowerShell for Pentesting In Kali Linux](https://www.offensive-security.com/offsec/kali-linux-powershell-pentesting/)
> - Hands on Challenges for learning PowerShell:
>   - underthewire.tech: https://underthewire.tech/wargames.htm
>   - codewars: https://www.codewars.com/

```
Expected Tools Overview: 12 hours
```
## 𝐁𝐚𝐬𝐡 𝐒𝐜𝐫𝐢𝐩𝐭𝐢𝐧𝐠

> - Practice:
>   - [Bash Scripting Practice on Hackerrank](https://www.hackerrank.com/domains/shell?filters%5Bstatus%5D%5B%5D=unsolved&filters%5Bstatus%5D%5B%5D=solved&filters%5Bsubdomains%5D%5B%5D=bash)
>   - https://www.learnshell.org/
> - Book:
>   - [Shell Scripting: How to Automate Command Line Tasks Using...](https://g.co/kgs/LW4kQy)

```
Expected Time: 4 hours
```

## 𝐏𝐚𝐬𝐬𝐢𝐯𝐞 𝐈𝐧𝐟𝐨𝐫𝐦𝐚𝐭𝐢𝐨𝐧 𝐆𝐚𝐭𝐡𝐞𝐫𝐢𝐧𝐠

```
- Website Recon
- Whois Enumeration
- Google hacking : https://www.exploit-db.com/google-hacking-database
- Netcraft
- Recon-ng : https://github.com/lanmaster53/recon-ng
- Open source code
- Shodan
- Security Headers Scanner
- SSL Server Test
- Pastebin
- User information Gathering
- Email Harvesting
- Stack Overflow
- OSINT Framework
- Maltego
```

```
Expected time: 30 mins
```

## 𝐀𝐜𝐭𝐢𝐯𝐞 𝐈𝐧𝐟𝐨𝐫𝐦𝐚𝐭𝐢𝐨𝐧 𝐆𝐚𝐭𝐡𝐞𝐫𝐢𝐧𝐠

```
- DNS Enumeration
  - Forward Lookup
  - Reverse Lookup
  - DNS Zone Transfers
  - Tools:
    - DNSrecon
    - DNSenum
- Port Scanning
  - TCP Scanning
  - UDP Scanning
  - Nmap: 
    - https://nmap.org/book/toc.html
    - https://www.amazon.com/Nmap-Network-Scanning-Official-Discovery/dp/0979958717
    - https://blog.zsec.uk/nmap-rtfm/
  - Masscan
- SMB Enumeration
- NFS Enumeration
- SMTP Enumeration
- SNMP Enumeration
```

```
Expected Time: 12 hours
```

## 𝐕𝐮𝐥𝐧𝐞𝐫𝐚𝐛𝐢𝐥𝐢𝐭𝐲 𝐒𝐜𝐚𝐧𝐧𝐢𝐧𝐠

```
- Vulnerability Scanning using Nessus
- Vulnerability Scanning using Nmap
```

```
Expected Time: 4 hours
```

## 𝐖𝐞𝐛 𝐀𝐩𝐩𝐥𝐢𝐜𝐚𝐭𝐢𝐨𝐧 𝐀𝐭𝐭𝐚𝐜𝐤𝐬

- Web Tools:
```
- DIRB: http://dirb.sourceforge.net/
- Dirsearch: https://github.com/maurosoria/dirsearch
- Dirbuster: https://tools.kali.org/web-applications/dirbuster
- Gobuster: https://github.com/OJ/gobuster
- Wfuzz: https://github.com/xmendez/wfuzz
- ffuf: https://github.com/ffuf/ffuf
- Burpsuite
- Nikto
- HTTPIe https://httpie.io/
```

- Practice:
> - Metasploitable 2
> - OWASP Juice Shop
> - Overthewire Natas
> - Web Security Academy
> - https://www.hackthissite.org/

```
Expected Time: 30 days
```

## 𝐁𝐮𝐟𝐟𝐞𝐫 𝐎𝐯𝐞𝐫𝐟𝐥𝐨𝐰

- Blogs:
> - [Buffer Overflows Made Easy](https://tcm-sec.com/buffer-overflows-made-easy/)
> - [Exploit writing tutorial part 1 : Stack Based Overflows](https://web.archive.org/web/20220228234520/https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/) 
> - [Exploit writing tutorial part 2 : Stack Based Overflows – jumping to shellcode](https://web.archive.org/web/20220228234628/https://www.corelan.be/index.php/2009/07/23/writing-buffer-overflow-exploits-a-quick-and-basic-tutorial-part-2/)
> - [What is Buffer Overflow? — TryHackMe: Buffer Overflow Prep Walkthrough](https://ahoner.medium.com/what-is-buffer-overflow-tryhackme-buffer-overflow-prep-walkthrough-9e2629a6b5b9)
> - [Buffer Overflow personal cheatsheet](https://liodeus.github.io/2020/08/11/bufferOverflow.html)
> - [Easy OSCP Bufferoverflow Preparation](https://hum4ng0d.github.io/OSCP-Easy-Bufferoverflow/)
> - [The Braindead Buffer Overflow Guide to Pass the OSCP Blindfolded](https://boschko.ca/braindead-buffer-overflow-guide-to-pass-the-oscp-blindfolded/)
> - [Simplifying Buffer Overflows for OSCP](https://appsecradar.net/posts/simplifying-buffer-overflows-for-oscp/)
> - [OSCP  Buffer Overflow Guide (Windows)](https://alomancy.gitbook.io/guides/guides/bof)
>


- Practice:
```
1. https://tryhackme.com/room/oscpbufferoverflowprep
2. protostar on vulnhub
3. vulnserver
4. Brainpan on vulnhub
5. warFTP
6. miniserv
7. https://overthewire.org/wargames/behemoth/
8. https://overthewire.org/wargames/narnia/
9. Brainpan 1: https://www.vulnhub.com/entry/brainpan-1,51/
10. Pinky’s Palace version 1: https://www.vulnhub.com/entry/pinkys-palace-v1,225/
11. Stack Overflows for Beginners: https://www.vulnhub.com/entry/stack-overflows-for-beginners-101,290/
12. SmashTheTux: https://www.vulnhub.com/entry/smashthetux-101,138/
13. Pandora’s Box: https://www.vulnhub.com/entry/pandoras-box-1,111/

```

- Windows Binaries (Recommend that you run these on Windows 7/XP 32 bit):
```
Vulnserver: https://samsclass.info/127/proj/vuln-server.htm
Minishare 1.4.1: https://www.exploit-db.com/exploits/636
Savant Web Server 3.1: https://www.exploit-db.com/exploits/10434
Freefloat FTP Server 1.0: https://www.exploit-db.com/exploits/40673
Core FTP Server 1.2: https://www.exploit-db.com/exploits/39480
WarFTP 1.65: https://www.exploit-db.com/exploits/3570
VUPlayer 2.4.9: https://www.exploit-db.com/exploits/40018
```

- Linux Binaries
```
Linux Buffer Overflow: https://samsclass.info/127/proj/lbuf1.htm
```

- Videos:

> - [Buffer Overflows made easy](https://www.youtube.com/playlist?list=PLLKT__MCUeix3O0DPbmuaRuR_4Hxo4m3G)
> - [Buffer Overflows made easy (2022 Edition)](https://youtu.be/ncBblM920jw)
> - [Basic Buffer Overflow - VulnServer TRUN](https://youtu.be/yJF0YPd8lDw)
> - [Stack Based Buffer Overflow Prep](https://youtu.be/1X2JGF_9JGM)
> - [OSCP Prep - x86 Windows Stack-Based Buffer Overflow Full Tutorial - War-FTP 1.65](https://youtu.be/Z2pQuGmFNrM)
> - [Buffer Overflow Prep (feat. Tib3rius and TryHackMe)](https://youtu.be/bBBaVQjjSLQ)

- Github:

```
1. https://github.com/justinsteven/dostackbufferoverflowgood
2. https://github.com/3isenHeiM/OSCP-BoF
3. https://github.com/gh0x0st/Buffer_Overflow
4. https://github.com/sradley/overflow (You should not use it in the exam)
5. https://github.com/onecloudemoji/BOF-Template (Buffer overflow template)
6. https://github.com/V1n1v131r4/OSCP-Buffer-Overflow
```

- Other Resources:

```
Whitepaper Introduction to Immunity Debugger: https://www.sans.org/reading-room/whitepapers/malicious/basic-reverse-engineering-immunity-debugger-36982
Do Stack Buffer Overflow Good: https://github.com/justinsteven/dostackbufferoverflowgood
Buffer Overflows for Dummies: https://www.sans.org/reading-room/whitepapers/threats/buffer-overflows-dummies-481
Vortex Stack Buffer Overflow Practice: https://www.vortex.id.au/2017/05/pwkoscp-stack-buffer-overflow-practice/
Smashing the Stack For Fun and Profit: http://www-inst.eecs.berkeley.edu/~cs161/fa08/papers/stack_smashing.pdf
Buffer Overflow Guide: https://github.com/johnjhacking/Buffer-Overflow-Guide
Stack based Linux Buffer Overflow: https://www.exploit-db.com/docs/english/28475-linux-stack-based-buffer-overflows.pdf
```

```
Expected time (without practice): 8 hours
```
## 𝐂𝐥𝐢𝐞𝐧𝐭-𝐬𝐢𝐝𝐞 𝐀𝐭𝐭𝐚𝐜𝐤𝐬

```
https://www.offensive-security.com/metasploit-unleashed/client-side-attacks/
```
```
Expected Time: (not sure)
```

## 𝐋𝐨𝐜𝐚𝐭𝐢𝐧𝐠 𝐏𝐮𝐛𝐥𝐢𝐜 𝐄𝐱𝐩𝐥𝐨𝐢𝐭𝐬

- Places to Find Exploits:
> - https://www.exploit-db.com/
> - https://packetstormsecurity.com/files/tags/exploit/
> - https://www.securityfocus.com/

- Tools for finding exploits:
```
Searchsploit: a command line search tool for Exploit-DB
Nmap NSE Script
The Browser Exploitation Framework (BeEF)


Manual for searchsploit: https://www.exploit-db.com/searchsploit
```
```
Expected Time: 1 hour
```

## 𝐀𝐧𝐭𝐢𝐯𝐢𝐫𝐮𝐬 𝐄𝐯𝐚𝐬𝐢𝐨𝐧

- Book
```
Antivirus Bypass Techniques: Learn Practical Techniques and Tactics to Combat, Bypass, and Evade Antivirus Software 

Link: https://g.co/kgs/WzEjAH
```

- Tools to play with Anti-Virus evasion:
```
Veil-Framework: https://github.com/Veil-Framework/Veil
Shellter: https://www.shellterproject.com/
Unicorn https://github.com/trustedsec/unicorn
UniByAV: https://github.com/Mr-Un1k0d3r/UniByAv
```

- Tools to play with for Obfuscation:
```
PowerShell:

Invoke-Obfuscation: https://github.com/danielbohannon/Invoke-Obfuscation
Chimera: https://github.com/tokyoneon/Chimera
Python:

Pyarmor: https://pypi.org/project/pyarmor/
PyObfx: https://github.com/PyObfx/PyObfx
C#:

ConfuserEx: https://github.com/yck1509/ConfuserEx
```

- Testing Payloads Publicly. (Keep in mind that submitting your samples to online scanners may be distributed to other AV engines):

```
Nodistribute: https://nodistribute.com/
Virustotal: https://www.virustotal.com/gui/home
Hybrid-Analysis: https://www.hybrid-analysis.com/
Any-Run: https://app.any.run
Reverse.it: https://reverse.it
Anti-Virus Evasion Tool: https://github.com/govolution/avet
DefenderCheck: https://github.com/matterpreter/DefenderCheck
ThreatCheck: https://github.com/rasta-mouse/ThreatCheck
```

```
Expected: 12 hours
```

## 𝐏𝐫𝐢𝐯𝐢𝐥𝐞𝐠𝐞 𝐄𝐬𝐜𝐚𝐥𝐚𝐭𝐢𝐨𝐧

- Blogs:
> - [Windows elevation of privileges](https://guif.re/windowseop)
> - [Linux elevation of privileges](https://guif.re/linuxeop) 
> - [Basic Linux Privilege Escalation](https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/)
> - [Checklist - Local Windows Privilege Escalation](https://book.hacktricks.xyz/windows/checklist-windows-privilege-escalation)
> - [Linux Privilege Escalation](https://book.hacktricks.xyz/linux-unix/privilege-escalation)
> - [Linux](https://guide.offsecnewbie.com/privilege-escalation/linux-pe)
> - [Linux Privilege Escalation Exploiting Capabilities](https://steflan-security.com/linux-privilege-escalation-exploiting-capabilities/)
> - [I absolutely suck at privilege escalation](https://www.reddit.com/r/oscp/comments/9ystub/i_absolutely_suck_at_privilege_escalation/)
> - [Privilege escalations in windows](https://infosecwriteups.com/privilege-escalation-in-windows-380bee3a2842)
> - [Windows Privilege Escalation Guide](https://www.absolomb.com/2018-01-26-Windows-Privilege-Escalation-Guide/)
> - [Hacking Linux Part I: Privilege Escalation](http://www.dankalia.com/tutor/01005/0100501004.htm)
> - [Windows Privilege Escalation Fundamentals](http://www.fuzzysecurity.com/tutorials/16.html)
> - [Windows Privilege Escalation Methods for Pentesters](https://pentest.blog/windows-privilege-escalation-methods-for-pentesters/)
> - [Windows Services - All roads lead to SYSTEM](https://labs.f-secure.com/archive/windows-services-all-roads-lead-to-system/)
> - [I hate hate hate HATEE privilege escalation.](https://www.reddit.com/r/oscp/comments/iclvle/i_hate_hate_hate_hatee_privilege_escalation_did/)

- Practice:
> - https://gtfobins.github.io/
> - https://lolbas-project.github.io/
> - https://forum.hackthebox.com/t/oscp-practice/531

- Videos/Courses
> - https://www.udemy.com/course/linux-privilege-escalation/
> - Tiberius and TCM udemy courses
> - [OSCP - Windows Privilege Escalation Methodology](https://www.youtube.com/watch?v=Qfy-traJwIs)
> - [Encyclopaedia Of Windows Privilege Escalation - Brett Moore](https://youtu.be/kMG8IsCohHA)
> - [DerbyCon 3 0 2105 Windows Attacks At Is The New Black Rob Fuller And Chris Gates](https://youtu.be/_8xJaaQlpBo)
> - [Privilege Escalation](https://www.youtube.com/playlist?list=PLDrNMcTNhhYrBNZ_FdtMq-gLFQeUZFzWV)
> - [Ippsec](https://www.youtube.com/c/ippsec)

- Github:
```
1. https://github.com/sagishahar/lpeworkshop
2. https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Methodology%20and%20Resources
3. https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Windows%20-%20Privilege%20Escalation.md
4. https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Linux%20-%20Privilege%20Escalation.md
5. https://github.com/netbiosX/Checklists/blob/master/Windows-Privilege-Escalation.md
6. https://github.com/abatchy17/WindowsExploits
7. https://github.com/PowerShellMafia/PowerSploit/tree/master/Privesc
8. https://github.com/rasta-mouse/Sherlock
9. https://github.com/AonCyberLabs/Windows-Exploit-Suggester

```

- Others

```
- https://github.com/carlospolop/PEASS-ng/tree/master/linPEAS
- https://in.security/lin-security-practise-your-linux-privilege-escalation-foo/
- https://www.vulnhub.com/entry/linsecurity-1,244/
- https://www.netsecfocus.com/oscp/2021/05/06/The_Journey_to_Try_Harder-_TJnull-s_Preparation_Guide_for_PEN-200_PWK_OSCP_2.0.html#section-10-buffer-overflows-for-windows-and-linux
- http://pwnwiki.io/#!privesc/windows/index.md
- https://pentest.blog/windows-privilege-escalation-methods-for-pentesters/
- https://github.com/N7WEra/SharpAllTheThings
- https://github.com/411Hall/JAWS/commits?author=411Hall
- https://github.com/bitsadmin/wesng
- https://github.com/rasta-mouse/Sherlock
- https://github.com/carlospolop/PEASS-ng/tree/master/winPEAS
- https://github.com/rasta-mouse/Watson
- https://github.com/GhostPack/Seatbelt
- https://github.com/gladiatx0r/Powerless
- https://github.com/PowerShellMafia/PowerSploit/tree/master/Recon
- https://github.com/breenmachine/RottenPotatoNG
- https://github.com/ohpe/juicy-potato
- https://rahmatnurfauzi.medium.com/windows-privilege-escalation-scripts-techniques-30fa37bd194
- https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/
- https://github.com/jondonas/linux-exploit-suggester-2
```

```
Expected: 12 hours
```


## 𝐏𝐚𝐬𝐬𝐰𝐨𝐫𝐝 𝐀𝐭𝐭𝐚𝐜𝐤𝐬

- Offline tools for password cracking

```
Hashcat: https://hashcat.net/hashcat/ Sample Hashes to test with Hashcat: https://hashcat.net/wiki/doku.php?id=example_hashes
John the Ripper: https://www.openwall.com/john/
Metasploit Unleashed using John the Ripper with Hashdump: https://www.offensive-security.com/metasploit-unleashed/john-ripper/
```

- Online Tools for password cracking

```
THC Hydra: https://github.com/vanhauser-thc/thc-hydra
Crowbar: https://github.com/galkan/crowbar
```

- Wordlist Generator

```
Cewl: https://digi.ninja/projects/cewl.php
Crunch: https://tools.kali.org/password-attacks/crunch
Cupp (In Kali Linux): https://github.com/Mebus/cupp
```

- Tools to check the hash type:

```
Hash-Identifier: https://github.com/psypanda/hashID

```
- Tools to dump for hashes:

```
Mimikatz: https://github.com/gentilkiwi/mimikatz
Mimipenguin: https://github.com/huntergregal/mimipenguin
Pypykatz: https://github.com/skelsec/pypykatz
```

- Wordlists:

```
In Kali: /usr/share/wordlists
Seclists: apt-get install seclists You can find all of his password lists here: https://github.com/danielmiessler/SecLists/tree/master/Passwords
Xajkep Wordlists: https://github.com/xajkep/wordlists
```

- Online Password Crackers:

```
https://hashkiller.io/
https://www.cmd5.org/
https://www.onlinehashcrack.com/
https://gpuhash.me/
https://crackstation.net/
https://passwordrecovery.io/
https://md5decrypt.net/en/
https://hashes.com/en/decrypt/hash
http://cracker.offensive-security.com/
```

- Others

```
Introduction to Password Cracking: https://alexandreborgesbrazil.files.wordpress.com/2013/08/introduction_to_password_cracking_part_1.pdf
Pwning Wordpress Passwords: https://medium.com/bugbountywriteup/pwning-wordpress-passwords-2caf12216956
```

```
Expected: 12 hours
```


## 𝐏𝐨𝐫𝐭 𝐑𝐞𝐝𝐢𝐫𝐞𝐜𝐭𝐢𝐨𝐧 𝐚𝐧𝐝 𝐓𝐮𝐧𝐧𝐞𝐥𝐢𝐧𝐠

- Blogs
> - [Proxytunnels](https://www.offensive-security.com/metasploit-unleashed/proxytunnels/)
> - [Portfwd](https://www.offensive-security.com/metasploit-unleashed/portfwd/)
> - [Explore Hidden Networks with double pivoting](https://pentest.blog/explore-hidden-networks-with-double-pivoting/)
> - [Tunneling and pivoting](https://0xdf.gitlab.io/2019/01/28/pwk-notes-tunneling-update1.html)
> - [Port Forwarding: A practical hands on guide](https://www.abatchy.com/2017/01/port-forwarding-practical-hands-on-guide)
> - [Configuring Port Forwarding on Windows](http://woshub.com/port-forwarding-in-windows/)
> - [SSH Tunneling Explained](https://chamibuddhika.wordpress.com/2012/03/21/ssh-tunnelling-explained/)

- Tools

```
Proxychains: https://github.com/haad/proxychains
Proxychains-ng: https://github.com/rofl0r/proxychains-ng
SSHuttle (Totally Recommend learning this): https://github.com/sshuttle/sshuttle
SSHuttle Documentation: https://sshuttle.readthedocs.io/en/stable/
Chisel https://github.com/jpillora/chisel
Ligolo: https://github.com/sysdream/ligolo
```

- Online Tunneling Services

```
Ngrok: https://ngrok.com/
Twilo: https://www.twilio.com/
```

- Practice

```
Wintermute: https://www.vulnhub.com/entry/wintermute-1,239/
```


```
Expected: 12 hours
```

## 𝐀𝐜𝐭𝐢𝐯𝐞 𝐃𝐢𝐫𝐞𝐜𝐭𝐨𝐫𝐲 𝐀𝐭𝐭𝐚𝐜𝐤𝐬

- Blogs

> - [Attack this active directory machine and get your 40 points!](https://www.reddit.com/r/oscp/comments/s5puw0/attack_this_active_directory_machine_and_get_your/)
> - [[AD 0] Setting up an Active Directory Lab](https://shroudri.github.io/guides/setting-up-active-directory/)
> - [Attacking Active Directory: 0 to 0.9](https://zer1t0.gitlab.io/posts/attacking_ad/)



- Github:

> - https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Active%20Directory%20Attack.md
> - https://github.com/davidprowe/BadBlood
> - https://github.com/avi7611/Active-directory-small-cheatsheet

- Practice:
```
- https://tryhackme.com/room/attacktivedirectory
- https://tryhackme.com/network/throwback
- Heist, Hutch, Vault on PG Play
- Tryhackme Holo, Throwback networks in addition to attacktive and post exploitation rooms
- Hackthebox: Forest, Sauna, dante, active, Arctic and Granny.
- CyberSecLabs
- Razorblack, Enterprise, VulnNet - Active on tryhackme
- wreath on tryhackme
- blackfield, intelligence, multimaster, cascade, heist...crap was that htb heist or pg heist or both, Reel, Sauna, Fuse, Sizzle, Mantis, and Resolute.
- https://drive.google.com/file/d/1RktnrenlhOMIqdPDAv-u60_yzW7K0KS0/view
- Rastalabs on HTB
```

- Videos:
> - [Kerberos & Attacks 101](https://www.youtube.com/watch?v=IBeUz7zMN24)
> - [Active Directory Attack Series](https://youtube.com/playlist?list=PLPDUz8KkxR5z2z84CJ1JyLXC9JgxkjPBk)
> - [Attacking Active Directory - GPP Credentials](https://www.youtube.com/watch?v=sTedpt47t2Y)
> - [70-640 Active Directory Course](https://youtube.com/playlist?list=PL1l78n6W8zypXtkh3uWIXbPssc4IGbfb5)
> - [Common Active Directory Attacks: Back to the Basics of Security Practices](https://youtu.be/vga7A2tYejE)
> - [What is Active Directory](https://youtu.be/GfqsFtmJQg0)

- TJNull's suggestion:

```
Setting up Active Directory:

Note: Make sure when you are setting up the Active Directory Server that you assign a static IP address to it and also a workstation that you will be joining the server to for further testing. I recommend that you set up a Windows 10 Workstation if you plan to use Windows Server 2016/2019.

Microsoft Documentation to install Active Directory: https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/deploy/install-active-directory-domain-services–level-100-
Install Windows Active Directory on Windows Server 2019: https://computingforgeeks.com/how-to-install-active-directory-domain-services-in-windows-server/
Understanding Users Accounts in Active Directory: https://docs.microsoft.com/en-us/windows/security/identity-protection/access-control/active-directory-accounts
Three ways to create an Active Directory User: https://petri.com/3-ways-to-create-new-active-directory-users
Join a Workstation to the Domain: https://docs.microsoft.com/en-us/windows-server/identity/ad-fs/deployment/join-a-computer-to-a-domain
Tools to help you automate the installation for Active Directory:

ADLab: https://github.com/browninfosecguy/ADLab
Automated Lab: https://github.com/AutomatedLab/AutomatedLab
MSLab: https://github.com/microsoft/MSLab
Invoke-ADLabDeployer: https://github.com/outflanknl/Invoke-ADLabDeployer
Active Directory User Setup: https://github.com/bjiusc/Active-Directory-User-Setup-Script
Enumerating Active Directory:

Active Directory Enumeration with Powershell: https://www.exploit-db.com/docs/english/46990-active-directory-enumeration-with-powershell.pdf
Active Directory Exploitation Cheat Sheet: https://github.com/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet#domain-enumeration
Powersploit: https://github.com/PowerShellMafia/PowerSploit
Understanding Authentication protocols that Active Directory Utilizes:

NTLM Authentication: https://docs.microsoft.com/en-us/windows-server/security/kerberos/kerberos-authentication-overview
Kerberos Authentication https://docs.microsoft.com/en-us/windows-server/security/kerberos/kerberos-authentication-overview
Cache and Stored Credentials: https://docs.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/hh994565(v=ws.11)
Group Managed Service Accounts: https://adsecurity.org/?p=4367
Lateral Movement in Active Directory:

Paving the Way to DA: https://blog.zsec.uk/path2da-pt1
Part 2, 3
Pass the Hash with Machine Accounts: https://www.ired.team/offensive-security-experiments/active-directory-kerberos-abuse/pass-the-hash-with-machine-accounts
Overpass the hash (Payload All the things): https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Active%20Directory%20Attack.md#overpass-the-hash-pass-the-key
Red Team Adventures Overpass the Hash: https://riccardoancarani.github.io/2019-10-04-lateral-movement-megaprimer/#overpass-the-hash
Pass the Ticket (Silver Tickets): https://adsecurity.org/?p=2011
Lateral Movement with DCOM: https://www.ired.team/offensive-security/lateral-movement/t1175-distributed-component-object-model
Active Directory Persistence:

Cracking Kerberos TGS Tickets Using Kerberoast: https://adsecurity.org/?p=2293
Kerberoasting Without Mimikatz: https://www.harmj0y.net/blog/powershell/kerberoasting-without-mimikatz/
Golden Tickets: https://www.ired.team/offensive-security-experiments/active-directory-kerberos-abuse/kerberos-golden-tickets
Pass the Ticket (Golden Tickets): https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Active%20Directory%20Attack.md#pass-the-ticket-golden-tickets
Understanding DCSync Attacks: https://attack.stealthbits.com/privilege-escalation-using-mimikatz-dcsync
Tools for Active Directory Lateral Movement and Persistence:

ADRecon: https://github.com/sense-of-security/ADRecon
Kerbrute: https://github.com/ropnop/kerbrute
Rubeus: https://github.com/GhostPack/Rubeus
Impacket: https://github.com/SecureAuthCorp/impacket
Other Resources:

Building an Active Directory with PowerShell: https://1337red.wordpress.com/building-and-attacking-an-active-directory-lab-with-powershell/
Lateral Movement for AD: https://riccardoancarani.github.io/2019-10-04-lateral-movement-megaprimer/#overpass-the-hash
Lateral Movement with CrackMapExec: https://www.hackingarticles.in/lateral-moment-on-active-directory-crackmapexec/
```



- Others:
```
- https://wadcoms.github.io/
- https://www.xmind.net/m/5dypm8/
- Cybermentor's Practical Ethical Hacking Course - Active Directory Section
```
```
Expected: 48 hours
```

## 𝐓𝐡𝐞 𝐌𝐞𝐭𝐚𝐬𝐩𝐥𝐨𝐢𝐭 𝐅𝐫𝐚𝐦𝐞𝐰𝐨𝐫𝐤


> - Metasploit Unleashed: https://www.offensive-security.com/metasploit-unleashed/
> - Book:
>    - [Metasploit: The Penetration Tester's Guide](https://g.co/kgs/Cpu7s9)

- MSFvenom Cheat Sheets:
```
http://security-geek.in/2016/09/07/msfvenom-cheat-sheet/
https://netsec.ws/?p=331
https://github.com/rapid7/metasploit-framework/wiki/How-to-use-msfvenom
```

```
Expected: 4 hours
```

## 𝐏𝐨𝐰𝐞𝐫𝐬𝐡𝐞𝐥𝐥 𝐄𝐦𝐩𝐢𝐫𝐞

> - Powershell Empire: https://github.com/BC-SECURITY/Empire
> - Powershell Empire Guide: https://alpinesecurity.com/blog/empire-a-powershell-post-exploitation-tool/


```
Expected: 4 hours
```

## 𝐓𝐫𝐲𝐢𝐧𝐠 𝐇𝐚𝐫𝐝𝐞𝐫: 𝐓𝐡𝐞 𝐋𝐚𝐛𝐬

- HTB VM List: https://docs.google.com/spreadsheets/d/1dwSMIAPIam0PuRBkCiDI88pU3yzrqqHkDtBngUHNCw8/edit#gid=1839402159
- Vulnhub VM List: https://docs.google.com/spreadsheets/d/1dwSMIAPIam0PuRBkCiDI88pU3yzrqqHkDtBngUHNCw8/edit#gid=0


# 𝐒𝐭𝐫𝐚𝐭𝐞𝐠𝐲

- Overview:

```
Phase I: Theory, Preparation and Note Taking
Phase II: Practice
Phase III: OSCP Labs & Origial Course Material
Phase IV: OSCP Exam
```
```
Thought Process:

So, Yeah! We have 180 days i.e. 175 remaining. I took a lot of time planning, it's ok tho. 
One shot, game khallas karna hai. Let's plan:

Let's divide OSCP into fundamental components that will require for us to crack OSCP:
1. Theory, theory and theory. In-depth Understanding of lot of topics.
2. Ability to apply knowledge practically.
3. Critical Thinking
4. High Pain threshold.
5. Consistency 
6. Note taking

Step by step dekha jaye toh, you should have basic understanding of almost everything beforehand so that you don't keep jumping back on phase I from phase II.
Do theory, make notes and refer to notes. Have everything at one place! That's it for today, hehe!
```

- [Study Methodology](https://www.reddit.com/r/intj/comments/savbmb/study_tips_from_an_intj_to_an_intj/)

