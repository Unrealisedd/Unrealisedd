<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=00F5FF&width=435&lines=Security+Researcher+%7C+Bug+Hunter;Kernel+%7C+Web+%7C+Mobile+%7C+Binary" alt="Typing SVG" />
  </a>
</div>

<div align="center">

`NASA` &nbsp; `Ubisoft` &nbsp; `British MOD` &nbsp; `NSF`

[![HackerOne](https://img.shields.io/badge/HackerOne-494649?style=flat&logo=hackerone&logoColor=white)](https://hackerone.com/unrealisedd2)

</div>

---

I'm a 20-year-old security researcher from the Netherlands. I find and report vulnerabilities in production systems, from kernel drivers to web applications.

Currently focused on binary exploitation, Windows kernel-level vulnerability research, and expanding my public research archive.

---

### Selected Research &nbsp; [![exploitarium](https://img.shields.io/badge/full_archive-exploitarium-blue?style=flat)](https://github.com/Unrealisedd/exploitarium)

| Target | Type | Impact |
|--------|------|--------|
| **dam.sys** | Kernel driver bugs (x4) | BSOD + confused deputy + info leak + session freeze from standard user |
| **Windows Defender** | NTLM coercion | Standard user forces SYSTEM credential leak via UNC path |
| **Windows Defender** | Signature lock bypass | `FILE_SHARE_READ` locks signatures on patched systems |
| **Firefox** | IPC sandbox escape | Unvalidated `AddCertException` → silent MITM on arbitrary hostnames |
| **Mosquitto** | Pre-auth RCE | Empty WebSocket frame heap overwrite → code execution |
| **MySQL Router** | OAuth cache ATO | Display-name cache collision → account takeover (CVSS 9.1) |
| **Keep** | Unauth RCE | Provider invoke chain → unauthenticated remote code execution |
| **OpenVPN** (ovpn-dco-win) | Kernel UAF | CNG key use-after-free in kernel driver |
| **Overwolf Updater** | LPE to SYSTEM | Forged Authenticode cert + insecure service DACL |
| **Safe Exam Browser** | Auth bypass + RCE | Service auth bypass → log injection → RCE as SYSTEM |
| **StorSvc** | DLL hijack LPE | `LoadLibraryW` without `LOAD_LIBRARY_SEARCH_SYSTEM32` → SYSTEM |
| **Discord Desktop** | RCE | Multiple desktop client RCE attack paths |
| **Nextcloud** | XXE + SSRF | File read/SSRF + protection bypass chain |
| **Wazuh** | Stack BOF + DoS | Stack buffer overflow + SCA denial of service |
| **n8n** | SSRF | Server-side request forgery via OAuth2 callback |
| **Fluent Bit** | Pre-auth DoS | collectd parser infinite loop from unauthenticated input |
| **Woodpecker CI** | Pipeline RCE | `\r` bypass of newline sanitization → YAML injection |
| **spacedesk** | LPE to SYSTEM | Everyone full-control service DACL |
| **LibreNMS** | SSTI → RCE | Template injection to remote code execution chain |
| **RetroArch** (libchdr) | Heap overflow | Integer overflow → OOB write on 32-bit via crafted CHD |

---

<p align="center">
  <i>"You can't secure what you don't understand."</i><br>
  <sub>— Bruce Schneier</sub>
</p>

---

<details>
  <summary>Support My Work</summary>

<p align="center">
  <a href="https://buymeacoffee.com/Unrealisedd"><img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black"/></a>
</p>

</details>

<div align="center">
<sub>vanmoorseltim@outlook.com</sub>
</div>
