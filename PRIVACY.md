Privacy Policy for Bluetooth Remote App

Last updated: 2026-08-16

Introduction

This Privacy Policy explains how the Bluetooth Remote app ("we", "us", "the app") collects, uses, and shares information when you install and use the app. The app lets your Android phone act as a Bluetooth HID (mouse, keyboard, gamepad) and optionally connect to a remote "companion" over the internet. Respecting your privacy and giving you control are core priorities.

Data We Collect

- Bluetooth device identifiers: When you pair/connect to hosts (PCs, TVs, consoles) the app saves their Bluetooth address and display name locally to make reconnecting easier ("Remembered Hosts").
- Pairing codes: Pairing codes are generated locally on-device to establish an internet companion link and are stored locally.
- Camera preview state: If you enable the optional internet companion and the companion views your phone camera, the app stores a flag that the camera is active. Camera frames are streamed only to an explicitly paired companion and only after you give consent.
- Procedures & macros: When you record "remembered steps" (macros), the actions are stored locally as an encoded payload. You can export, import, save, or delete these procedures. Exported payloads are encoded text you can share manually.
- Stored pastes & keyboard suggestions: Text snippets you save in the app and lightweight usage counters used to surface keyboard suggestions are stored locally on the device.
- Settings & preferences: App settings (sensitivity, scroll speed, custom tabs/buttons, pad layout, blocklist, internet/companion settings, etc.) are persisted locally using Android DataStore.
- License verification: The app may perform local license verification (for example, via a localhost check) — only verification state and failure messages are used to control features; no external telemetry is sent by that check itself.

How We Use Data

- Local convenience: Data listed above is used to provide core app functionality — reconnecting to hosts, honoring your custom buttons/tabs, replaying saved macros, suggesting frequently used paste text, and restoring settings across app restarts.
- Companion link: Pairing codes and signaling URLs are used only to establish an optional companion link so a remote companion can control or view the phone when explicitly allowed by you.
- Camera streaming: Camera frames are streamed to an explicitly paired and consented companion. The app includes an owner-side kill switch to stop the camera at any time.

Data Sharing & Third Parties

- The app does not sell or share your personal data for advertising or marketing.
- Exported procedures and any text you explicitly share are shared by you and not transmitted by the app to third parties automatically.
- If you use the internet companion feature, data sent to the companion (input events, optional camera preview) goes to the remote peer you pair with via the signaling mechanism. The app does not forward camera data to arbitrary third parties — only to the paired companion.
- We may use third-party open-source libraries packaged with the app; those libraries operate locally on the device. Read their licenses for details.

Retention

- All persistent data described above is stored on the device by default. You can delete saved procedures, stored pastes, and remembered hosts from within the app. To remove a Bluetooth pairing completely you may also need to use the device's system Bluetooth settings.

Security

- We take reasonable precautions to protect data stored on the device. Pairing codes, blocklist, and remembered hosts are stored in app-private storage.
- Camera streams and companion links use the signaling URL and established pairing codes; however, network security depends in part on the companion you connect to and the network path. Do not use the companion feature with parties you do not trust.

Your Choices

- Companion consent: The internet companion feature is opt-in and gated by a one-time consent prompt. You can disable the companion link at any time via the app settings.
- Camera kill switch: An owner-side kill switch is available to stop camera streaming immediately.
- Export & delete: You can export or delete stored procedures and stored pastes at any time.
- Blocklist: You can add host addresses to a blocklist to prevent them from being shown as remembered hosts or re-advertised.

Children

- The app is not intended for children under 13. We do not knowingly collect personal information from children under 13.

Changes to This Policy

We may update this policy to reflect changes in the app or legal requirements. When we do, the date at the top will be updated.

Contact

For questions, corrections, or data removal requests, open an issue on the project repository or contact the app maintainer. Replace this placeholder with your preferred contact: maintainer@example.com

Notes for Play Store

When publishing to the Play Store, include this policy link (once published to GitHub Pages or any static hosting) in the "Privacy Policy" field of your Play Console listing.
