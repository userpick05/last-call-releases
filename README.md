# Last Call ? release feed

This repository is **only** a version signal and a download.

It carries `latest.json` (a version string and release notes) plus the built
Android APK as a release asset. There is **no source code here** ? the app's
source is private.

The app fetches `latest.json` anonymously to tell you when a newer build
exists. It never sends anything, and the download link the app opens is
hardcoded into the app itself, so a tampered feed cannot redirect you
somewhere else.

Nothing in this repo can read your data. The app's data lives in a private
Firebase project locked to a single account.
