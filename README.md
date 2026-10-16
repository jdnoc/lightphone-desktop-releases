# Slight

An independent desktop messaging app for Light Phone II. Not affiliated with or endorsed by Light.

## Download for Mac

**[Download Slight 0.8.7 — Apple Silicon](https://github.com/jdnoc/lightphone-desktop-releases/releases/download/v0.8.7/Slight-0.8.7-macos-arm64.dmg)**

Requires macOS 13 or later and a supported Light Phone II. [Release notes, checksums, and setup sources](https://github.com/jdnoc/lightphone-desktop-releases/releases/tag/v0.8.7) · [Latest release](https://github.com/jdnoc/lightphone-desktop-releases/releases/latest)

Open the DMG, drag **Slight** into **Applications**, then open it and follow the phone setup steps. The Mac needs internet once during first-time EDL setup. No Docker, VM, Homebrew, Python, or Android tools need to be installed.

Slight supports SMS, image MMS, group conversations, contacts, and phone-only notes and recordings. Connections prefer USB, then direct Wi-Fi, then the optional encrypted relay over cellular or other Wi-Fi networks. Menu bar mode keeps notifications working with the window closed.

## Other platforms

Intel Mac, Windows, and Linux installers are not available yet. This release supports Light Phone II, not Light Phone III. RCS is not supported; notes are read-only.

## Updates and source

This repository hosts signed installers and the signed updater feed. For installation, choose the **.dmg** file; the other assets support updates, source distribution, and verification. In-app updates use this repository without a GitHub sign-in.

The GPLv3 Python/setup helper and complete pinned EDL and F2FS tool sources accompany each release. The separate desktop application and hosted service implementations remain in the private app repository. Phone backups, messages, pairing credentials, and signing keys are excluded.
