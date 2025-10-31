# leaf-1-legal

This repository anchors the legal foundation of the Phonicboon platform. It contains versioned legal agreements, cryptographic hashes, and metadata that ensure every consent event is traceable, reproducible, and tamper-proof.

---

## 📜 Purpose

`leaf-1-legal` is the first leaf in a modular, auditable architecture. It is not wired to blockchain — its sole job is to version and verify legal agreements. This repo enables:

- Transparent legal terms for all parties  
- Cryptographic anchoring of every agreement version  
- Reproducible audit trails for consent and IP protection  
- Trust through public visibility and hash-based verification

---

## 🧾 Legal Transparency

This repo will include:

- **Terms and Conditions** *(pending)*  
- **Privacy Policy** *(pending)*  
- **Trademark Notice**  
  - Trademark: **Phonicboon™**  
  - Registration Number: **UK00003876542**  
  - Registered to: **Phonicboon Ltd.**
- **Author Identity**  
  - Name: **David John Foster**  
  - Wallet Address: `0xB7461A650a79B29e6AFBCB93Cf34B34fEc721917`  
  - Email: `admin@phonicboon.com`

All future declarations will be versioned and hashed for public verification.

---

## 📁 Folder Structure

| Path               | Purpose |
|--------------------|---------|
| `agreements/`      | Markdown versions of each legal agreement (`v1.0.md`, `v1.1.md`, etc.) |
| `hashes/`          | SHA256 hashes of each agreement version (`v1.0.sha256`) |
| `tags/`            | Optional Git tag metadata or signed manifests |
| `dataset.json`     | Canonical map of version → hash → timestamp → notes |
| `README.md`        | This document |

---

## ✅ What’s Been Done

- Created `v1.0.md` — initial wallet consent agreement  
- Generated SHA256 hash:  
  `0240625e36c12e3fa69e76e07bb809cd175ad82495553e93057d069e189fc30c`  
- Mapped hash and timestamp in `dataset.json`  
- Committed and tagged as `v1.0`  
- Author: David John Foster (`admin@phonicboon.com`)  
- Repo initialized with Git for auditability

---

## 🔐 Verification

To verify agreement integrity:

```bash
sha256sum agreements/v1.0.md
