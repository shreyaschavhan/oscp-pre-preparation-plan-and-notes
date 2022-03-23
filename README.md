`Note: These are my notes for personal reference!`

# 𝐎𝐒𝐂𝐏 𝐏𝐫𝐞-𝐏𝐫𝐞𝐩𝐚𝐫𝐚𝐭𝐢𝐨𝐧 𝐏𝐥𝐚𝐧 𝐚𝐧𝐝 𝐍𝐨𝐭𝐞𝐬


> - `21st March 2022` : Start Date
> - `19th Sept 2022` : Expected End Date
> - `180 days` : Goal

---

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
- [Assembling the pieces: penetration test breakdown](#𝐀𝐬𝐬𝐞𝐦𝐛𝐥𝐢𝐧𝐠-𝐭𝐡𝐞-𝐩𝐢𝐞𝐜𝐞𝐬:-𝐩𝐞𝐧𝐞𝐭𝐫𝐚𝐭𝐢𝐨𝐧-𝐭𝐞𝐬𝐭-𝐛𝐫𝐞𝐚𝐤𝐝𝐨𝐰𝐧)
- [Trying Harder: The Labs](#𝐓𝐫𝐲𝐢𝐧𝐠-𝐇𝐚𝐫𝐝𝐞𝐫:-𝐓𝐡𝐞-𝐋𝐚𝐛𝐬)

## 𝐏𝐫𝐞-𝐫𝐞𝐪𝐮𝐢𝐬𝐢𝐭𝐞𝐬

- Solid understanding of TCP/IP networking
  - TCP/IP Fundamentals 
    - Part I : https://youtu.be/xdQ9sgpkrX8
    - Part II: https://youtu.be/NdvWI6RH1eo

## 𝐆𝐞𝐭𝐭𝐢𝐧𝐠 𝐂𝐨𝐦𝐟𝐨𝐫𝐭𝐚𝐛𝐥𝐞 𝐰𝐢𝐭𝐡 𝐊𝐚𝐥𝐢 𝐋𝐢𝐧𝐮𝐱

## 𝐂𝐨𝐦𝐦𝐚𝐧𝐝 𝐋𝐢𝐧𝐞 𝐅𝐮𝐧

## 𝐏𝐫𝐚𝐜𝐭𝐢𝐜𝐚𝐥 𝐓𝐨𝐨𝐥𝐬

## 𝐁𝐚𝐬𝐡 𝐒𝐜𝐫𝐢𝐩𝐭𝐢𝐧𝐠

## 𝐏𝐚𝐬𝐬𝐢𝐯𝐞 𝐈𝐧𝐟𝐨𝐫𝐦𝐚𝐭𝐢𝐨𝐧 𝐆𝐚𝐭𝐡𝐞𝐫𝐢𝐧𝐠

## 𝐀𝐜𝐭𝐢𝐯𝐞 𝐈𝐧𝐟𝐨𝐫𝐦𝐚𝐭𝐢𝐨𝐧 𝐆𝐚𝐭𝐡𝐞𝐫𝐢𝐧𝐠

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


