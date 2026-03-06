# Session-artefact-parser
Session Parser is a Python-based digital forensics tool for analysis of Session Messenger artefacts on Windows and macOS. It decrypts Session’s SQLCipher databases, extracts attachment decryption keys, and performs forensic-safe decryption and reconstruction of encrypted attachments from authorised forensic acquisitions.
# Session Forensic Decryptor

A Python-based forensic tool to decrypt and parse **Session Messenger**
artifacts, including SQLCipher databases and encrypted attachments.

## Features
- Decrypts `db.sqlite` using SQLCipher
- Extracts `local_attachment_encrypted_key`
- Decrypts files from `attachments.noindex`
- Auto-detects file types (JPG, PNG, PDF, MP4, etc.)
- GUI and CLI support
- Forensic-safe (read-only source handling)

## Requirements
- Python 3.10+
- SQLCipher
- PyNaCl

## Installation
```bash
pip install -r requirements.txt
