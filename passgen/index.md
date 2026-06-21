# Privacy Policy — PassGen

**Last updated:** 21 June 2026
**App:** PassGen — Secure Password Generator
**Developer:** GrizPlay (Rohit Singh)
**Contact:** alwaysrohitsingh@gmail.com
**Package:** com.grizplayapp.passgen

---

## 1. Overview

PassGen is an offline password generator and strength checker. We built it with one clear principle: **your passwords belong to you, not us.**

Every password PassGen generates or analyses — and your history, settings, and theme preference — is stored only on your device. We do not have servers. We do not collect this data. We cannot see it.

---

## 2. Data We Collect

### 2.1 Data stored only on your device

The following data is saved to your phone's local storage (AsyncStorage) and never leaves your device:

| Data | Purpose | Storage key |
|------|---------|-------------|
| Password history (last 20, masked by default) | Core app function | `@pg/history` |
| Generator settings (mode, length, character options) | Remember your preferences on reopen | `@pg/settings` |
| Theme preference (dark/light/auto) | UI personalisation | `@pg/theme_mode` |
| Onboarding completion flag | Skip onboarding on relaunch | `@pg/onboarded` |

**We never transmit any of the above data to any server — ours or anyone else's.**

### 2.2 Data collected by third-party services

**Google AdMob (advertising)**
PassGen displays banner advertisements powered by Google AdMob. AdMob may collect:
- Advertising ID (a resettable device identifier)
- Approximate location (if granted by OS)
- General device information (OS version, screen size)
- Ad interaction data (impressions, clicks)

This data is collected by Google, not by us. Google's privacy policy applies to this data:
[https://policies.google.com/privacy](https://policies.google.com/privacy)

You can reset or opt out of ad tracking in your device settings:
- **Android:** Settings → Privacy → Ads → Reset Advertising ID / Opt out of Ads Personalisation

---

## 3. Data We Do NOT Collect

We explicitly confirm we do **not** collect:

- The passwords you generate or type in to check
- Analytics or usage events
- Crash reports (errors are logged to the device console only)
- Email addresses or any contact information
- Location data
- Any data that identifies you to us

---

## 4. How Data Is Used

All locally stored data (Section 2.1) is used solely to provide the app's core features:
- Showing your password history so you can copy a previously generated password again
- Remembering your generator mode/length/character preferences between sessions
- Remembering your theme preference

We have no access to this data and cannot use it for any purpose.

---

## 5. Sharing

The "Share" buttons in PassGen use your device's native share sheet (`Share.share()`) to send text — never an image, never a network request.

- **Generate tab:** sharing includes the generated password itself, plus its strength stat — this is a deliberate convenience for sending a password to yourself or someone you trust via another app (e.g. Signal, WhatsApp)
- **Strength tab:** sharing deliberately **excludes** the password you typed — only the strength label, crack time, and entropy are shared, since a password you're actively checking is more likely to be one you actually use elsewhere
- In both cases, the share text is generated locally and handed directly to the OS share sheet — **we do not receive, store, or see what you share, or who you share it with**
- The recipient app's privacy policy governs what they do with the shared text

---

## 6. Children's Privacy

PassGen is a general-purpose utility intended for users capable of managing their own passwords. It is not directed at children under 13, and we do not knowingly collect data from children under 13 — though as described above, we collect no personal data from any user, adult or child.

PassGen complies with the **Children's Online Privacy Protection Act (COPPA)** and **GDPR** because we collect no personal data from any user.

If you believe we have inadvertently collected information from a child, please contact us at alwaysrohitsingh@gmail.com and we will address it promptly. (Though as noted above, we have no servers and receive no data.)

---

## 7. Data Security

Since all your data remains on your device:
- Your data is protected by your device's own security (screen lock, encryption)
- No data is in transit to be intercepted
- No server can be breached to expose your data

If you lose your phone or uninstall the app, your data is lost.

> **Android backup note:** We have disabled automatic Google cloud backup (`android:allowBackup="false"`) to prevent your password history from being uploaded to Google's servers without your knowledge.

---

## 8. Data Retention and Deletion

All data is stored locally on your device.

- **To delete one history entry:** tap the trash icon on that entry in the History tab
- **To delete all history:** "Clear all history" at the top of the History tab
- **To delete everything:** Uninstall the app. All AsyncStorage data is removed automatically.

We retain no data on our side because we receive none.

---

## 9. Your Rights

Since we hold no personal data, the standard data rights (access, correction, deletion, portability) are all in your hands — you access, edit, and delete your data directly in the app.

For GDPR purposes: we act as neither data controller nor data processor for your password data, as we never receive it.

For questions about AdMob data collected by Google, contact Google directly or review their privacy controls at [https://myaccount.google.com/data-and-privacy](https://myaccount.google.com/data-and-privacy).

---

## 10. Third-Party Links

The Settings screen in PassGen contains links to other GrizPlay apps on the Google Play Store. Visiting those links is governed by Google Play's privacy policy. We do not track which links you click.

---

## 11. Changes to This Policy

We will update this policy if we add features that affect data collection (e.g., cloud sync, breach-checking against an online database). When we do:
- The "Last updated" date at the top will change
- If the change is material, we will note it in the app update release notes

Continued use of the app after any change constitutes acceptance of the updated policy.

---

## 12. Contact

If you have questions about this privacy policy:

**Email:** alwaysrohitsingh@gmail.com
**App:** PassGen — GrizPlay
**Play Store:** https://play.google.com/store/apps/details?id=com.grizplayapp.passgen

We aim to respond within 48 hours.

---

## Changelog

| Date | Change |
|------|--------|
| 21 Jun 2026 | Rewritten to match the full GrizPlay policy template (sections, AdMob disclosure, COPPA/GDPR, allowBackup note) |
| 21 Jun 2026 | Initial policy published |

---

*PassGen is part of the GrizPlay portfolio of offline-first Android apps.*
