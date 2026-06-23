# Privacy Policy — Currency Converter

**Last updated:** 23 June 2026
**App:** Currency Converter
**Developer:** GrizPlay (Rohit Singh)
**Contact:** grizplayapp@gmail.com
**Package:** com.grizplayapp.currencyconverter

---

## 1. Overview

Currency Converter is an offline-first currency and crypto conversion tool. We built it with one clear principle: **your settings and conversion history belong to you, not us.**

Everything you configure — your base currency, favourite currencies, amounts, and conversion history — is stored only on your device. We do not have user accounts and we do not collect or see this data.

The only data this app sends over the network is an anonymous request for today's exchange rates — it contains no information about you.

---

## 2. Data We Collect

### 2.1 Data stored only on your device

The following data is saved to your phone's local storage (AsyncStorage) and never leaves your device:

| Data | Purpose | Storage key |
|------|---------|-------------|
| Theme preference (dark/light/system) | UI personalisation | `@cc/theme_mode` |
| Base currency | Core app function | `@cc/base` |
| Display currencies | Core app function | `@cc/display` |
| Favourite currencies | Core app function | `@cc/favorites` |
| Last entered amount | Restores your last conversion | `@cc/amount` |
| Cached exchange rates (today + previous day) | Offline access + trend badges | `@cc/rates`, `@cc/rates_prev`, `@cc/rates_date` |
| Conversion history (last 20) | Lets you revisit past conversions | `@cc/history` |
| Onboarding completion flag | Skip onboarding on relaunch | `@cc/onboarded` |

**We never transmit any of the above data to any server — ours or anyone else's.**

### 2.2 Exchange rate data (anonymous network request)

To show up-to-date conversion rates, the app fetches a public exchange-rate dataset from the **fawazahmed0/currency-api**, hosted on the jsDelivr CDN:

- No API key, login, or account is required
- The request contains no information that identifies you or your device
- It is a plain `GET` request for a static JSON file (the same file every user receives)
- If the request fails or you're offline, the app falls back to a rate snapshot bundled inside the app, then to your last cached rates

This is the only network call the app makes outside of advertising (see 2.3).

### 2.3 Data collected by third-party services

**Google AdMob (advertising)**
Currency Converter displays banner advertisements powered by Google AdMob. AdMob may collect:
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

- Your name, email, or any account information (the app has no accounts/login)
- Your location
- Analytics or usage events
- Crash reports (errors are logged to the device console only)
- Any data that identifies you when fetching exchange rates
- Photos, contacts, or files on your device

---

## 4. Permissions Used

| Permission | Why it's needed |
|------------|------------------|
| `INTERNET` | Fetch daily exchange rates and serve ads |
| `VIBRATE` | Haptic feedback on taps (e.g. selecting a currency) |

The app requests no camera, location, contacts, storage, or microphone permissions.

---

## 5. Sharing Conversions

The "Share" feature lets you send a converted amount to another app (WhatsApp, Messages, etc.) via your device's native share sheet. This is plain text generated locally on your device — **we do not receive, store, or see what you share.**

---

## 6. Children's Privacy

Currency Converter is a general-purpose utility tool not directed at children. We do not knowingly collect data from children under 13 — and as described above, we collect no personal data from any user, adult or child.

Currency Converter complies with the **Children's Online Privacy Protection Act (COPPA)** and **GDPR** because we collect no personal data from any user.

If you believe we have inadvertently collected information from a child, please contact us at grizplayapp@gmail.com and we will address it promptly.

---

## 7. Data Security

Since all personal settings and history remain on your device:
- Your data is protected by your device's own security (screen lock, encryption)
- No account data is in transit to be intercepted
- No server can be breached to expose your settings or history

> **Android backup note:** We have disabled automatic Google cloud backup (`android:allowBackup="false"`) to prevent your settings and history from being uploaded to Google's servers without your knowledge.

If you lose your phone or uninstall the app, your settings and history are lost.

---

## 8. Data Retention and Deletion

All data is stored locally on your device.

- **To remove a currency from your list:** Long-press it on the Converter screen
- **To clear your conversion history:** Use the clear option on the History screen
- **To delete all data:** Uninstall the app. All AsyncStorage data is removed automatically.

We retain no data on our side because we receive none.

---

## 9. Your Rights

Since we hold no personal data, the standard data rights (access, correction, deletion, portability) are all in your hands — you access, edit, and delete your data directly in the app.

For GDPR purposes: we act as neither data controller nor data processor for your personal data, as we never receive it.

For questions about AdMob data collected by Google, contact Google directly or review their privacy controls at [https://myaccount.google.com/data-and-privacy](https://myaccount.google.com/data-and-privacy).

---

## 10. Third-Party Links

The Settings screen contains links to other GrizPlay apps on the Google Play Store. Visiting those links is governed by Google Play's privacy policy. We do not track which links you click.

---

## 11. Changes to This Policy

We will update this policy if we add features that affect data collection (e.g., rate alerts requiring notification permissions, cloud sync). When we do:
- The "Last updated" date at the top will change
- If the change is material, we will note it in the app update release notes

Continued use of the app after any change constitutes acceptance of the updated policy.

---

## 12. Contact

If you have questions about this privacy policy:

**Email:** grizplayapp@gmail.com
**App:** Currency Converter — GrizPlay
**Play Store:** https://play.google.com/store/apps/details?id=com.grizplayapp.currencyconverter

We aim to respond within 48 hours.

---

## Changelog

| Date | Change |
|------|--------|
| 23 Jun 2026 | Initial policy published ahead of closed testing |

---

*Currency Converter is part of the GrizPlay portfolio of offline-first Android apps.*
