`Note: These are my notes for personal reference!`



# 𝐎𝐒𝐂𝐏 𝐏𝐫𝐞-𝐏𝐫𝐞𝐩𝐚𝐫𝐚𝐭𝐢𝐨𝐧 𝐏𝐥𝐚𝐧 𝐚𝐧𝐝 𝐍𝐨𝐭𝐞𝐬



> - `21st March 2022` : Start Date
> - `19th Sept 2022` : Expected End Date
> - `180 days` : Goal

---
<img src="https://user-images.githubusercontent.com/68887544/159728391-b9c52bda-b711-4c63-aa52-3886a7ab54c1.png">

## ⁍ 𝐓𝐚𝐛𝐥𝐞 𝐨𝐟 𝐂𝐨𝐧𝐭𝐞𝐧𝐭𝐬

- [Pre-requisites](#𝐏𝐫𝐞-𝐫𝐞𝐪𝐮𝐢𝐬𝐢𝐭𝐞𝐬)
- [Getting Comfortable with Kali Linux](#𝐆𝐞𝐭𝐭𝐢𝐧𝐠-𝐂𝐨𝐦𝐟𝐨𝐫𝐭𝐚𝐛𝐥𝐞-𝐰𝐢𝐭𝐡-𝐊𝐚𝐥𝐢-𝐋𝐢𝐧𝐮𝐱)
- [Command Line Fun](#𝐂𝐨𝐦𝐦𝐚𝐧𝐝-𝐋𝐢𝐧𝐞-𝐅𝐮𝐧)
- [Practical Tools](#𝐏𝐫𝐚𝐜𝐭𝐢𝐜𝐚𝐥-𝐓𝐨𝐨𝐥𝐬)
- [Bash Scripting](#𝐁𝐚𝐬𝐡-𝐒𝐜𝐫𝐢𝐩𝐭𝐢𝐧𝐠)
- [Passive Information Gathering](#𝐏𝐚𝐬𝐬𝐢𝐯𝐞-𝐈𝐧𝐟𝐨𝐫𝐦𝐚𝐭𝐢𝐨𝐧-𝐆𝐚𝐭𝐡𝐞𝐫𝐢𝐧𝐠)
- [Active Information Gathering](#𝐀𝐜𝐭𝐢𝐯𝐞-𝐈𝐧𝐟𝐨𝐫𝐦𝐚𝐭𝐢𝐨𝐧-𝐆𝐚𝐭𝐡𝐞𝐫𝐢𝐧𝐠)
- [Vulnerability Scanning](#𝐕𝐮𝐥𝐧𝐞𝐫𝐚𝐛𝐢𝐥𝐢𝐭𝐲-𝐒𝐜𝐚𝐧𝐧𝐢𝐧𝐠)
- [Web Application Attacks](#𝐖𝐞𝐛-𝐀𝐩𝐩𝐥𝐢𝐜𝐚𝐭𝐢𝐨𝐧-𝐀𝐭𝐭𝐚𝐜𝐤𝐬)
- [Introduction to Buffer Overflow](#𝐈𝐧𝐭𝐫𝐨𝐝𝐮𝐜𝐭𝐢𝐨𝐧-𝐭𝐨-𝐁𝐮𝐟𝐟𝐞𝐫-𝐎𝐯𝐞𝐫𝐟𝐥𝐨𝐰)
- [Windows Buffer Overflows](#𝐖𝐢𝐧𝐝𝐨𝐰𝐬-𝐁𝐮𝐟𝐟𝐞𝐫-𝐎𝐯𝐞𝐫𝐟𝐥𝐨𝐰𝐬)
- [Linux Buffer Overflows](#𝐋𝐢𝐧𝐮𝐱-𝐁𝐮𝐟𝐟𝐞𝐫-𝐎𝐯𝐞𝐫𝐟𝐥𝐨𝐰𝐬)
- [Client-side Attacks](#𝐂𝐥𝐢𝐞𝐧𝐭-𝐬𝐢𝐝𝐞-𝐀𝐭𝐭𝐚𝐜𝐤𝐬)
- [Locating Public Exploits](#𝐋𝐨𝐜𝐚𝐭𝐢𝐧𝐠-𝐏𝐮𝐛𝐥𝐢𝐜-𝐄𝐱𝐩𝐥𝐨𝐢𝐭𝐬)
- [Fixing Exploits](#𝐅𝐢𝐱𝐢𝐧𝐠-𝐄𝐱𝐩𝐥𝐨𝐢𝐭𝐬)
- [File Transfers](#𝐅𝐢𝐥𝐞-𝐓𝐫𝐚𝐧𝐬𝐟𝐞𝐫𝐬)
- [Antivirus Evasion](#𝐀𝐧𝐭𝐢𝐯𝐢𝐫𝐮𝐬-𝐄𝐯𝐚𝐬𝐢𝐨𝐧)
- [Privilege Escalation](#𝐏𝐫𝐢𝐯𝐢𝐥𝐞𝐠𝐞-𝐄𝐬𝐜𝐚𝐥𝐚𝐭𝐢𝐨𝐧)
- [Password Attacks](#𝐏𝐚𝐬𝐬𝐰𝐨𝐫𝐝-𝐀𝐭𝐭𝐚𝐜𝐤𝐬)
- [Port Redirection and Tunneling](#𝐏𝐨𝐫𝐭-𝐑𝐞𝐝𝐢𝐫𝐞𝐜𝐭𝐢𝐨𝐧-𝐚𝐧𝐝-𝐓𝐮𝐧𝐧𝐞𝐥𝐢𝐧𝐠)
- [Active Directory Attacks](#𝐀𝐜𝐭𝐢𝐯𝐞-𝐃𝐢𝐫𝐞𝐜𝐭𝐨𝐫𝐲-𝐀𝐭𝐭𝐚𝐜𝐤𝐬)
- [The Metasploit Framework](#𝐓𝐡𝐞-𝐌𝐞𝐭𝐚𝐬𝐩𝐥𝐨𝐢𝐭-𝐅𝐫𝐚𝐦𝐞𝐰𝐨𝐫𝐤)
- [Powershell Empire](#𝐏𝐨𝐰𝐞𝐫𝐬𝐡𝐞𝐥𝐥-𝐄𝐦𝐩𝐢𝐫𝐞)
- [Assembling the pieces: penetration test breakdown](#𝐀𝐬𝐬𝐞𝐦𝐛𝐥𝐢𝐧𝐠-𝐭𝐡𝐞-𝐩𝐢𝐞𝐜𝐞𝐬-𝐩𝐞𝐧𝐞𝐭𝐫𝐚𝐭𝐢𝐨𝐧-𝐭𝐞𝐬𝐭-𝐛𝐫𝐞𝐚𝐤𝐝𝐨𝐰𝐧)
- [Trying Harder: The Labs](#𝐓𝐫𝐲𝐢𝐧𝐠-𝐇𝐚𝐫𝐝𝐞𝐫-𝐓𝐡𝐞-𝐋𝐚𝐛𝐬)

## 𝐏𝐫𝐞-𝐫𝐞𝐪𝐮𝐢𝐬𝐢𝐭𝐞𝐬

> - Solid understanding of TCP/IP networking
>   - TCP/IP Fundamentals 
>     - [Part I](https://youtu.be/xdQ9sgpkrX8)
>     - [Part II](https://youtu.be/NdvWI6RH1eo)
> - Familiarity with basic Bash and/or Python scripting
>   - Python Books:
>     - [Black Hat Python](https://g.co/kgs/xmdQNE)
>     - [Violent Python](https://g.co/kgs/vJfCsm)
>   - Vidoes: 
>     - [The Complete Python Hacking Course: Beginner To Advance! (2021)](https://youtu.be/0NQ2aMxBYNE)
>     - [The Complete Python Hacking Course Playlist](https://youtube.com/playlist?list=PL9bcYdRTwTIme7BckMbAd55KdwEzeSe9m)


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

## 𝐁𝐚𝐬𝐡 𝐒𝐜𝐫𝐢𝐩𝐭𝐢𝐧𝐠

> - Practice:
>   - [Bash Scripting Practice on Hackerrank](https://www.hackerrank.com/domains/shell?filters%5Bstatus%5D%5B%5D=unsolved&filters%5Bstatus%5D%5B%5D=solved&filters%5Bsubdomains%5D%5B%5D=bash)
>   - https://www.learnshell.org/
> - Book:
>   - [Shell Scripting: How to Automate Command Line Tasks Using...](https://g.co/kgs/LW4kQy)



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

## 𝐕𝐮𝐥𝐧𝐞𝐫𝐚𝐛𝐢𝐥𝐢𝐭𝐲 𝐒𝐜𝐚𝐧𝐧𝐢𝐧𝐠
## 𝐖𝐞𝐛 𝐀𝐩𝐩𝐥𝐢𝐜𝐚𝐭𝐢𝐨𝐧 𝐀𝐭𝐭𝐚𝐜𝐤𝐬
## 𝐈𝐧𝐭𝐫𝐨𝐝𝐮𝐜𝐭𝐢𝐨𝐧 𝐭𝐨 𝐁𝐮𝐟𝐟𝐞𝐫 𝐎𝐯𝐞𝐫𝐟𝐥𝐨𝐰
## 𝐖𝐢𝐧𝐝𝐨𝐰𝐬 𝐁𝐮𝐟𝐟𝐞𝐫 𝐎𝐯𝐞𝐫𝐟𝐥𝐨𝐰𝐬
## 𝐋𝐢𝐧𝐮𝐱 𝐁𝐮𝐟𝐟𝐞𝐫 𝐎𝐯𝐞𝐫𝐟𝐥𝐨𝐰𝐬
## 𝐂𝐥𝐢𝐞𝐧𝐭-𝐬𝐢𝐝𝐞 𝐀𝐭𝐭𝐚𝐜𝐤𝐬
## 𝐋𝐨𝐜𝐚𝐭𝐢𝐧𝐠 𝐏𝐮𝐛𝐥𝐢𝐜 𝐄𝐱𝐩𝐥𝐨𝐢𝐭𝐬
## 𝐅𝐢𝐱𝐢𝐧𝐠 𝐄𝐱𝐩𝐥𝐨𝐢𝐭𝐬
## 𝐅𝐢𝐥𝐞 𝐓𝐫𝐚𝐧𝐬𝐟𝐞𝐫𝐬
## 𝐀𝐧𝐭𝐢𝐯𝐢𝐫𝐮𝐬 𝐄𝐯𝐚𝐬𝐢𝐨𝐧
## 𝐏𝐫𝐢𝐯𝐢𝐥𝐞𝐠𝐞 𝐄𝐬𝐜𝐚𝐥𝐚𝐭𝐢𝐨𝐧
## 𝐏𝐚𝐬𝐬𝐰𝐨𝐫𝐝 𝐀𝐭𝐭𝐚𝐜𝐤𝐬
## 𝐏𝐨𝐫𝐭 𝐑𝐞𝐝𝐢𝐫𝐞𝐜𝐭𝐢𝐨𝐧 𝐚𝐧𝐝 𝐓𝐮𝐧𝐧𝐞𝐥𝐢𝐧𝐠
## 𝐀𝐜𝐭𝐢𝐯𝐞 𝐃𝐢𝐫𝐞𝐜𝐭𝐨𝐫𝐲 𝐀𝐭𝐭𝐚𝐜𝐤𝐬
## 𝐓𝐡𝐞 𝐌𝐞𝐭𝐚𝐬𝐩𝐥𝐨𝐢𝐭 𝐅𝐫𝐚𝐦𝐞𝐰𝐨𝐫𝐤
## 𝐏𝐨𝐰𝐞𝐫𝐬𝐡𝐞𝐥𝐥 𝐄𝐦𝐩𝐢𝐫𝐞
## 𝐀𝐬𝐬𝐞𝐦𝐛𝐥𝐢𝐧𝐠 𝐭𝐡𝐞 𝐩𝐢𝐞𝐜𝐞𝐬: 𝐩𝐞𝐧𝐞𝐭𝐫𝐚𝐭𝐢𝐨𝐧 𝐭𝐞𝐬𝐭 𝐛𝐫𝐞𝐚𝐤𝐝𝐨𝐰𝐧
## 𝐓𝐫𝐲𝐢𝐧𝐠 𝐇𝐚𝐫𝐝𝐞𝐫: 𝐓𝐡𝐞 𝐋𝐚𝐛𝐬


