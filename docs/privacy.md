---
title: slider — Privacy Policy
---

# slider Privacy Policy

_Last updated: 2026-04-29_

slider ("the app") is a local music player developed by individual
developer ("we"). The app plays audio files that you import yourself
from your own device or cloud storage; it does not stream music from
any service and does not require an account.

## What we do not collect

We do **not** collect, store, or transmit any of the following:

- Your name, email, phone number, or any account credentials
- Your music files, artwork, or library metadata
- Your playback history (what, when, how often you listened)
- Your playlists or ratings
- Advertising / tracking identifiers (IDFA / IDFV)
- Your device's IP address or precise location

All music files, library data (SQLite database), playlists, ratings,
play counts, and lyrics live exclusively on your device.

## What we do collect

### Anonymous crash diagnostics

If the app crashes unexpectedly, an anonymous crash report is sent to
[Sentry](https://sentry.io/) — a third-party error monitoring service —
to help us fix the bug. The report contains:

- Stack trace of the failing code
- iOS version, device model
- App version + build number
- Anonymous session marker (no user identifier)

Before the report leaves your device, our scrubber automatically
strips:

- The user's iOS Documents container path (varies per install)
- File URIs (e.g. paths to your music files)
- Long base64 blobs (security-scoped bookmark data)
- Local variables in stack frames (which may contain track titles)

We do not configure Sentry to collect IP addresses or user agents
(`sendDefaultPii: false`). Crash reports cannot be tied to an individual
user.

The scrubber runs locally on your device before any data leaves it; if
you stop using the app, no diagnostics are sent.

## Permissions

slider may request the following permissions on iOS:

- **Files / folder access** — only to read audio files you explicitly
  pick via the system Files browser or Share Sheet. The app cannot read
  your photos, contacts, location, microphone, or any other file
  outside what you've handed to it.

## Children's privacy

The app is rated 4+ and does not knowingly collect any personal
information from anyone, including children under 13.

## Changes to this policy

If we ever change what we collect, we'll update this page and bump the
"Last updated" date. Significant changes will also be highlighted in
the App Store release notes for the version that introduces them.

## Contact

Issues, questions, or removal requests:
<https://github.com/zerozoo-a/slider/issues>
