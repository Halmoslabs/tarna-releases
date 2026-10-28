# Tarna

Keyboard navigation for your Mac. Press **Shift–Command–Period**, then type a hint to choose a control. Tarna combines native control discovery with automatic text recognition that runs on your Mac.

## Download

**[Download Tarna 1.0.4 for Mac (.dmg)](https://github.com/Halmoslabs/tarna-releases/releases/download/v1.0.4/Tarna-1.0.4-macos.dmg)** · [ZIP download](https://github.com/Halmoslabs/tarna-releases/releases/download/v1.0.4/Tarna-1.0.4-macos.zip) · [Release notes and checksums](https://github.com/Halmoslabs/tarna-releases/releases/tag/v1.0.4)

Requires **macOS 14 or later**. The download supports Apple silicon and Intel, is signed by Halmos Labs, Inc., and is notarized by Apple.

1. Open the DMG and drag **Tarna** to **Applications**.
2. Open Tarna and grant Accessibility and Screen Recording when prompted.
3. Press **Shift–Command–Period** to show hints. Press **Escape** to dismiss them.

For scrolling, show hints first, press **Shift–S**, and choose an area. Use **J/K/H/L** to scroll; **Escape** finishes. In the direct edition, detected scroll areas receive a subtle outline after 1.5 seconds with hints open, or immediately when selecting a scroll area.

Change the hint and scrolling shortcuts in **Settings → Shortcuts**. The page groups them by when they work: anywhere, while hints are open, or after selecting a scroll area. Restore Defaults brings back the original bindings.

For updates, open Tarna's menu-bar menu and choose **Check for Updates…**, or use **Settings → General**. Automatic checks can be turned on or off there. Downloads and the update feed are cryptographically signed; automatic installation is off by default.

The standalone edition includes Sparkle for secure updates. [Third-party software notices](THIRD-PARTY-NOTICES.txt) are included with its downloads.

## Editions

- **Direct download:** native Accessibility targeting, menu-bar hints, automatic local text recognition, grouped lists, and selected-area scrolling. Signed updates are delivered through Sparkle.
- **Mac App Store:** a separate sandboxed edition using local text recognition and a precision grid for unlabeled controls. It does not inspect other apps’ Accessibility trees. Updates come from the App Store. This edition is in preparation and is not yet available.

Requires macOS 14 or later. Release builds support Apple silicon and Intel. Coverage depends on the interface; recognized text is not necessarily clickable.

[Privacy](PRIVACY.md) · [Support](SUPPORT.md)

This repository contains official downloads and public release information. Tarna’s application source is maintained in a separate private repository.

Copyright © 2026 Halmos Labs, Inc.
