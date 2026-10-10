---
title: Smidgen — Privacy Policy
layout: default
permalink: /recipe-keeper/privacy-policy.html
---

# Privacy Policy — Smidgen

**Effective date**: 2026-10-10
**Last updated**: 2026-10-10

Smidgen ("the App") respects your privacy. This document explains what information the App collects, how it is used, and how it is protected. The App complies with the Google Play Data Safety requirements and the COPPA principles for U.S. distribution.

---

## 1. Personal Information We Collect

**The App does not directly collect personal information.**

- No account creation or sign-in is required.
- Your recipes, ingredients, steps, cookbooks, grocery items, and source URLs are **stored on your device**, and the App never transmits them to any server.
- If backup to your Google account is turned on in Android's settings, Android may include the App's data in that device backup. That copy is kept in your Google account under Google's terms; the App operator cannot access it.
- The App does not request your name, email, phone number, or any identifying information.

---

## 2. Automatically Collected Information (Third-Party SDKs)

The App includes third-party services to display advertising and recognize text in photos on your device. These services may automatically collect limited information. Photo-to-recipe import never sends your photo or the text read from it — recognition runs entirely on your device (see Section 2-2):

### 2-1. Google AdMob (advertising)
- **Collected**: Advertising identifier (AAID on Android) and app set ID, IP address (used to estimate your approximate location), device information (model, OS version, language), your interactions with ads (impressions, taps), and diagnostic information about the app's and the SDK's performance. On Android versions that support it, the SDK may also use Android's Privacy Sandbox ad topics and ad measurement features.
- **Used for**: Ad delivery (personalized where your device settings allow it), ad performance measurement, analytics, fraud prevention.
- **Operator**: Google LLC ([Google Privacy Policy](https://policies.google.com/privacy)).
- **Opt-out**:
  - Android 12 and later: Settings → Google → Ads → Delete advertising ID
  - Earlier Android versions: Settings → Google → Ads → "Opt out of Ads Personalization", or Reset advertising ID
- AdMob and Google ML Kit (diagnostics only — see Section 2-2) are the only third-party services that receive data in the current release.

### 2-2. Photo-to-recipe import (on-device — your photo is never transmitted)
- **How it works**: When you tap the camera button ("Import from a photo") on the New Recipe or Edit Recipe screen and take a picture of a recipe, the App reads the text **on your device** using Google ML Kit text recognition. The image is never uploaded, and no recipe text is sent anywhere.
- **No third-party operator receives it**: no server, no API call, and no account is involved.
- **ML Kit diagnostics**: The recognition model is bundled inside the App, so nothing is downloaded to read a photo. Google's ML Kit SDK does send Google diagnostic and usage data — device model and OS version, app package and version, a per-installation identifier (not designed to identify you or your device), performance metrics such as latency, and error codes — over an encrypted connection, and Google does not pass it to other third parties. It never includes the photo or the recognized text. Operator: Google LLC ([ML Kit data disclosure](https://developers.google.com/ml-kit/android-data-disclosure)).
- **Availability**: photo import is unlimited. It requires no API key and costs nothing to run.
- **You stay in control**: The App first shows you the title, ingredients and steps it read from the photo and fills in nothing until you accept them. Every accepted import then lands on the Recipe Edit screen for review and manual correction before save.

---

## 3. Notifications

Smidgen does **not** schedule any reminders or push notifications. The App requests no notification permission and posts nothing to the Android notification shade.

---

## 4. Data Retention and Deletion

- The App operator keeps no data on servers; the App has none.
- Recipes, ingredients, steps, cookbooks, and grocery items live in your device's local storage and are deleted when the App is uninstalled. A copy that Android's device backup made (Section 1) is managed in your Google account, not by the App, and Android may restore it if you reinstall the App.
- The App provides a built-in **Export backup (JSON)** feature so you can take a copy of all your data with you before uninstalling.
- The **Restore from backup** feature replaces all current data with the contents of a backup file you select. This is irreversible from inside the App; keep an exported backup if you want to undo.

---

## 5. Sharing With Third Parties

The App operator does not sell your data and runs no server of its own. Data is, however, transferred to third parties by the SDKs listed in Section 2 — Google AdMob receives the advertising identifier, approximate location, app-interaction and diagnostic information, which is why Google Play's Data safety section for this App reports those four items as both collected and shared. Google ML Kit receives the diagnostic data and per-installation identifier described in Section 2-2. Your recipes, photos, cookbooks and grocery items are never part of that transfer.

When you tap "Export backup (JSON)", the resulting file is handed to the Android share sheet — *you* choose where it goes (Google Drive, email, etc). The App itself does not upload it.

---

## 6. Children's Privacy

The App is not directed at children under 13 (COPPA). The App does not knowingly collect information from children under 13. If you believe a child has used the App, contact us; the App operator holds no data, and we will help you clear what the advertising SDK received (delete or reset the advertising ID, Section 2-1).

---

## 7. Your Rights

- Inquire what data the App collects — none directly (see Section 2 for advertising identifier opt-out and Section 2-2 for the on-device photo-import disclosure).
- Delete your data — delete a recipe from its screen (Delete), a cookbook from the Cookbooks tab (⋮ → Delete) and the grocery list from the Grocery tab (Clear all); to remove everything at once use Android Settings → Apps → Smidgen → Storage → Clear storage, or uninstall the App. A copy in Android's device backup (Section 1) is removed from your Google account's backup settings.
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
- 2026-09-04 — Photo text recognition moved on-device; Section 5 states what the SDKs receive.
- 2026-10-08 — Added the diagnostics Google ML Kit sends.
- 2026-10-09 — Updated for the free release: photo import is unlimited. The App was renamed Smidgen; what it collects is unchanged.
- 2026-10-10 — Android device backup, the full list of what AdMob receives, the in-app delete actions, and the Android 12+ advertising ID path.

(End)
