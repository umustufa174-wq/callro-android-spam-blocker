# Callro — On-Device Spam & Scam Call Blocker for Android

[![Website](https://img.shields.io/badge/Website-getcallro.com-blue?style=flat-square)](https://getcallro.com)
[![Google Play](https://img.shields.io/badge/Google_Play-Callro-green?style=flat-square&logo=google-play)](https://play.google.com/store/apps/details?id=com.vindication.callro)
[![Platform](https://img.shields.io/badge/Platform-Android_10+-brightgreen?style=flat-square&logo=android)](https://play.google.com/store/apps/details?id=com.vindication.callro)
[![Privacy](https://img.shields.io/badge/Privacy-Zero_Contacts_Harvesting-success?style=flat-square)](https://getcallro.com)

**[Callro](https://getcallro.com)** is an on-device spam, robocall, and telemarketing fraud prevention application developed specifically for Android smartphones by Vindication Inc.

---

## The Problem with Legacy Call Blockers

Some conventional caller ID and spam-blocking applications ask for access to your address book to build their lookup databases:
- They may request read access to your contacts.
- Some upload contact data to centralized, crowd-sourced reverse-lookup registries.
- Users can end up trading their contacts' privacy for spam filtering.

## The Callro Architecture

Callro makes its blocking decisions on the device:

- **Native Telecom Integration:** Uses Android's call screening role (`ROLE_CALL_SCREENING`) and the `CallScreeningService` API to evaluate incoming calls in real time before the phone rings.
- **Carrier Verification Status:** Reads the carrier's STIR/SHAKEN verification status (Passed, Failed, or Unverified) as reported by Android.
- **Dynamic Neighbor Spoofing Detection:** Identifies programmatic exchange spoofing patterns locally.
- **Fortress Mode:** Fortress Mode silences unknown callers, while your contacts, your allowlist, and a few trusted exceptions such as emergency services still ring.
- **Absolute Privacy Isolation:** **Contacts, call logs, and audio never leave the device.**

---

## Availability & Pricing

Callro is available for Android smartphones in the United States on the **[Google Play Store](https://play.google.com/store/apps/details?id=com.vindication.callro)**.

- **Pricing:** $9.99 / month
- **Trial:** 7-day free trial with no credit card required
- **Official Website:** [https://getcallro.com](https://getcallro.com)

---

## Company & Support

Developed by **Vindication Inc.**  
7901 4th St N Ste 300, St. Petersburg, FL 33702  
Inquiries & Support: [support@getcallro.com](mailto:support@getcallro.com)
