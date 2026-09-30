# Pixel Grabber

Screenshot, annotation, color picking and floating reference tools for graphic designers, by DesignByKazbo. Formerly TintShot.

**Recommended beta: [Pixel Grabber 0.5.0 Beta 10](https://github.com/KazboXIII/TintShot/releases/tag/v0.5.0-beta.10)**

- [Download the Windows x64 installer](https://github.com/KazboXIII/TintShot/releases/download/v0.5.0-beta.10/PixelGrabber-0.5.0-beta.10-Setup-x64.exe) — recommended for installation and built-in updates.
- [Download the portable Windows x64 ZIP](https://github.com/KazboXIII/TintShot/releases/download/v0.5.0-beta.10/PixelGrabber-0.5.0-beta.10-Portable-x64.zip) — extract and run TintShot.exe.
- [Feature guide](https://github.com/KazboXIII/TintShot/releases/download/v0.5.0-beta.10/FEATURE-GUIDE.txt), [beta notes](https://github.com/KazboXIII/TintShot/releases/download/v0.5.0-beta.10/BETA-NOTES.txt), [tester guide](https://github.com/KazboXIII/TintShot/releases/download/v0.5.0-beta.10/TESTER-GUIDE.txt), and [SHA-256 checksums](https://github.com/KazboXIII/TintShot/releases/download/v0.5.0-beta.10/SHA256SUMS.txt).

Beta 10 adds editable .pgproject files and reversible crops, on-device Windows OCR, saved .pgboard reference boards, optional automatic export rules with retry, and image drag-out to compatible apps. Use the Workspace menu and controls below the editor; automatic exports are configured in Settings > Export.

It also includes the previously unpublished Beta 9 improvements: background PNG saves, reused asynchronous thumbnails, capture visibility settings and startup update prompts. The rounded dark workspace, lavender accents, 175% fullscreen toolbar and dedicated Pen button remain.

Requires Windows 10 version 1809 or newer / Windows 11, Intel or AMD x64, and .NET Framework 4.8. OCR requires installed Windows OCR language support. ARM Windows is unsupported in this beta. The application and installer are unsigned.

- **Ctrl+Shift+2:** capture a region and annotate it on screen.
- **Ctrl+Shift+3:** pick a screen color.
- **Ctrl+Shift+1:** open the design desk.
- **Ctrl+,** or the tray menu: settings and customizable shortcuts.

Close the previous Pixel Grabber, TintShot or Surge Capture copy before installing. Upgrades preserve your library, settings, startup preference and installation folder. **Beta 4/5 users should install Beta 10 manually once** because those older builds can fail HTTPS update checks.

Installed copies check GitHub Releases at startup and periodically; you choose when to install. Settings > Updates controls automatic checks and beta releases. Enable beta releases to receive Beta 10. Downloads are checked against GitHub's SHA-256 asset digest. Portable copies require manual replacement or installation.

The repository remains **KazboXIII/TintShot** for updater compatibility. The internal executable remains **TintShot.exe**, and data stays in `%LOCALAPPDATA%\SurgeCapture`. TintShot-named release downloads are byte-identical compatibility aliases; use the branded downloads above.

**Editable projects retain original pixels underneath redactions and outside crops.** For redacted delivery, use flattened PNG, Copy or Drag image with opaque Cover annotations. Blur and mosaic are visual effects, not secure redaction. Undo history is session-local. Drag-cache files last at least 48 hours; export permanent linked assets to a permanent folder.

OCR runs locally. There are no capture uploads or telemetry. Closing the main window hides the app in the tray by default; use the tray's Quit command to exit.

This repository distributes releases and product documentation. Older releases remain available. See the release notes for tested coverage and remaining manual checks, including final-installer installation, receiving-app drag behavior, mixed-DPI/HDR capture and additional OCR languages. The packaged feature guide's local-only statement describes its preparation; Beta 10 is now distributed through the linked prerelease.
