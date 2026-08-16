# Privacy Policy — Bluetooth Remote

_Last updated: 2026-08-16_

This is the publicly hosted copy of the app's privacy policy. Use this URL in your Play Console's "Privacy Policy" field after you push and enable GitHub Pages for this repository (see instructions below).

## Summary

The Bluetooth Remote app stores connection metadata (remembered hosts, pairing codes), saved macros and text snippets, and user settings on your device. The optional internet companion link and camera preview are strictly opt-in and require explicit consent. You control exports, deletes, and blocklists.

## What we collect

- Bluetooth addresses and display names of hosts you pair with (locally stored).
- Pairing codes for the internet companion (generated and stored locally).
- Procedures/macros and exported payloads (stored locally; export is manual).
- Stored paste snippets and keyboard usage counters (local only).
- Settings and preferences (local DataStore).
- Local license verification state used to enable app features.

## How it is used

Data is used for app functionality: reconnecting, macros, custom buttons, pad layout, and companion pairing. Camera frames are sent only to the paired companion when you explicitly allow the camera.

## Sharing

The app does not share or sell your personal data. Exported procedures and any manual user-shared text are shared by the user. If you enable the companion, input events and optional camera frames are sent to the paired remote peer.

## Security & retention

Data is stored in app-private storage. You can delete stored procedures, pastes, and remembered hosts from the app. To fully remove a Bluetooth pairing you may need to use system Bluetooth settings.

## Your choices

- Disable or re-enable the internet companion in settings.
- Revoke camera access by using the owner-side kill switch.
- Export or delete saved procedures and stored pastes.
- Add addresses to the blocklist.

## Contact

Replace `maintainer@example.com` with your contact email for privacy requests.

---

### How to publish this page on GitHub Pages

1. Commit and push this repository to GitHub.
2. In the repository Settings → Pages, set the source to the `docs/` folder on the `main` (or default) branch.
3. Save. GitHub will publish at `https://<your-username>.github.io/<repo-name>/privacy.html` (or `/privacy/` depending on renderer).
4. Copy the published URL into the Play Console's Privacy Policy field.

If you prefer a dedicated `gh-pages` branch instead of `docs/`, move or copy `privacy.md` into that branch and enable Pages from that branch.
