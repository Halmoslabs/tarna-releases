# Tarna privacy

Tarna Privacy
Updated 26 October 2026

Tarna processes your interface on your Mac. It has no account system, advertising, or analytics SDK. Screen content and keyboard input are never uploaded. The standalone edition contacts GitHub to check for and download signed software updates.

Accessibility
With your permission, Tarna reads the foreground app’s accessible controls and exposed menu-bar items to create keyboard hints. Selecting a hint can focus, click, or scroll the chosen control. Tarna checks the current target again before acting.

Screen Recording
With your permission, Tarna captures the foreground window to recognize visible text using Apple Vision on your Mac. This runs during idle preparation as well as hint sessions so hints can appear quickly. Images are transient and are not saved. Tarna retains recent text labels, coordinates, and an image fingerprint in memory for reuse; they are replaced as the interface changes and disappear when the app quits.

Keyboard and mouse input
Tarna listens for its shortcut and consumes hint keys while navigation is active. Outside hint mode, ordinary keys pass through unchanged. Input activity invalidates prepared hints; Tarna does not record ordinary typed text, maintain a keystroke history, or learn a personal usage profile.

Local diagnostics
macOS unified logs may contain performance durations, target counts, process identifiers, and error codes. Tarna does not log recognized text, screenshots, control titles, or ordinary typed keys. It does not automatically send diagnostics anywhere.

Your controls
You can revoke Accessibility and Screen Recording in System Settings → Privacy & Security. You can quit Tarna from its menu-bar menu to stop all processing. It does not start itself at login. Sparkle includes helpers used only to securely download and install updates.

Apple’s operating-system services and any support correspondence you choose to send are governed separately. This notice describes the Tarna app itself.

Software updates
The standalone edition uses Sparkle to check a public HTTPS feed hosted by GitHub. GitHub receives ordinary connection information, such as your IP address, when the app checks or downloads updates; its own privacy policy governs its service. System profiling is disabled. No interface content, recognized text, or typed keys are included. Update archives and the feed must be cryptographically signed. You can turn automatic checks off in Tarna's menu and check manually instead. Automatic installation is off by default; you can opt in through Sparkle's update interface.

---

Tarna Privacy — Mac App Store edition
Updated 26 October 2026

Tarna provides keyboard navigation using visible text and a precision grid. It processes everything on your Mac. It has no account system, advertising, analytics SDK, or network client. Updates come only from the Mac App Store.

Screen Recording
With your permission, Tarna captures your displays and recognizes visible words with Apple Vision. It excludes its own hint overlays from these captures. Recognition runs during quiet preparation as well as hint sessions. Images are transient and are never saved or uploaded. Recent text labels, coordinates, and image fingerprints remain in memory briefly for reuse and disappear when Tarna quits. The app does not inspect another app’s accessibility tree.

Input Monitoring and clicking access
Input Monitoring lets Tarna recognize its shortcut and hint keys. Clicking access appears under Accessibility in System Settings and lets Tarna post the click or scroll you request. These are Core Graphics event permissions. Ordinary keys pass through outside navigation; Tarna does not record typed text or maintain a keystroke history.

Target checking
Before activating recognized text, Tarna verifies that the same text remains in the same place and that the underlying window has not changed. Grid clicks and scrolling check the current window geometry. Text recognition does not prove a word is clickable; the precision grid lets you choose unlabeled targets explicitly. macOS restricts actions in protected interfaces, including some Open and Save dialogs.

Local diagnostics
macOS unified logs may contain timing values, counts, error codes, and process identifiers. They do not contain recognized text, screenshots, or ordinary typed keys. Tarna does not send diagnostics anywhere.

Your controls
You can revoke Input Monitoring, clicking access, or Screen Recording in System Settings → Privacy & Security. Quit Tarna from its menu-bar menu to stop all processing. Tarna does not install a helper, launch at login, or store files outside its app container.

Apple’s operating-system and App Store services, and any support correspondence you choose to send, are governed separately. This notice describes the Tarna app itself.
