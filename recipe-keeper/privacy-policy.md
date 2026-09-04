---
title: Recipe Keeper — Privacy Policy
layout: default
permalink: /recipe-keeper/privacy-policy.html
---

# Privacy Policy — Recipe Keeper

**Effective date**: 2026-09-04
**Last updated**: 2026-09-04

Recipe Keeper ("the App") respects your privacy. This document explains what information the App collects, how it is used, and how it is protected. The App complies with the Google Play Data Safety requirements and the COPPA principles for U.S. distribution.

---

## 1. Personal Information We Collect

**The App does not directly collect personal information.**

- No account creation or sign-in is required.
- Your recipes, ingredients, steps, cookbooks, grocery items, and source URLs are **stored only on your device** and never transmitted to any server.
- The App does not request your name, email, phone number, or any identifying information.

---

## 2. Automatically Collected Information (Third-Party SDKs)

The App includes third-party services to display advertising and process in-app purchases. These services may automatically collect limited information. Photo-to-recipe import is **not** one of them — it runs entirely on your device (see Section 2-3):

### 2-1. Google AdMob (advertising)
- **Collected**: Advertising identifier (AAID on Android), device information (model, OS version, language), approximate location (country-level).
- **Used for**: Personalized ad delivery, ad performance measurement, fraud prevention.
- **Operator**: Google LLC ([Google Privacy Policy](https://policies.google.com/privacy)).
- **Opt-out**:
  - Android: Settings → Google → Ads → "Opt out of Ads Personalization"
  - Or reset your advertising identifier
- **Pro subscribers see no ads**, so no AdMob data is collected from Pro users.
- This is the only third-party service that receives data in the current release.

### 2-2. Google Play Billing & RevenueCat (in-app purchases)
- **Collected**: Payment information needed to process the transaction (Google account ID, payment method) by Google. An anonymous subscriber ID (random UUID, generated on first launch) by RevenueCat to track entitlement status.
- **Used for**: Processing the Pro subscription, restoring purchases on re-install, and detecting cancellations.
- **Operators**: Google LLC + RevenueCat, Inc. ([RevenueCat Privacy Policy](https://www.revenuecat.com/privacy)). Payment data is handled inside Google Play Billing; the App operator never stores it.
- **Not active in the current release**: the Pro subscription is not yet purchasable, so no billing or subscriber data is collected today. This section describes the behaviour that begins when subscriptions are switched on.

### 2-3. Photo-to-recipe import (on-device — nothing is transmitted)
- **How it works**: When you tap "Import from photo" and pick or take a picture of a recipe, the App reads the text **on your device** using Google ML Kit text recognition. The image is never uploaded, and no recipe text is sent anywhere.
- **No third-party operator receives it**: no server, no API call, and no account is involved. Earlier drafts of this policy described a cloud vision service; the App no longer uses one, and no image has been transmitted by the released App.
- **Model delivery**: ML Kit's recognition model may be delivered through Google Play services on your device. That delivery carries no photo, no recipe text, and no identifier from the App.
- **Availability**: photo import is available on the free tier up to 3 imports per day; Pro removes that cap. It requires no API key and costs nothing to run.
- **You stay in control**: Every imported recipe lands on the Recipe Edit screen for review and manual correction before save. Unparseable items are explicitly flagged "needs review" rather than silently dropped.

---

## 3. Notifications

Recipe Keeper does **not** schedule any reminders or push notifications. The App requests no notification permission and posts nothing to the Android notification shade.

---

## 4. Data Retention and Deletion

- The App does not retain any data on remote servers.
- Recipes, ingredients, steps, cookbooks, and grocery items live in your device's local storage and are deleted when the App is uninstalled.
- The App provides a built-in **Export backup (JSON)** feature so you can take a copy of all your data with you before uninstalling.
- The **Restore from backup** feature replaces all current data with the contents of a backup file you select. This is irreversible from inside the App; keep an exported backup if you want to undo.

---

## 5. Sharing With Third Parties

The App operator does not sell your data and runs no server of its own. Data is, however, transferred to third parties by the SDKs listed in Section 2 — Google AdMob receives the advertising identifier, approximate location, app-interaction and diagnostic information, which is why Google Play's Data safety section for this App reports those four items as both collected and shared. Your recipes, photos, cookbooks, grocery items and backups are never part of that transfer.

When you tap "Export backup (JSON)", the resulting file is handed to the Android share sheet — *you* choose where it goes (Google Drive, email, etc). The App itself does not upload it.

---

## 6. Children's Privacy

The App is not directed at children under 13 (COPPA). The App does not knowingly collect information from children under 13. If you believe a child has provided data via the App, contact us and we will delete it promptly.

---

## 7. Your Rights

- Inquire what data the App collects — none directly (see Section 2 for advertising identifier opt-out and Section 2-3 for the on-device photo-import disclosure).
- Delete all local data — uninstall the App, or use Settings → Restore from backup with an empty bundle.
- Export your data — Settings → Export backup (JSON).

---

## 8. Privacy Contact

| Field | Value |
|---|---|
| Operator | Hyunwoo Jung |
| Email | chaosphch@gmail.com |
| Response time | Within 7 business days |

---

## 9. Changes to This Policy

This policy may be updated to reflect changes in law, technology, or App functionality. Updates will be posted on this page with a new "Last updated" date.

---

## 10. Revision History

- 2026-05-28 — Initial version (closed-test launch prep).

(End)
