---
title: Recipe Keeper — Privacy Policy
layout: default
permalink: /recipe-keeper/privacy-policy.html
---

# Privacy Policy — Recipe Keeper

**Effective date**: (replace with launch date — YYYY-MM-DD)
**Last updated**: 2026-05-28

Recipe Keeper ("the App") respects your privacy. This document explains what information the App collects, how it is used, and how it is protected. The App complies with the Google Play Data Safety requirements and the COPPA principles for U.S. distribution.

---

## 1. Personal Information We Collect

**The App does not directly collect personal information.**

- No account creation or sign-in is required.
- Your recipes, ingredients, steps, cookbooks, grocery items, and source URLs are **stored only on your device** and never transmitted to any server.
- The App does not request your name, email, phone number, or any identifying information.

---

## 2. Automatically Collected Information (Third-Party SDKs)

The App includes third-party services to display advertising, process in-app purchases, and (for Pro subscribers) parse photographed recipes. These services may automatically collect limited information:

### 2-1. Google AdMob (advertising)
- **Collected**: Advertising identifier (AAID on Android), device information (model, OS version, language), approximate location (country-level).
- **Used for**: Personalized ad delivery, ad performance measurement, fraud prevention.
- **Operator**: Google LLC ([Google Privacy Policy](https://policies.google.com/privacy)).
- **Opt-out**:
  - Android: Settings → Google → Ads → "Opt out of Ads Personalization"
  - Or reset your advertising identifier
- **Pro subscribers see no ads**, so no AdMob data is collected from Pro users.

### 2-2. Google Play Billing & RevenueCat (in-app purchases)
- **Collected**: Payment information needed to process the transaction (Google account ID, payment method) by Google. An anonymous subscriber ID (random UUID, generated on first launch) by RevenueCat to track entitlement status.
- **Used for**: Processing the Pro subscription, restoring purchases on re-install, and detecting cancellations.
- **Operators**: Google LLC + RevenueCat, Inc. ([RevenueCat Privacy Policy](https://www.revenuecat.com/privacy)). Payment data is handled inside Google Play Billing; the App operator never stores it.

### 2-3. OpenAI Vision API (Pro photo-to-recipe import)
- **What is sent**: When a Pro subscriber taps "Import from photo" and takes a picture of a recipe (cookbook page, handwritten card, web screenshot), the App sends **that single image** to the OpenAI API (model: `gpt-4o-mini`). No saved recipes, cookbooks, grocery items, or device identifier are attached.
- **What comes back**: A structured text breakdown — title + ingredients (amount/unit/name) + steps. The App parses this through the same ingredient-normalization logic used for manual entry and saves the result locally; **the photo itself is not retained by the App**.
- **OpenAI's handling**: Per OpenAI's API data policy, images submitted via the API are processed in transit and are **not used to train OpenAI's models**. See <https://openai.com/policies/api-data-usage-policies>.
- **Operator**: OpenAI, L.L.C. ([OpenAI Privacy Policy](https://openai.com/policies/privacy-policy)).
- **Demo / Free mode**: Free users do not see the Import-from-photo button. When the App is built without an OpenAI API key, the button is also hidden and **no image ever leaves the device** even for Pro users.
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

The App does not share user data with third parties. The third-party SDKs listed in Section 2 collect data per their own policies, which the App operator does not control.

When you tap "Export backup (JSON)", the resulting file is handed to the Android share sheet — *you* choose where it goes (Google Drive, email, etc). The App itself does not upload it.

---

## 6. Children's Privacy

The App is not directed at children under 13 (COPPA). The App does not knowingly collect information from children under 13. If you believe a child has provided data via the App, contact us and we will delete it promptly.

---

## 7. Your Rights

- Inquire what data the App collects — none directly (see Section 2 for advertising identifier opt-out and Section 2-3 for Pro photo-import disclosure).
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
