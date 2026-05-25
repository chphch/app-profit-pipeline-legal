---
title: Cat Calorie — Privacy Policy
layout: default
permalink: /cat-calorie/privacy-policy.html
---

# Privacy Policy — Cat Calorie

**Effective date**: (replace with launch date — YYYY-MM-DD)
**Last updated**: 2026-05-26

Cat Calorie ("the App") respects your privacy. This document explains what information the App collects, how it is used, and how it is protected. The App complies with the Google Play Data Safety requirements and the COPPA principles for U.S. distribution.

---

## 1. Personal Information We Collect

**The App does not directly collect personal information.**

- No account creation or sign-in is required.
- Cat profile data (name, weight, age, neutered status, lifestyle) and feeding-log entries are **stored only on your device** and never transmitted to any server.
- The App does not request your name, email, phone number, or any identifying information.

---

## 2. Automatically Collected Information (Third-Party SDKs)

The App includes third-party services to display advertising and process in-app purchases. These services may automatically collect limited information:

### 2-1. Google AdMob (advertising)
- **Collected**: Advertising identifier (AAID on Android, IDFA on iOS), device information (model, OS version, language), approximate location (country-level).
- **Used for**: Personalized ad delivery, ad performance measurement, fraud prevention.
- **Operator**: Google LLC ([Google Privacy Policy](https://policies.google.com/privacy)).
- **Opt-out**:
  - Android: Settings → Google → Ads → "Opt out of Ads Personalization"
  - iOS: Settings → Privacy & Security → Tracking → toggle off "Allow Apps to Request to Track"
  - Or reset your advertising identifier

### 2-2. Google Play Billing (in-app purchases — when added in V2)
- **Collected**: Payment information needed to process the transaction (Google account ID, payment method).
- **Used for**: Processing in-app purchases and refunds.
- **Operator**: Google LLC. Payment data is handled inside Google Play Billing; the App operator never stores it.

### 2-3. OpenAI Vision API (photo-based portion estimation)
- **What is sent**: When you tap "Scan food bowl" and take a photo, the App sends that single image to the OpenAI API (model: `gpt-4o-mini`) along with the selected food brand/product name as plain text. No cat profile, no feeding history, no device identifier, and no account information is attached.
- **What comes back**: A single integer (estimated grams). The App stores only that integer locally; the photo itself is **not** retained by the App.
- **OpenAI's handling**: Per OpenAI's API data policy, images submitted via the API are processed in transit and are **not used to train OpenAI's models**. See <https://openai.com/policies/api-data-usage-policies>.
- **Operator**: OpenAI, L.L.C. ([OpenAI Privacy Policy](https://openai.com/policies/privacy-policy)).
- **Demo mode**: When the App is built without an OpenAI API key, scans return a fixed demo value (58 g) and **no image leaves the device**.
- **Quota**: Free users are limited to 3 scans per day (KST calendar day). Pro subscribers and viewers of an optional rewarded ad receive additional scans. The quota counter is stored on-device only.

---

## 3. Data Retention and Deletion

- The App does not retain any data on remote servers.
- Cat profile and feeding-log data live in your device's local storage and are deleted when the App is uninstalled.

---

## 4. Sharing With Third Parties

The App does not share user data with third parties. The third-party SDKs listed in Section 2 collect data per their own policies, which the App operator does not control.

---

## 5. Children's Privacy

The App is not directed at children under 13 (COPPA). The App does not knowingly collect information from children under 13. If you believe a child has provided data via the App, contact us and we will delete it promptly.

---

## 6. Your Rights

- Inquire what data the App collects — none directly (see Section 2 for advertising identifier opt-out).
- Delete all local data — uninstall the App.

---

## 7. Privacy Contact

| Field | Value |
|---|---|
| Operator | Hyunwoo Jung |
| Email | chaosphch@gmail.com |
| Response time | Within 7 business days |

---

## 8. Changes to This Policy

This policy may be updated to reflect changes in law, technology, or App functionality. Updates will be posted on this page with a new "Last updated" date.

---

## 9. Revision History

- 2026-05-21 — Initial version
- 2026-05-26 — §2-3 rewritten to present-tense disclosure of the OpenAI Vision API integration; documented demo-mode behavior, daily quota, and which fields are/are not sent.

(End)
