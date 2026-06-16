# Privacy Policy — Baby Firsts

**Last updated:** 16 June 2026
**App:** Baby Firsts
**Developer:** GrizPlay (Rohit Singh)
**Contact:** alwaysrohitsingh@gmail.com
**Package:** com.grizplayapp.babyfirsts

---

## 1. Overview

Baby Firsts is an offline baby milestone journal. We built it with one clear principle: **your baby's memories belong to you, not us.**

Everything you record — your baby's name, date of birth, milestones, notes, and keepsake cards — is stored only on your device. We do not have servers. We do not collect this data. We cannot see it.

---

## 2. Data We Collect

### 2.1 Data stored only on your device

The following data is saved to your phone's local storage (AsyncStorage) and never leaves your device:

| Data | Purpose | Storage key |
|------|---------|-------------|
| Baby profiles (name, date of birth, emoji) | Core app function | `@bf/profiles`, `@bf/active` |
| Milestone records (title, date, note) | Core app function | `@bf/records/{babyId}` |
| Onboarding completion flag | Skip onboarding on relaunch | `@bf/onboarded` |
| Theme preference (dark/light/system) | UI personalisation | `@bf/theme_mode` |

**We never transmit any of the above data to any server — ours or anyone else's.**

### 2.2 Data collected by third-party services

**Google AdMob (advertising)**
Baby Firsts displays banner advertisements powered by Google AdMob. AdMob may collect:
- Advertising ID (a resettable device identifier)
- Approximate location (if granted by OS)
- General device information (OS version, screen size)
- Ad interaction data (impressions, clicks)

This data is collected by Google, not by us. We request **non-personalised ads only** (`requestNonPersonalizedAdsOnly: true`). Google's privacy policy applies to this data:
[https://policies.google.com/privacy](https://policies.google.com/privacy)

You can reset or opt out of ad tracking in your device settings:
- **Android:** Settings → Privacy → Ads → Reset Advertising ID / Opt out of Ads Personalisation

---

## 3. Data We Do NOT Collect

We explicitly confirm we do **not** collect:

- Baby names, dates of birth, or any profile information
- Milestone records, notes, or keepsake card content
- Photos (no photo feature exists in v1.0)
- Location data
- Analytics or usage events
- Crash reports (errors are logged to the device console only)
- Email addresses or any contact information
- Any data that identifies you or your child to us

---

## 4. How Data Is Used

All locally stored data (Section 2.1) is used solely to provide the app's core features:
- Displaying your baby's milestone list and timeline
- Generating keepsake card images for sharing
- Remembering your theme preference

We have no access to this data and cannot use it for any purpose.

---

## 5. Sharing Keepsake Cards

The "Share" feature in Baby Firsts generates a PNG image of a keepsake card on your device using `react-native-view-shot`. When you share this image:

- The image is created locally on your device
- It is shared via your device's native share sheet (WhatsApp, Messages, etc.)
- **We do not receive, store, or see the image**
- The recipient app's privacy policy governs what they do with the image

---

## 6. Children's Privacy

Baby Firsts is designed for **parents and guardians** to record their baby's milestones. The intended users of this app are adults.

We do not knowingly collect data from children under 13. All baby data (name, DOB, milestones) is stored exclusively on the parent's device and is never transmitted to us.

Baby Firsts complies with the **Children's Online Privacy Protection Act (COPPA)** and **GDPR** because we collect no personal data from any user, adult or child.

If you believe we have inadvertently collected information from a child, please contact us at alwaysrohitsingh@gmail.com and we will address it promptly. (Though as noted above, we have no servers and receive no data.)

---

## 7. Data Security

Since all personal data remains on your device:
- Your data is protected by your device's own security (screen lock, encryption)
- No data is in transit to be intercepted
- No server can be breached to expose your data

If you lose your phone or uninstall the app, your data is lost. We recommend keeping your device backed up.

> **Android backup note:** We have disabled automatic Google cloud backup (`android:allowBackup="false"`) to prevent your baby's data from being uploaded to Google's servers without your knowledge.

---

## 8. Data Retention and Deletion

All data is stored locally on your device.

- **To delete a milestone:** Long-press it on the Timeline screen → confirm deletion
- **To delete a baby profile:** Contact us (v1.1 — account deletion UI coming)
- **To delete all data:** Uninstall the app. All AsyncStorage data is removed automatically.

We retain no data on our side because we receive none.

---

## 9. Your Rights

Since we hold no personal data, the standard data rights (access, correction, deletion, portability) are all in your hands — you access, edit, and delete your data directly in the app.

For GDPR purposes: we act as neither data controller nor data processor for your personal baby data, as we never receive it.

For questions about AdMob data collected by Google, contact Google directly or review their privacy controls at [https://myaccount.google.com/data-and-privacy](https://myaccount.google.com/data-and-privacy).

---

## 10. Third-Party Links

The Settings screen in Baby Firsts contains links to other GrizPlay apps on the Google Play Store. Visiting those links is governed by Google Play's privacy policy. We do not track which links you click.

---

## 11. Changes to This Policy

We will update this policy if we add features that affect data collection (e.g., photo attachments, cloud backup). When we do:
- The "Last updated" date at the top will change
- If the change is material, we will note it in the app update release notes

Continued use of the app after any change constitutes acceptance of the updated policy.

---

## 12. Contact

If you have questions about this privacy policy:

**Email:** alwaysrohitsingh@gmail.com
**App:** Baby Firsts — GrizPlay
**Play Store:** https://play.google.com/store/apps/details?id=com.grizplayapp.babyfirsts

We aim to respond within 48 hours.

---

## Changelog

| Date | Change |
|------|--------|
| 16 Jun 2026 | Initial policy published for v1.0.0 launch |

---

*Baby Firsts is part of the GrizPlay portfolio of offline-first Android apps.*
