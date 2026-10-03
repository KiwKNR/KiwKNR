# Kanarat Kaeothong (KiwKNR / Axiom0x)

Offensive security / pentester based in Thailand. I break web apps and networks,
audit source code for bugs, and run a small CTF team. Currently doing red team work
at BMSP and teaching cyber-warfare labs for the Royal Thai Navy on the side.

Day to day I'm in Burp, reading PHP/Python source looking for the thing a dev
assumed no one would ever send, and writing it up with a PoC that actually runs.

```
role      red teamer / penetration tester
focus     web exploitation, network pentest, AD, privesc
ctf       web / pwn / rev / crypto, player + trainer
```

## Disclosures

I audit open-source web apps on my own time. Rule I keep: no report goes out
without a working PoC first, and the fix gets coordinated with the maintainer
through a GitHub Security Advisory before anything is public.

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

Also took 1st runner-up in the Cyber Warrior (naval personnel) team CTF at Navy Cyber Fair 2026.

## Stuff I've built

**SENTINEL-7 CyberRange** - red vs blue range I put together with the SENTINEL-7 team
for Navy training. Each operator gets an isolated Docker container with a loaded
toolset, spins up in a few seconds, live scoreboard for the missions.
Live at redopsdb.com.

**ELEC CTF Arena** - CTF platform I run for the Navy Electronics Department where I
teach. Server-side flag checking (SHA-256), live board, new labs daily. In production
at elec-ctf-arena.vercel.app.

## Tools I live in

Burp Suite, nmap, Metasploit, Wireshark, Ghidra, sqlmap, ffuf, gobuster, httpx,
subfinder, katana, gitleaks, trufflehog, BloodHound, gdb (gef/pwndbg).
Mostly Kali, some Parrot and Arch. Scripting in Python and Bash, bit of C and Go,
PowerShell when the target's Windows.

## What I test

Web is home turf: SQLi, XSS, SSRF, IDOR, auth bypass, file upload, SSTI, deser.
APIs too (BOLA/IDOR, broken auth, mass assignment, JWT). On internal work it's the
usual recon, pivoting, lateral movement, and AD stuff (kerberoasting, pass-the-hash,
BloodHound). Then privesc and post-ex once I'm in.

Security contact: open a private vulnerability report on the relevant repo.
