# Session-artefact-parser
Session Forensic Decryptor is a Python-based digital forensics tool for the lawful analysis of Session Messenger artifacts. It decrypts SQLCipher databases, extracts attachment keys, and performs forensic-safe decryption of encrypted attachments from authorised forensic acquisitions.
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
