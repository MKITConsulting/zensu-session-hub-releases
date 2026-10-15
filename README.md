# Zensu Session Hub for macOS

Official downloads and app updates for Zensu Session Hub.

The first public release is being prepared. Installers will appear on the [Releases page](https://github.com/MKITConsulting/zensu-session-hub-releases/releases). Once available, [Download the latest release](https://github.com/MKITConsulting/zensu-session-hub-releases/releases/latest) will take you to the current version.

## Requirements

- macOS 14 Sonoma or later.
- An Apple Silicon or Intel Mac.

## Download and install

Choose the DMG for your Mac from the release assets:

| Mac | Installer filename |
| --- | --- |
| Apple Silicon (M-series) | `Zensu-Session-Hub-<version>-aarch64-apple-darwin.dmg` |
| Intel | `Zensu-Session-Hub-<version>-x86_64-apple-darwin.dmg` |

Open the DMG, drag **Zensu Session Hub** into **Applications**, then launch it from Applications and follow the setup prompts.

Release installers are signed and notarized for macOS. SHA-256 checksums accompany the downloads. To check a downloaded installer, run `shasum -a 256` followed by its file path in Terminal and compare the result with the release checksum.

## Update the app

Open **Settings → App updates** in the installed app. Enable **Check automatically**, or select **Check for updates** whenever you want. When an update is available, finish any active Hub operation, select **Download and install**, then **Restart now** to use the new version.

You can also update manually: quit Session Hub, download the newer DMG for your Mac, and replace the copy in Applications.

This repository contains public release downloads and update information. Source code is maintained separately.
