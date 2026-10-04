<div align="center">

<a href="https://overkazaf.github.io/blogs/"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&random=false&width=620&height=80&lines=0xaf+%E2%94%82+Security+Researcher;Breaking+DRM+%C2%B7+Reversing+Android+%C2%B7+Building+Tools" alt="Typing SVG" /></a>

<br/>

**DRM Engineer at [NetEase](https://www.netease.com) · Previously [Alibaba Cloud](https://www.alibabacloud.com)**

[![Blog](https://img.shields.io/badge/Blog-overkazaf.github.io-0d1117?style=flat-square&logo=hugo&logoColor=58a6ff)](https://overkazaf.github.io/blogs/)
[![GitHub followers](https://img.shields.io/github/followers/overkazaf?label=Follow&style=flat-square&logo=github&color=0d1117&logoColor=58a6ff)](https://github.com/overkazaf)
[![Profile Views](https://komarev.com/ghpvc/?username=overkazaf&style=flat-square&color=0d1117&label=Visitors)](https://github.com/overkazaf)

</div>

---

```
0xaf@re-lab:~$ whoami
```

> Security engineer. 10+ years reversing DRM systems, Android app protections, and low-level binary obfuscation.
> I break content protection stacks (Widevine · FairPlay · PlayReady), reverse mobile security at scale
> (MetaSec · MTGSig · SecurityGuard), and build offensive tooling that bridges static analysis and runtime instrumentation.

```
0xaf@re-lab:~$ cat /etc/career
BUAA → ECUST → Acxiom → Alibaba Cloud → NetEase (current)
```

---

### `0x00` Exploit Surface

<table>
<tr>
<td width="50%" valign="top">

```
┌─── DRM & Content Protection ───┐
│                                │
│  Widevine L1/L3                │
│  FairPlay + KSM                │
│  PlayReady SL3000              │
│  Netflix MSL Protocol          │
│  Chrome CDM Internals          │
│  Whitebox Crypto · HDCP        │
│                                │
└────────────────────────────────┘
```

</td>
<td width="50%" valign="top">

```
┌─── Mobile Reverse Engineering ─┐
│                                │
│  Douyin MetaSec (6-god sigs)   │
│  Meituan MTGSig                │
│  Taobao SecurityGuard          │
│  PDD libpdd_secure             │
│  Xiaohongshu Shield            │
│  APK Hardening (24 vendors)    │
│                                │
└────────────────────────────────┘
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

```
┌─── Offensive Tooling ──────────┐
│                                │
│  Frida Instrumentation         │
│  Ghidra Scripting              │
│  OLLVM Deobfuscation           │
│  Symbolic Execution            │
│  Native VMP Analysis           │
│  unidbg Emulation              │
│                                │
└────────────────────────────────┘
```

</td>
<td width="50%" valign="top">

```
┌─── Low-Level Systems ──────────┐
│                                │
│  ARM TrustZone (EL0→EL3)      │
│  TEE Security                  │
│  MITM Infrastructure           │
│  Device Fingerprinting         │
│  SVC Syscall Protection        │
│  eBPF Tracing                  │
│                                │
└────────────────────────────────┘
```

</td>
</tr>
</table>

---

### `0x01` Arsenal

<table>
<tr>
<td width="50%" valign="top">

**[reverse_engineering](https://github.com/overkazaf/reverse_engineering)** `⭐ 8`
```
RE cookbook — DRM, Android native, exploitation
techniques, analysis workflows. The field manual.
```

</td>
<td width="50%" valign="top">

**[aria](https://github.com/overkazaf/aria)** `⭐ 8`
```
FairPlay DRM decrypt pipeline. KSM extraction,
stream decryption, m3u8 repackaging.
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[re-agent](https://github.com/overkazaf/re-agent)** `⭐ 3`
```
AI-powered terminal agent for RE and CTF.
Go + LLM-driven binary analysis.
```

</td>
<td width="50%" valign="top">

**[cap](https://github.com/overkazaf/cap)**
```
MITM proxy for mobile RE. Go + Svelte.
Real-time traffic interception & analysis.
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[unpack](https://github.com/overkazaf/unpack)** `⭐ 1`
```
Android unpacker. 24 commercial packer vendors.
Automated deprotection pipeline.
```

</td>
<td width="50%" valign="top">

**[Ponce4Ghidra](https://github.com/overkazaf/Ponce4Ghidra)**
```
Symbolic execution plugin for Ghidra.
Taint analysis & constraint solving.
```

</td>
</tr>
</table>

---

### `0x02` Dispatches from the Lab

```
0xaf@re-lab:~$ tail -f /var/log/research.log
```

| tag | post | date |
|:---:|------|-----:|
| `re` | [Ponce4Ghidra 符号执行实战](https://overkazaf.github.io/blogs/posts/ponce4ghidra-symbolic-execution-crackme/) | `2026-10-03` |
| `hw` | [用 RP2350 从零搭建一个 DRM 系统](https://overkazaf.github.io/blogs/posts/rp2350-diy-audio-drm-from-scratch/) | `2026-09-30` |
| `re` | [PDD libpdd_secure Anti-Token](https://overkazaf.github.io/blogs/posts/pinduoduo-libpdd-secure-antitoken-evidence-boundaries/) | `2026-08-26` |
| `re` | [美团 MTGSig DFP Risk Control](https://overkazaf.github.io/blogs/posts/meituan-mtgsig-dfp-risk-control-boundaries/) | `2026-08-26` |
| `drm` | [PlayReady SL3000 Deep Dive](https://overkazaf.github.io/blogs/posts/playready-pro-license-sl3000-deep-dive/) | `2026-08-24` |
| `drm` | [Widevine PSSH & L1 Deep Dive](https://overkazaf.github.io/blogs/posts/widevine-pssh-license-l1-deep-dive/) | `2026-08-24` |

**[→ all 25 posts](https://overkazaf.github.io/blogs/)**

---

### `0x03` Loadout

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

![Ghidra](https://img.shields.io/badge/Ghidra-bf360c?style=flat-square&logoColor=white)
![Frida](https://img.shields.io/badge/Frida-ef6c00?style=flat-square&logoColor=white)
![radare2](https://img.shields.io/badge/radare2-424242?style=flat-square&logoColor=white)
![unidbg](https://img.shields.io/badge/unidbg-1565c0?style=flat-square&logoColor=white)
![IDA Pro](https://img.shields.io/badge/IDA_Pro-4a148c?style=flat-square&logoColor=white)
![Unicorn](https://img.shields.io/badge/Unicorn-333333?style=flat-square&logoColor=white)
![Keystone](https://img.shields.io/badge/Keystone-555555?style=flat-square&logoColor=white)
![Capstone](https://img.shields.io/badge/Capstone-666666?style=flat-square&logoColor=white)

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![ARM](https://img.shields.io/badge/ARM-0091BD?style=flat-square&logo=arm&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![QEMU](https://img.shields.io/badge/QEMU-FF6600?style=flat-square&logo=qemu&logoColor=white)

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=overkazaf&show_icons=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&ring_color=58a6ff" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=overkazaf&layout=compact&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" height="165" />

<br/>

<img src="https://streak-stats.demolab.com?user=overkazaf&hide_border=true&background=0D1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=6e7681" width="49%" />

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/overkazaf/overkazaf/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/overkazaf/overkazaf/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/overkazaf/overkazaf/output/github-snake-dark.svg" />
</picture>

</div>

---

<div align="center">

```
0xaf@re-lab:~$ echo $MOTTO
DRM systems don't break themselves.
```

</div>
