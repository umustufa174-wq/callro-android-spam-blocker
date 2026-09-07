# Callro — On-Device Spam & Scam Call Blocker for Android

[![Website](https://img.shields.io/badge/Website-getcallro.com-blue?style=flat-square)](https://getcallro.com)
[![Google Play](https://img.shields.io/badge/Google_Play-Callro-green?style=flat-square&logo=google-play)](https://play.google.com/store/apps/details?id=com.vindication.callro)
[![Platform](https://img.shields.io/badge/Platform-Android_10+-brightgreen?style=flat-square&logo=android)](https://play.google.com/store/apps/details?id=com.vindication.callro)
[![Privacy](https://img.shields.io/badge/Privacy-Zero_Contacts_Harvesting-success?style=flat-square)](https://getcallro.com)

**[Callro](https://getcallro.com)** is an on-device spam, robocall, and telemarketing fraud prevention application developed specifically for Android smartphones by Vindication Inc.

---

## The Problem with Legacy Call Blockers

Most conventional caller ID and spam blocking applications operate on an invasive data-harvesting model:
- They require full read access to your address book.
- They upload personal contacts, phone numbers, and names to centralized crowd-sourced reverse-lookup registries.
- Users inadvertently sacrifice their family’s and contacts' privacy just to filter spam calls.

## The Callro Architecture

Callro operates on a strict **on-device architecture**:

- **Native Telecom Integration:** Interfaces directly with Android's official `ROLE_CALL_SCREENING` and `CallScreeningService` APIs to evaluate incoming calls in real time before the phone rings.
- **Cryptographic Carrier Attestation:** Evaluates STIR/SHAKEN digital certificates (Full A-level attestation vs. gateway spoofing) directly on the handset.
- **Dynamic Neighbor Spoofing Detection:** Identifies programmatic exchange spoofing patterns locally.
- **Fortress Mode:** An accessible toggle designed to protect seniors and vulnerable families from Medicare scams and imposter fraud by allowing only verified contacts to ring the handset.
- **Absolute Privacy Isolation:** **Contacts, call logs, and audio never leave the device.**

---

## Availability & Pricing

Callro is available for Android smartphones worldwide on the **[Google Play Store](https://play.google.com/store/apps/details?id=com.vindication.callro)**.

- **Pricing:** $9.99 / month
- **Trial:** 7-day free trial with no credit card required
- **Official Website:** [https://getcallro.com](https://getcallro.com)

---

## Company & Support

Developed by **Vindication Inc.**  
7901 4th St N Ste 300, St. Petersburg, FL 33702  
Inquiries & Support: [support@getcallro.com](mailto:support@getcallro.com)
