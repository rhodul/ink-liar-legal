---
title: Privacy Policy — Ink Liar
---

# Privacy Policy for Ink Liar

**Effective date:** 2026-04-20
**Last updated:** 2026-04-27

"Ink Liar" (the "App") is a free Android game published by Rastislav
Hodul ("we", "us", or "the Developer"). This privacy policy explains
what data the App collects, how that data is used, and your rights
regarding it.

The App is deliberately designed to collect as little data as possible.
We operate no servers, maintain no user accounts, and perform no custom
analytics or telemetry on our own infrastructure. The data footprint
described below comes almost entirely from two Google services the App
integrates: **Google AdMob** (for advertising) and **Google User
Messaging Platform** (UMP, for GDPR/CCPA consent management).

---

## 1. What we collect directly

**Nothing.** We do not collect, store, or transmit any personal data
to any server we control, because we operate no server. The App is a
self-contained Android application that runs entirely on your device.

## 2. What is stored locally on your device

The App stores the following in Android's DataStore preferences system,
on the device only:

- Your local **high score** (integer).
- Your preferences for game-mode toggles: "Stroop mode" (on/off),
  "Reduce motion" (on/off), "Mute sounds" (on/off), and "Difficulty
  mode" (Easy / Normal / Hard).
- Your consent state for advertising personalization (handled
  internally by Google's UMP SDK).

This data never leaves your device except through the Android system's
own auto-backup feature (see below) or through the Google advertising
services described in Section 4.

## 3. Android Auto-Backup

If you have Google-account-based automatic backup enabled on your
device (Settings → Google → Backup), the App's locally stored data may
be included in those backups, sent to Google Drive under your Google
Account's private storage. This is standard Android behavior, controlled
by you in your device's system settings. The App does not exempt any
data from backup — nothing it stores qualifies as sensitive information.
You can disable backup for the App in your device's system settings.

## 4. Google AdMob (advertising)

The App displays advertising served by **Google AdMob** (part of the
Google Mobile Ads SDK). AdMob is operated by Google LLC and is subject
to [Google's Privacy Policy](https://policies.google.com/privacy).

AdMob may collect and process the following when ads are served:

- Your **advertising ID** (AAID — a resettable identifier you control
  in Android system settings under *Privacy → Ads*).
- Your **IP address** and **approximate location** (derived from IP).
- Your **device information** — model, operating system version,
  language.
- Your **interactions with ads** (impressions, clicks).

This data is used by Google and its advertising partners to select and
measure advertising. It is not available to the Developer in a form
that personally identifies you. We see only aggregated, anonymized
metrics in our AdMob console.

The App displays three AdMob ad formats:

- **Banner** ads at the bottom of the game screen (shown continuously
  while you play).
- **Interstitial** ads after a fixed number of game-overs, no more often
  than once every two minutes.
- **App-Open** ads when you return to the App from the background, no
  more often than once every four hours, suppressed for the first 30
  seconds of a session, suppressed for 30 seconds after an interstitial,
  and suppressed entirely if you have not granted advertising consent.

All three formats are controlled by the consent dialog described in
Section 5, are served by Google AdMob, and share the data flows
described above.

For full details on Google's advertising data practices:
[Google Advertising Privacy & Terms](https://policies.google.com/technologies/ads).

## 5. Google User Messaging Platform (UMP) — consent

To comply with GDPR (EU/UK) and CCPA (California) requirements, the App
uses Google's **UMP SDK** to display a consent dialog on first launch
in affected jurisdictions. UMP determines whether consent is required,
records your choice, and communicates it to advertising partners so
they can personalize (or not personalize) ads accordingly.

You can revisit your consent choice at any time via the **"Privacy
options"** row that appears in the App's Settings dialog (visible only
in jurisdictions where consent management is required).

UMP is covered by Google's Privacy Policy referenced above.

## 6. What we do NOT do

For the avoidance of doubt, Ink Liar does **not**:

- Require or offer user accounts or sign-in.
- Operate a game server, online leaderboard, or multiplayer feature.
- Run any custom analytics or telemetry beyond what Google's SDKs send
  to Google as described above.
- Integrate with social media, email, contacts, the camera, or the
  microphone.
- Collect health, financial, biometric, or precise-location data.
- Sell your data to any third party the Developer controls.

## 7. Children

Ink Liar is **not directed at children under 13**. It carries an
age-appropriate content rating in the Google Play Store. We do not
knowingly collect personal data from children. If you are a parent or
guardian and believe your child has provided data through AdMob while
using the App, please contact us at the address below and we will
coordinate with Google to address it.

## 8. Your rights

**Local data.** Uninstalling the App removes all locally stored data
from the device. (Data in Android Auto-Backup, if enabled, may persist
in your Google Drive until the device is restored without the App, or
until you delete the backup from your Google Account.)

**Advertising consent.** You can re-open the consent dialog at any time
via Settings → **Privacy options** in the App (where applicable).

**Google-held data.** Because most data in scope is held by Google and
not by the Developer, your rights of access, correction, and deletion
under GDPR, CCPA, and similar laws are exercised through Google's own
tools:

- [Your Google Account Data & Privacy](https://myaccount.google.com/data-and-privacy)
- [Google Ads Settings](https://adssettings.google.com/)
- [Reset Advertising ID on Android](https://support.google.com/googleplay/android-developer/answer/6048248)

**California (CCPA) / Virginia (VCDPA) / similar state laws.** To the
extent these laws apply, you have the right to opt out of the "sale"
or "sharing" of personal information for targeted advertising. In the
App, this right is exercised through the UMP consent flow (Settings →
Privacy options).

## 9. Data retention

- **Local data:** retained on your device until you uninstall the App,
  clear its data via Android Settings, or delete associated backups
  from your Google Account.
- **Google AdMob data:** retained and processed per
  [Google's own retention policies](https://policies.google.com/technologies/retention).

The Developer retains no data directly, because the Developer collects
none.

## 10. Changes to this policy

We may update this privacy policy from time to time to reflect changes
in the App or in applicable law. Changes take effect on the date posted
as "Last updated" at the top of this document. Continued use of the App
after an update constitutes acceptance of the revised policy.

Historical versions of this document are available in the
[public Git history](https://github.com/rhodul/ink-liar-legal/commits/master/privacy-policy.md)
of its source repository.

## 11. Contact

For privacy questions specific to Ink Liar (questions about Google's
advertising services must be addressed to Google directly via the
links in Section 8):

**Developer:** Rastislav Hodul
**Email:** rhodul@idbase.com

---

*Ink Liar is published by Rastislav Hodul. The App is distributed via
the Google Play Store under the package name `com.gnugu.tapthecolor`.
This document's source repository:
[github.com/rhodul/ink-liar-legal](https://github.com/rhodul/ink-liar-legal).*
