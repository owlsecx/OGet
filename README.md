# 🦉 OGet

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OCore-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.1-cyan?style=flat-square"/>
</p>

> **OGet** — Secure Multi-File Downloader

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OGet is a secure multi-file downloader for authorised retrieval workflows. It supports URL lists, resume, integrity verification, proxies, and optional post-download encryption, with a defensive safety posture that favours dry-run and gated external fetches. Integrity reports help operators prove what was collected.

---

## ✨ Features

- Multi-URL download from CLI args or a URL list file
- Concurrent threads with resume for interrupted transfers
- Integrity verification and download reporting
- HTTP/SOCKS proxy and optional stealth mode
- Optional encrypt-after-download and decrypt helpers
- Background/daemon mode for long retrieval jobs

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OGet -u https://example.com/file.bin -o ./downloads
./OGet -f urls.txt -t 8 --resume --verify
./OGet -u https://example.com/a.bin -e -p socks5://127.0.0.1:9050
./OGet --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 275+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled.s.Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
