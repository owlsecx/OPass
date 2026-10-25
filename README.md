# 🦉 OPass

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OPass-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **OPass** — Owl KeyForge Password Generator

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OPass is a command-line password and passphrase generator built on cryptographically secure randomness. It produces passwords, word-based passphrases and numeric PINs, and can score the strength of an existing password.

---

## ✨ Features

- Cryptographically secure password generation with configurable length
- Word-based passphrase generation with a customizable word count and separator
- Numeric PIN generation of a chosen length
- Strength scoring of a supplied password
- Batch generation of multiple values in a single run
- Optional exclusion of symbols from generated passwords

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OPass --gen -l 20 -n 5
./OPass --passphrase -w 5 --sep -
./OPass --pin -l 6
./OPass --check 'P@ssw0rd'
./OPass --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
