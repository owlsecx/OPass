# 🔑 OPass

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-OUtility%20%2F%20Security-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-None%20(Standalone)-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **OPass** is a cryptographically secure password and passphrase generator. It uses Python’s `secrets` module (CSPRNG) to create strong passwords, scored passphrases, numeric PINs, and supports bulk generation with CSV export and strength analysis.

---

## 📌 Overview

OPass generates high-entropy passwords and memorable passphrases using secure random sources. It includes real-time strength scoring, easy-read mode, customizable charsets, bulk generation, and detailed strength feedback to help users create truly secure credentials.

---

## 🖥️ Modules

| # | Module                  | Description |
|---|-------------------------|-------------|
| **[1]** | **Generate Passwords**      | Custom charset, length, count with strength scoring |
| **[2]** | **Generate Passphrase**     | Word-based diceware-style passphrases |
| **[3]** | **PIN Generator**           | Numeric PINs (4–20 digits) |
| **[4]** | **Bulk Generate**           | Large batch generation with CSV export |
| **[5]** | **Check Strength**          | Score an existing password and give recommendations |
| **[6]** | **Settings**                | Configure length, charset, separator, output directory |

---

## 📊 Key Features

- **Cryptographically Secure**: Uses `secrets` module (CSPRNG) instead of `random`
- **Strength Scoring**: Real entropy calculation with "Very Strong" to "Very Weak" levels
- **Easy-Read Mode**: Avoids ambiguous characters (l,1,I,O,0)
- **Passphrase Support**: Diceware-style memorable phrases with customizable separator
- **Bulk Export**: Generate hundreds/thousands of passwords and export to CSV
- **Live Strength Feedback**: Immediate entropy bits and recommendations
- **Custom Charsets**: Lowercase, Uppercase, Digits, Symbols with easy toggles

---

## ⚙️ Requirements

- **Linux or Windows**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OPass

📁 Output
All generated passwords are saved to the ogen_results/ directory:

ogen_YYYYMMDD_HHMMSS.txt — single or passphrase generation
ogen_bulk_YYYYMMDD_HHMMSS.csv — bulk generation with strength details


📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.
