<div align="center">

<img src="assets/banner.svg" alt="axiom0x // offensive security" width="840"/>

<h1>Kanarat Kaeothong &nbsp;·&nbsp; <code>Axiom0x</code></h1>

<a href="https://github.com/KiwKNR">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=900&color=34D058&center=true&vCenter=true&width=660&height=42&lines=offensive+security+%2F+pentest%2C+Thailand;i+break+web+apps+and+networks;read+the+source%2C+find+the+bug%2C+write+the+PoC;red+teamer+%40+BMSP+%E2%80%A2+CTF+trainer" alt="what i do"/>
</a>

<p>
<a href="https://github.com/KiwKNR/CVE-2026-103978"><img src="https://img.shields.io/badge/CVE--2026--103978-path%20traversal-critical?style=flat-square" alt="CVE-2026-103978"/></a>
<a href="https://github.com/KiwKNR/CVE-2026-104826"><img src="https://img.shields.io/badge/CVE--2026--104826-upload%20RCE-critical?style=flat-square" alt="CVE-2026-104826"/></a>
<img src="https://img.shields.io/badge/daily%20driver-Kali-557C94?style=flat-square&logo=kalilinux&logoColor=white" alt="Kali"/>
<img src="https://img.shields.io/badge/Navy%20Cyber%20Fair%202026-1st%20runner--up-FFD700?style=flat-square&labelColor=1a1a1a" alt="Navy Cyber Fair 2026"/>
<img src="https://img.shields.io/badge/CVEs%20assigned-2-8957e5?style=flat-square" alt="CVEs assigned"/>
<img src="https://komarev.com/ghpvc/?username=KiwKNR&style=flat-square&color=34d058&label=profile+views" alt="profile views"/>
</p>

</div>

I break web apps and networks, audit source code for bugs, and run a small CTF team.
Currently doing red team work at BMSP and teaching cyber-warfare labs for the Royal
Thai Navy on the side.

Day to day I'm in Burp, reading PHP/Python source looking for the thing a dev assumed
no one would ever send, then writing it up with a PoC that actually runs.

```console
axiom0x@kali:~$ whoami
role   red teamer / penetration tester
focus  web exploitation, network pentest, AD, privesc
ctf    web / pwn / rev / crypto, player + trainer
```

## Disclosures

I audit open-source web apps on my own time. Rule I keep: no report goes out without
a working PoC first, and the fix gets coordinated with the maintainer through a GitHub
Security Advisory before anything is public.

| CWE | Class | Severity | Status |
|:--|:--|:-:|:--|
| CWE-22 | Unauthenticated path traversal | High | [CVE-2026-103978](https://github.com/KiwKNR/CVE-2026-103978), GHSA advisory |
| CWE-434 | Unauthenticated file upload to RCE | Critical | reported, fix in progress |
| CWE-22 | Path traversal in chunked upload, file write to RCE | High | [CVE-2026-104826](https://github.com/KiwKNR/CVE-2026-104826), GHSA advisory |

Repo names stay private until a patch ships. CVE numbers go here once they're assigned.

## Certifications

| Cert | Issuer | Note |
|:--|:--|:--|
| CRTeamer, Certified Red Teamer | The SecOps Group | passed with Merit (v1.01) |
| CNPen, Certified Network Pentester | The SecOps Group | passed with Merit |
| CRTA, Certified Red Team Analyst | CyberWarfare Labs | |
| WEB-RTA, Web Red Team Analyst | CyberWarfare Labs | |
| API-RTA, API Red Team Analyst | CyberWarfare Labs | |
| kWAPTA, Web App Pentest Apprentice | Knight Squad Academy | |
| kAPIPTA, API Pentest Apprentice | Knight Squad Academy | |
| Penetration Testing Specialist | NCSA (สกมช.) | 28 hrs |
| Cybersecurity Professional (Advanced) | NCSA (สกมช.) | |
| Cybersecurity Foundation | NCSA (สกมช.) | |
| Cloud Security Standard for Practitioner (TCSAP) | NCSA (สกมช.) | 11 hrs |
| Ethical Hacking & Penetration Testing | FutureSkill | |
| Cybersecurity Fundamentals | FutureSkill | |

## Competitions

**Navy Cyber Fair 2026** ("Ready to Defend, Ready to Dominate") - 1st runner-up in the
Cyber Warrior track (naval personnel level), team CTF. Hands-on cyber operations
contest hosted by the Royal Thai Navy Directorate of Communications and IT. Writeups for the
challenges I solved are in [NAVY-CYBER-FAIR-2026-Writeups](https://github.com/KiwKNR/NAVY-CYBER-FAIR-2026-Writeups).

## Stuff I've built

**SENTINEL-7 CyberRange** - red vs blue range I put together with the SENTINEL-7 team
for Navy training. Each operator gets an isolated Docker container with a loaded
toolset, spins up in a few seconds, live scoreboard for the missions. Live at
[redopsdb.com](https://www.redopsdb.com).

**ELEC CTF Arena** - CTF platform I run for the Navy Electronics Department where I
teach. Server-side flag checking (SHA-256), live board, new labs daily. In production
at [elec-ctf-arena.vercel.app](https://elec-ctf-arena.vercel.app).

[![Pentest Vault](https://github-readme-stats.vercel.app/api/pin/?username=KiwKNR&repo=Pentest-Vault&theme=dark&hide_border=true)](https://github.com/KiwKNR/Pentest-Vault)
[![CTF Vault](https://github-readme-stats.vercel.app/api/pin/?username=KiwKNR&repo=CTF-Vault&theme=dark&hide_border=true)](https://github.com/KiwKNR/CTF-Vault)

## Tools I live in

Burp Suite, nmap, Metasploit, Wireshark, Ghidra, sqlmap, ffuf, gobuster, httpx,
subfinder, katana, gitleaks, trufflehog, BloodHound, gdb (gef/pwndbg). Mostly Kali,
some Parrot and Arch. Scripting in Python and Bash, bit of C and Go, PowerShell when
the target's Windows.

## What I test

Web is home turf: SQLi, XSS, SSRF, IDOR, auth bypass, file upload, SSTI, deser. APIs
too (BOLA/IDOR, broken auth, mass assignment, JWT). On internal work it's the usual
recon, pivoting, lateral movement, and AD stuff (kerberoasting, pass-the-hash,
BloodHound). Then privesc and post-ex once I'm in.

<br/>

![stats](https://github-readme-stats.vercel.app/api?username=KiwKNR&show_icons=true&theme=dark&hide_border=true&count_private=true)
![langs](https://github-readme-stats.vercel.app/api/top-langs/?username=KiwKNR&layout=compact&theme=dark&hide_border=true)

## Security contact

Open a private vulnerability report on the relevant repo, or encrypt to my PGP key
([`pgp.asc`](pgp.asc)):

```
3703 5DDA 7B71 F8CC B1DB  5F2B 3B8F 3468 4648 460A
```
