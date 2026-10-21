# VOXA Installation & User Guide

**English** · [简体中文](./VOXA-User-Guide.zh-CN.md)

VOXA turns an Apple TV Siri Remote into a remote input device for your Mac, with button mapping, touch controls, Shortcuts integration, and configurable scenes.

Microphone Edition (paid) lets you use the built-in microphone on a supported Apple TV Siri Remote directly as a microphone input on your Mac.

## System Requirements

- Apple Silicon Mac (M1, M2, M3, M4, or newer)
- macOS 13 Ventura or later
- Apple TV Siri Remote paired with the Mac over Bluetooth

> The current installer is arm64-only. It supports Apple Silicon Macs and does not support Intel Macs.

## Installation

1. Download `VOXA-2.0.1-Build93.dmg` from [Releases](https://github.com/jinzongma/apple-tv-remote-for-mac/releases/latest).
2. Double-click the DMG to open it.
3. Drag `Voxa.app` into the Applications folder shown on the right.
4. Open Applications in Finder and double-click `Voxa.app`.

## First Use

1. Open VOXA.
2. Grant Accessibility and Input Monitoring permissions when prompted. After changing permissions, quit VOXA completely and reopen it.
3. In macOS System Settings → Bluetooth, confirm that the Siri Remote is connected.
4. Open Mapping in VOXA, select a remote button, and configure its action.
5. To use different mappings by app, add apps under Scenes and enable automatic switching.

## Updating an Older Version

1. Quit VOXA if it is running.
2. Open the new DMG.
3. Drag the new `Voxa.app` into Applications and choose Replace.
4. Reopen VOXA. Existing button mappings and settings are normally preserved.

## Troubleshooting

### Button Mappings Do Not Respond

Check that Accessibility and Input Monitoring permissions are enabled, then quit VOXA completely and reopen it. Avoid keeping multiple copies of the same VOXA version.

### Siri Remote Is Not Found

In macOS System Settings → Bluetooth, confirm that the remote is paired and shown as connected, then return to VOXA and reconnect.

## Version Information

- Current version: **VOXA 2.0.1 (Build 93)**
- Installer: Developer ID signed and notarized by Apple
- SHA-256: `aea8c6a39604fefa6bf5e55bd54bdcdc1d5da42ebab21ac33914da1e98e74240`

## Contact

For questions or feedback, email [huabeijinzongma@icloud.com](mailto:huabeijinzongma@icloud.com).
