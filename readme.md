# 🎯 TechTonicExpoCTF Writeups - F3ngShu1's Digital Vault

<div align="center">

```
"Every challenge is a puzzle waiting to be solved...
                        and every flag is a victory worth celebrating."
                                        - F3ngShu1 Team
```

![TechTonic Banner](https://img.shields.io/badge/Team-F3ngShu1-purple?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTEyIDJMMTMuMDkgOC4yNkwyMCA5TDEzLjA5IDE1Ljc0TDEyIDIyTDEwLjkxIDE1Ljc0TDQgOUwxMC45MSA4LjI2TDEyIDJaIiBzdHJva2U9IiNmZmZmZmYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIi8+Cjwvc3ZnPgo=)
![CTF](https://img.shields.io/badge/CTF-TechTonic%20Expo-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

</div>

## 🎯 About This Repository

Welcome to F3ngShu1's comprehensive writeup collection for **TechTonic Expo CTF**! This repository contains detailed solutions and methodologies for both the Qualification and Finals rounds, showcasing advanced penetration testing techniques, cryptographic analysis, and reverse engineering strategies.

**Team Members:**

- Vincent Aurigo Osnard
- Muhamad Rizqi Wiransyah
- Julius Wijaya

## 🏆 Competition Overview

This repository is divided into two major phases:

### 📁 Qualification Round

Complete writeups covering fundamental to advanced challenges across multiple security domains.

### 📁 Finals Round

Elite-level challenges requiring deep technical expertise and creative problem-solving approaches.

---

## 🌟 Qualification Round - Challenge Categories

### 🕸️ **Web Exploitation**

1. **Cookie Trickery** - Browser storage manipulation
   - Technique: Cookie tampering, privilege escalation
   - Flag: `TechtonicExpoCTF{C00K13_TR1CK3RY}`

2. **Bypass OTP** - Two-factor authentication bypass
   - Technique: OTP verification bypass, parameter manipulation
   - Flag: `TechtonicExpoCTF{BypasOTP_EzUbb777}`

3. **Disguised Upload** - File upload filter evasion
   - Technique: Extension manipulation, upload bypass
   - Flag: `TechtonicExpoCTF{UPL04D_3X3CUT3}`

4. **JS Secret Hunter** - JavaScript code analysis
   - Technique: Runtime JavaScript analysis, function inspection
   - Flag: `TechtonicExpoCTF{J4V45CR1PT_FL4G_R3V3AL}`

### 🔐 **Cryptography**

1. **Zankyou** - RSA cryptanalysis with shuffled primes
   - Technique: Prime factorization, permutation brute-force
   - Flag: `TechtonicExpoCTF{RS4_1S_0UR_F4M}`

2. **Stardust Enigma** - Advanced RSA with modular arithmetic leaks
   - Technique: GCD attack, modular arithmetic exploitation
   - Flag: `TechtonicExpoCTF{fu7ur3_i5_1n_y0ur_h4nd5}`

### 🔧 **Reverse Engineering**

1. **Kirigaya Secret** - AVL Tree binary puzzle
   - Technique: Python bytecode decompilation, XOR decryption
   - Flag: `TechtonicExpoCTF{s0m3on3_t0ld_m3_t0_@_m0r3_ch4ll}`

2. **Random XOR** - File encryption reversing
   - Technique: Seed prediction, XOR cipher reversal
   - Flag: `TechtonicExpoCTF{X0R_IS_NOt_R4ndOM_at_A11}`

### 🔍 **Forensics**

1. **Network Nightmare** - Network traffic analysis
   - Technique: Wireshark packet analysis, Base64 decoding
   - Flag: `TechtonicExpoCTF{th1s_fr3ak_m3_0ut}`

2. **AES No Jutsu** - AES encrypted image extraction
   - Technique: AES-CBC decryption, steganography
   - Flag: `TechtonicExpoCTF{fu7ur3_i5_1n_y0ur_h4nd5}`

### 🖼️ **Steganography**

1. **Pixel Secrets** - Hidden data in PNG images
   - Technique: LSB analysis using zsteg
   - Flag: `TechtonicExpoCTF{p1x3l_p0w3r_unl34sh3d}`

2. **Kue Lapis** - Multi-layer image steganography
   - Technique: Bit plane extraction, channel analysis
   - Flag: `TechtonicExpoCTF{ku3_l4p1s_d4r1_st3g4n0}`

---

## 🏆 Finals Round - Challenge Categories

### 🕸️ **Web Exploitation**

1. **Session Impersonator API** - API method manipulation
   - Technique: HTTP method override, privilege escalation
   - Flag: `TechtonicExpoCTF{API_FLagXBoskuh}`

2. **XSS Reflected Encoded** - Encoded XSS injection
   - Technique: URL encoding bypass, reflected XSS
   - Flag: `TechtonicExpoCTF{XSS_TR1GGR_5C0P3}`

3. **UID Voyager (IDOR)** - Insecure direct object reference
   - Technique: Base64 decoding, IDOR exploitation
   - Flag: `TechtonicExpoCTF{1D0R_3XP0S3D_T0K3N}`

### 🔐 **Cryptography**

1. **Stein** - Custom cipher reverse mapping
   - Technique: Byte-by-byte cipher mapping, known-plaintext attack
   - Flag: `TechtonicExpoCTF{N3v3r_Us3_St4t1c_K3y}`

2. **Auth** - JWT token manipulation
   - Technique: JWT decoding, privilege escalation
   - Flag: `TechtonicExpoCTF{d0n7_g3t_too_s7re5s3d_4b0u7_crypt0_br0}`

3. **Wonderhoy** - MD5 collision attack
   - Technique: HashClash collision generation
   - Flag: `TechtonicExpoCTF{HALOOooOO👋_I'm_Emu🤩_Otori🤗_Emu😍_is_meaning😋_smile😁_wonderhoyyyy✨🎉🧨🎁🎢}`

### 🔧 **Reverse Engineering**

1. **Byte Rebellion** - Python bytecode analysis
   - Technique: Bytecode disassembly, constant extraction
   - Flag: `TechtonicExpoCTF{n0_m0r3_funny_th4n_6yt3_c0d3}`

---

## 🌌 Repository Structure

```
TechTonicExpo/
├── Quals/
│   └── pdf/
│       └── WriteUpTechTonicExpo - F3N9_SHU1.pdf
│
├── Finals/
│   └── pdf/
│       └── FengShui - TechTonicExpoCTF - WriteUp - Final - English.pdf
│
└── README.md
```

---

## 📋 Complete Challenge Overview

### Qualification Round

| Category  | Challenge         | Difficulty | Technique           | Status |
| --------- | ----------------- | ---------- | ------------------- | ------ |
| Web       | Cookie Trickery   | ⭐⭐       | Cookie Manipulation | ✅     |
| Web       | Bypass OTP        | ⭐⭐⭐     | OTP Bypass          | ✅     |
| Web       | Disguised Upload  | ⭐⭐⭐     | File Upload Exploit | ✅     |
| Web       | JS Secret Hunter  | ⭐⭐       | JavaScript Analysis | ✅     |
| Crypto    | Zankyou           | ⭐⭐⭐⭐   | RSA Factorization   | ✅     |
| Crypto    | Stardust Enigma   | ⭐⭐⭐⭐   | Modular Arithmetic  | ✅     |
| Reverse   | Kirigaya Secret   | ⭐⭐⭐     | Bytecode Analysis   | ✅     |
| Reverse   | Random XOR        | ⭐⭐⭐     | XOR Cipher          | ✅ 🩸  |
| Forensics | Network Nightmare | ⭐⭐⭐     | PCAP Analysis       | ✅     |
| Forensics | AES No Jutsu      | ⭐⭐⭐     | AES Decryption      | ✅     |
| Stego     | Pixel Secrets     | ⭐⭐       | LSB Extraction      | ✅     |
| Stego     | Kue Lapis         | ⭐⭐⭐     | Multi-layer Stego   | ✅     |

### Finals Round

| Category | Challenge                | Difficulty | Technique         | Status |
| -------- | ------------------------ | ---------- | ----------------- | ------ |
| Web      | Session Impersonator API | ⭐⭐⭐     | API Manipulation  | ✅     |
| Web      | XSS Reflected Encoded    | ⭐⭐⭐⭐   | Encoded XSS       | ✅     |
| Web      | UID Voyager              | ⭐⭐⭐     | IDOR Exploitation | ✅     |
| Crypto   | Stein                    | ⭐⭐⭐     | Cipher Mapping    | ✅     |
| Crypto   | Auth                     | ⭐⭐⭐     | JWT Manipulation  | ✅     |
| Crypto   | Wonderhoy                | ⭐⭐⭐⭐   | MD5 Collision     | ✅     |
| Reverse  | Byte Rebellion           | ⭐⭐⭐⭐   | Bytecode Analysis | ✅     |

---

<div align="center">

**"In CTF, every failure is a lesson, and every flag is a celebration."**

_Keep hacking, keep learning, keep improving! 🚀_

[![Star this repo](https://img.shields.io/github/stars/F3ngShu1/TechTonicExpo-WriteUp?style=social)](https://github.com/F3ngShu1/TechTonicExpo-WriteUp)
[![Fork this repo](https://img.shields.io/github/forks/F3ngShu1/TechTonicExpo-WriteUp?style=social)](https://github.com/F3ngShu1/TechTonicExpo-WriteUp)

_Crafted with 💜 by F3ngShu1 Team_

**Vincent Aurigo Osnard • Muhamad Rizqi Wiransyah • Julius Wijaya**

</div>
