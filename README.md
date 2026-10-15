# Zensu Session Hub for macOS

Official downloads and app updates for Zensu Session Hub.

## Requirements

- macOS 14 Sonoma or later.
- An Apple Silicon or Intel Mac.

## Download and install

1. Open the [latest release](https://github.com/MKITConsulting/zensu-session-hub-releases/releases/latest).
2. Under **Assets**, download the `.dmg` installer for your Mac:

   | Mac | Choose the DMG ending in |
   | --- | --- |
   | Apple Silicon (M-series) | `aarch64-apple-darwin.dmg` |
   | Intel | `x86_64-apple-darwin.dmg` |

3. Open the DMG and drag **Zensu Session Hub** into **Applications**.
4. Launch the app from Applications and follow the setup prompts.

Release installers are signed and notarized for macOS. SHA-256 checksums accompany the downloads. To check a downloaded installer, run `shasum -a 256` followed by its file path in Terminal and compare the result with the release checksum.

## Update the app

Open **Settings → App updates** in the installed app. Enable **Check automatically**, or select **Check for updates** whenever you want. When an update is available, finish any active Hub operation, select **Download and install**, then **Restart now** to use the new version.

You can also update manually: quit Session Hub, download the newer DMG for your Mac from the [latest release](https://github.com/MKITConsulting/zensu-session-hub-releases/releases/latest), and replace the copy in Applications.

This repository contains public release downloads and update information. The source code is maintained in a separate private repository.
