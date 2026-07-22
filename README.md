# ⚡ BIGVIRTUE1 Free

**BIGVIRTUE1 - Advanced Privacy Guardian Encryption Program**

**Strong Multi-Layer Encryption | Free for Personal Use | Linux Only**

---

### 📖 소개 (Introduction)
BIGVIRTUE1 Free는 사용자의 데이터를 보호하기 위해 설계된 강력한 암호화 도구입니다. 리눅스(Linux) 환경에서 데이터 보호의 기본에 충실한 '대덕탑 개인정보 수호신' 암호화 프로그램입니다.

본 프로젝트는 BIGVIRTUE1 개인정보 수호신 시리즈의 무료 배포 버전으로, 리눅스 사용자 누구나 안전하고 편리하게 사용할 수 있도록 설계되었습니다.

> "What no other company would provide, I have built and released for free to protect your data."
> "어떤 기업도 제공하지 않는 강력한 개인정보 보호 기술, 세상에 기여하기 위해 직접 개발하여 리눅스 개인용으로 무료 공개합니다."

---

### ⚖️ 라이선스 및 이용 정책 (License & Usage Policy)

* **개인 사용자 (Personal Use):** 본 프로그램은 개인적인 용도로만 무료로 사용 가능합니다.
* **상업적 이용 (Commercial Use):** 기업 및 상업적 목적의 사용은 사전 공식 허가가 필요합니다.
* **Contact:** [bigvirtue1@naver.com]

* **Free for personal use only (Linux).**
* **Commercial use is prohibited without prior authorization.**

---

## 📖 Introduction
`bigvirtue1_free` is the **bigvirtue1 Linux Privacy Guardian God Encryption Program**.
No Korean company sells this.
One independent developer built it and released it for free.
Built for people who believe privacy is a right, not a product.

---

## ✨ Features
- **Multi-Layer Encryption** — Multiple strong symmetric encryption algorithms in serial chain
- **RSA-4096 Session Keys** — Generated in real-time for every encryption
- **Chunked Encryption for Large Files** — Files are encrypted in 16MB chunks, keeping memory usage low and stable even for multi-gigabyte files
- **Directory Encryption** — Encrypt entire folders into a single encrypted archive
- **Dual Viewer** — View images and text side by side with Sync mode
- **Tree View** — Browse encrypted directory contents without extracting
- **Fullscreen Viewer** — Full-screen buttons for each pane and for the whole viewer
- **Right-click Menu** — Quick access to all file operations
- **Secure Memory Wipe** — Sensitive data (passwords, keys) is actively zeroed from memory as soon as it's no longer needed
- **Password Field Transparency** — The on-screen password field is the single source of truth; if it's empty, nothing decrypts. It's cleared automatically when a viewer closes or an operation finishes
- **Network Blocked (App-Level)** — Python's socket module is disabled within the app; this is an application-level restriction, not an OS firewall
- **Debugger Detection (Basic)** — Checks /proc/self/status for an attached tracer and exits if found. This is a basic, well-known check; as with any open-source tool, a determined attacker with source access can work around it
- **VM Detection** — Warns (does not block) when running inside a common virtual machine
- **Self-Integrity Check (compiled builds only)** — Verifies a SHA-256 hash embedded in the executable at build time. Only active when running as a compiled binary, not when run as a raw Python script
- **YUKHYO & NINE STAR KI** — Traditional East Asian divination tools included
- **Drag & Drop** — Drag files directly into the file list
- **Search & Sort** — Search and sort your encrypted files, memos, and loaded temporary files easily
- **Session Purge** — One-click wipe of all session data

---

## 💻 Requirements
- Linux (x86_64)
- No installation required — just run the binary

---

## 📁 File Structure
After first run, these directories are created automatically next to the binary:
```
bigvirtue1_free/
├── bigvirtue1_free      ← Executable
├── bigvirtue1_free.png  ← Icon
├── install.sh           ← Installer
├── vault/               ← Encrypted files (.bv1, .bv1x)
└── memos/                ← Plain text memos (.txt)
```

---

## 🔒 A Note on Security Scope

This program provides strong encryption for your files (AES-256-GCM, ChaCha20-Poly1305,
and a Serpent/AES-CBC layer, chained together, with RSA-4096 session keys). That part is
solid and uses well-established cryptographic libraries.

The anti-tampering features listed above (debugger detection, self-integrity check) are
best-effort speed bumps, not guarantees — this is normal for any open-source tool, since
the source is visible to everyone. They do not claim to stop a determined, skilled attacker.
Features that were previously listed but aren't actually implemented (keylogger protection,
screen-capture protection) have been removed from this list for accuracy; these are very
difficult to guarantee at the application level on Linux and we'd rather be upfront about
that than overstate what the program does.

---

## 📜 License
- **Personal use**: Free
- **Commercial use**: Paid license required
- 📧 Email: bigvirtue1@naver.com
- 🌐 Website: [bigvirtue1.com](https://bigvirtue1.com)

---

## 👤 Developer
**bigvirtue1** — Independent developer & professional divination practitioner
Self-taught programmer | 7+ years | 20+ programs built

- 🌐 Website: [bigvirtue1.com](https://bigvirtue1.com)
- 📧 Email: bigvirtue1@naver.com
- 🐙 GitHub: [github.com/bigvirtue1](https://github.com/bigvirtue1)

---

## 한글 소개
`bigvirtue1_free` 는 리눅스용 개인정보 보호 수호신 암호화 프로그램입니다.
한국의 어떤 기업도 이런 프로그램을 팔지 않습니다.
한 명의 개인 개발자가 혼자 만들어서 무료로 공개했습니다.

### 주요 기능
- 다중 레이어 강력 암호화 (AES-256-GCM + ChaCha20-Poly1305 + Serpent/AES-CBC 체인)
- 실시간 RSA-4096 세션키
- 대용량 파일도 16MB 단위로 나눠서 암호화 — 수 GB 파일도 메모리 사용량 안정적
- 디렉토리 통째로 암호화
- 좌우 분리 듀얼 뷰어 (Sync 기능), 개별/전체 전체화면 버튼
- 트리뷰로 암호화 디렉토리 내부 탐색
- 화면 비밀번호 입력창이 유일한 기준 — 비어있으면 아무것도 복호화되지 않으며, 뷰어를 닫거나 작업이 끝나면 자동으로 지워짐
- 네트워크 접근을 앱(파이썬) 레벨에서 차단 — OS 방화벽 수준의 차단은 아님
- 민감한 정보(비밀번호, 키)는 사용 직후 메모리에서 즉시 0으로 덮어씀
- 육효 & 구성기학 점술 기능 포함

### 보안 범위에 대한 안내
암호화 자체(AES-256-GCM, ChaCha20-Poly1305, RSA-4096)는 검증된 암호 라이브러리를
사용하며 견고합니다. 다만 디버거 탐지·자체 무결성 검사 같은 변조 방지 기능들은
오픈소스 프로그램의 특성상 소스 코드가 공개되어 있어 숙련된 공격자를 완전히
막지는 못하는, 기초적인 수준의 저지선입니다. 이전에 안내되었던 키로거/화면캡처
방지 기능은 실제로 구현되어 있지 않아 목록에서 제외했습니다 — 리눅스 앱 레벨에서
이를 보장하기는 매우 어렵고, 실제보다 부풀려 안내하는 것보다는 정직하게 안내하는
것이 낫다고 판단했습니다.

### 라이선스
- **개인 사용**: 무료
- **기업 사용**: 유료 라이선스 문의

### 개발자
- 🌐 공식 사이트: [bigvirtue1.com](https://bigvirtue1.com)
- 📧 이메일: bigvirtue1@naver.com
- 🐙 GitHub: [github.com/bigvirtue1](https://github.com/bigvirtue1)
