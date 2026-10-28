# Tarna support

Use [GitHub Issues](https://github.com/Halmoslabs/tarna-releases/issues/new) for bug reports and feature requests. Include your Tarna version, macOS version, whether you use the direct or App Store edition, and concise steps to reproduce the problem.

Issues are public. Please omit passwords, private documents, recognized screen text, and unredacted screenshots of personal information.

## Getting started

Press **Shift–Command–Period** to show hints. Type the displayed letters to choose a target. **Escape** dismisses hints. Large lists may show one group hint ending in `*`; choose that group to reveal its entries. **Backspace** returns to the previous selection level.

These are the default bindings. Open **Settings → Shortcuts** to change Show hints, Select scroll area (Select scroll point in the Store edition), and the four scrolling keys. Click a shortcut button and press the new combination. Escape cancels recording; Restore Defaults restores all six bindings. Duplicate and reserved shortcuts are rejected. **Show hints works anywhere. Select scroll area or point works only while hints are open, even when you assign it a Command or Control combination.**

The direct edition needs Accessibility for control discovery, clicks, and navigation keys. Screen Recording enables automatic on-device text recognition. The App Store edition instead uses Input Monitoring, clicking access, and Screen Recording; it does not read Accessibility trees. macOS presents clicking access under Accessibility in System Settings.

Use **Shift–S** in hint mode to select a scrolling area in the direct edition, or a scrolling point in the App Store edition. Then use **J/K/H/L** repeatedly to scroll; **Escape** finishes. The direct edition outlines detected scroll areas after 1.5 seconds with hints open and immediately during area selection. The selected area's guide displays your configured scrolling keys.

The Store edition also provides **Shift–G** for a precision grid: choose cells to narrow an area. At fine scale, move the crosshair with arrow keys or H/J/K/L (one point per press, or ten with Shift), then press Return to confirm. No cell selection clicks automatically. Return can also select the current region’s center before fine mode. Tab switches displays in grid mode.

Protected system interfaces can restrict input. Text recognition cannot determine whether every word is interactive. If a target moves before selection, Tarna cancels the stale action rather than clicking its former position.

## Updates

The direct edition includes **Check for Updates…** and **Automatically Check for Updates** in its menu and update controls in **Settings → General**. Update feeds and archives must pass signature verification before installation. The App Store edition updates through Apple’s App Store.
