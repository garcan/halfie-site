---
title: Privacy Policy
lang: en
---

# Halfie Privacy Policy

[Türkçe](gizlilik) · [Support](./)

**Last updated:** October 19, 2026

## 1. Data controller

Hakan Kaya (individual developer) · email: [official.mediatv.tr@gmail.com](mailto:official.mediatv.tr@gmail.com)

## 2. In short

Halfie is an app for two paired people to share lists, notes, events and a chat.
**Your lists, notes, events, messages and the location you share in an emergency alert are end-to-end encrypted:**
they can only be read on your and your partner's phones. We (Halfie) cannot see this content.

We use **no** ads, analytics, tracking tools or third-party trackers. Your data is not sold.

## 3. Personal data we process

| Data | Why | Where | How long |
|---|---|---|---|
| Email address (shared by Apple when you Sign in with Apple; Apple's relay address if you choose "Hide My Email") | Your account | Server (Supabase, Frankfurt/EU) | Until the account is deleted |
| Display name (shared by Apple at first sign-in, or typed by you) | Showing your partner who you are | Server | Until the account is deleted |
| Sign in with Apple link token | Revoking the link at Apple when you delete your account | Server (not readable by anyone, including the app) | Revoked and deleted when the account is deleted |
| User ID, pairing information | Pairing you with your partner | Server | Until the account is deleted / pairing ends |
| Public encryption key | Letting your partner send you encrypted data | Server | Until the account is deleted |
| Encrypted packets (content unreadable) | Delivering changes to your partner | Server | Deleted once your partner receives them; at most 30 days |
| Packet metadata (from, to, when, size) | Delivery | Server | Deleted with the packet |
| Notification address (device token from Apple), app language, chosen notification sounds | Showing you a notification when your partner sends something | Server | Deleted when you sign out, delete your account, or Apple reports it invalid |
| Notification type and time (message / heart / gift / alert) | Sending the notification | Passes through our server and Apple, not stored | — |
| Lists, notes, events, messages | The app itself | **Only on your phones** | Until you delete them / the pairing ends |
| Location (only when you send an emergency alert) | So your partner can reach you | Encrypted, to your partner's phone | Together with the chat message |
| Your partner's phone number (if you enter it) | Calling from the chat | **Only on your own phone** | Until the pairing ends |

Notifications **never** contain message content; they only show the sender's name and a type such as "New message".

## 4. Optional features

- **iCloud backup (off by default):** If you turn it on, a copy of your data is encrypted on your phone and stored in
  **your own iCloud Drive**. The key is kept in iCloud Keychain. Halfie cannot access this file. You can turn it off in
  Settings → iCloud backup and delete it in iPhone Settings → iCloud.
- **Restore to a new phone:** When you switch phones, your shared data is sent to you end-to-end encrypted from your
  partner's phone, with their approval.
- **Purchases (Halfie+, gifts):** Payment is handled by Apple; we never see your card details. Sharing your
  subscription with your partner happens through an end-to-end encrypted packet; sharing ends when the pairing ends.

## 5. Transfers

Our server is hosted by Supabase Inc. in the European Union (Frankfurt). Notifications are processed by Apple Push
Notification Service, sign-in by Sign in with Apple, payments by the App Store, and the optional backup by iCloud (Apple Inc.). End-to-end encrypted
content cannot be read by any of these providers.

## 6. Your rights

To ask whether and how your data is processed, or to request correction, deletion or to object, email
[official.mediatv.tr@gmail.com](mailto:official.mediatv.tr@gmail.com).

**You can delete your account in the app:** Settings → Delete account. This permanently deletes your account,
pairing, keys, notification address and pending packets from the server, revokes your Sign in with Apple link, and deletes the data on your phone.
We cannot delete copies on your partner's phone or the backup in your own iCloud.

## 7. Security

Data in transit is protected by TLS, and content is additionally end-to-end encrypted (X25519 + ChaCha20-Poly1305).
Data on the phone is protected by iOS Data Protection. You can confirm that you and your partner use the same keys by
comparing the security code in Settings → End-to-end encryption.

## 8. Age

Halfie is for users aged 18 and over.

## 9. Changes

If this policy changes, we will announce it in the app and on this page.
