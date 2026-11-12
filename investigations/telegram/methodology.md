

# Telegram Android Forensics — Investigation Methodology

## 1. Overview

This document describes the methodology used to examine
the Telegram Android application in a controlled laboratory
environment.

The investigation focused on application examination,
log collection, dynamic testing, evidence integrity,
and forensic documentation.

## 2. Investigation Environment

| Component | Description |
|---|---|
| Host OS | Windows |
| Test Device | Android Studio Emulator |
| Application | Telegram for Android |
| Connection | Android Debug Bridge (ADB) |
| Forensic Tools | Autopsy, FTK Imager, JADX |
| Log Collection | Android Logcat |
| Integrity Verification | SHA-256 |

## 3. Investigation Process

### Phase 1 — Environment Preparation
- Configured an Android emulator.
- Established ADB connectivity.
- Prepared the Telegram application for examination.
- Organised investigation files and evidence folders.

### Phase 2 — Static Examination
- Examined the Android application package using JADX.
- Reviewed the available application structure.
- Recorded relevant technical observations.

### Phase 3 — Evidence Collection
- Collected application and system logs using ADB.
- Saved baseline logs before controlled testing.
- Generated SHA-256 hashes for evidence integrity checks.
- Recorded relevant screenshots and investigation notes.

### Phase 4 — Dynamic Testing
- Launched Telegram in the Android emulator.
- Performed controlled application testing.
- Observed application behaviour.
- Compared application states.
- Collected additional logs and documented observations.

### Phase 5 — Forensic Examination
- Used FTK Imager during forensic examination.
- Created an investigation case in Autopsy.
- Examined available forensic material.
- Documented findings and investigation limitations.

### Phase 6 — Documentation
- Organised investigation evidence and screenshots.
- Documented the tools and procedures used.
- Prepared technical investigation notes and reporting.

## 4. Evidence Integrity

SHA-256 hashing was used to support integrity verification
of collected investigation files.

The original evidence files are not published in this
portfolio.

## 5. Limitations

The investigation was limited to the accessible evidence
and Android emulator environment.

The work does not demonstrate complete recovery of
protected Telegram application data.

## 6. Skills Demonstrated

- Android Application Forensics
- Digital Evidence Collection
- Log Analysis
- Static Application Examination
- Controlled Dynamic Testing
- SHA-256 Integrity Verification
- Technical Documentation

## 7. Security and Privacy

This investigation was conducted in an authorised
academic laboratory environment.

Personal data, authentication credentials, session
tokens, and confidential evidence are excluded
from public documentation.
