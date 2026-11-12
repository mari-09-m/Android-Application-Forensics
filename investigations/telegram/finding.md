
# Telegram Android Forensics — Findings and Analysis

## 1. Investigation Summary

This document summarises observations from a controlled
forensic investigation of the Telegram Android application.

The investigation involved application examination,
Android log collection, dynamic testing, forensic tools,
and evidence integrity verification.

## 2. Environment and Connectivity

An Android Studio emulator was used as the test environment.

ADB was used to communicate with the emulator and
collect investigation data.

## 3. Android Log Collection

Application and system logs were collected using
Android Logcat.

A pre-login log file was saved and its SHA-256 hash
was calculated to support evidence integrity verification.

## 4. Application Examination

JADX was used to examine the Android application package.

The investigation included reviewing available application
structures and documenting technical observations.

## 5. Dynamic Testing

Controlled application testing was performed using
the Android emulator.

Application states and observable changes were recorded
during testing.

These observations were documented for comparison
and further forensic examination.

## 6. Forensic Tools

FTK Imager was used during the investigation process.

An Autopsy case was created to organise and examine
available forensic material.

The creation of a forensic case does not, by itself,
demonstrate successful recovery of protected user data.

## 7. Evidence Integrity

SHA-256 hashing was used to support verification
of collected investigation files.

Original evidence files and sensitive investigation
data are not included in this repository.

## 8. Limitations

The investigation was limited to the available emulator
environment and accessible evidence.

The work does not establish complete recovery of
Telegram's protected application data.

## 9. Key Learning Outcomes

- Android forensic investigation
- Log collection and examination
- Controlled application testing
- Evidence integrity verification
- Forensic tool usage
- Technical documentation

## 10. Supporting Evidence

Selected sanitised screenshots and evidence references
will be added after verification and publication review.
