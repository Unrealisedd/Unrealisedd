<div align="center">

# Unrealisedd

**Security Researcher | Vulnerability Hunter | Reverse Engineer**

`12 CVEs` &nbsp; `NASA` &nbsp; `Ubisoft` &nbsp; `British MOD` &nbsp; `NSF`

[![HackerOne](https://img.shields.io/badge/HackerOne-494649?style=flat&logo=hackerone&logoColor=white)](https://hackerone.com/unrealisedd2)

</div>

---

I'm a 20-year-old security researcher from the Netherlands, studying IT at Fontys University of Applied Sciences. I find and report vulnerabilities in production systems — from kernel drivers to web applications.

Currently focused on binary exploitation, Windows kernel-level vulnerability research, and expanding my public research archive.

---

### Selected Research &nbsp; [![exploitarium](https://img.shields.io/badge/full_archive-exploitarium-blue?style=flat)](https://github.com/Unrealisedd/exploitarium)

| Target | Type | Impact |
|--------|------|--------|
| **Windows Defender** | NTLM coercion | Standard user forces SYSTEM credential leak via UNC path |
| **Windows Defender** | Signature lock bypass | `FILE_SHARE_READ` locks signatures on patched systems (CVE-2026-45498 bypass) |
| **dam.sys** | Kernel driver bugs (x3) | BSOD + confused deputy + Defender freeze from standard user |
| **OpenVPN** (ovpn-dco-win) | Kernel UAF | CNG key use-after-free in kernel driver |
| **Overwolf Updater** | LPE to SYSTEM | Forged Authenticode cert + insecure service DACL |
| **Safe Exam Browser** | Auth bypass + RCE | Service auth bypass → log injection → RCE as SYSTEM |
| **Discord Desktop** | RCE | Multiple desktop client RCE attack paths |
| **Nextcloud** | XXE + SSRF | File read/SSRF + protection bypass chain |
| **Woodpecker CI** | Pipeline RCE | `\r` bypass of newline sanitization → YAML injection |
| **spacedesk** | LPE to SYSTEM | Everyone full-control service DACL |
| **LibreNMS** | SSTI → RCE | Template injection to remote code execution chain |
| **RetroArch** (libchdr) | Heap overflow | Integer overflow → OOB write on 32-bit via crafted CHD |

---

### Repos

<table>
<tr>
<td width="50%">

**[exploitarium](https://github.com/Unrealisedd/exploitarium)**
Public archive of original exploit PoCs and vulnerability research writeups.

</td>
<td width="50%">

**[Methodology](https://github.com/Unrealisedd/Methodology)**
My pentesting methodology — recon through exploitation.

</td>
</tr>
<tr>
<td width="50%">

**[BAC-workflow](https://github.com/Unrealisedd/BAC-workflow)**
Automated broken access control testing.

</td>
<td width="50%">

**[Recon-workflow](https://github.com/Unrealisedd/Recon-workflow)**
Recon automation pipeline for bug bounty.

</td>
</tr>
</table>

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Unrealisedd&theme=github_dark&hide_border=true&hide_title=true&show_icons=true&count_private=true)

</div>

<div align="center">
<sub>vanmoorseltim@outlook.com</sub>
</div>
