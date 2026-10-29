# Pixel Grabber

Screenshot, annotation, screen recording, color picking and floating reference tools for graphic designers, by DesignByKazbo.

**Latest beta: [Pixel Grabber 0.9.0 Beta 19](https://github.com/KazboXIII/PixelGrabber/releases/tag/v0.9.0-beta.19)**

- [Download the Windows x64 installer](https://github.com/KazboXIII/PixelGrabber/releases/download/v0.9.0-beta.19/PixelGrabber-0.9.0-beta.19-Setup-x64.exe): recommended for installation and built-in updates.
- [Download the portable Windows x64 ZIP](https://github.com/KazboXIII/PixelGrabber/releases/download/v0.9.0-beta.19/PixelGrabber-0.9.0-beta.19-Portable-x64.zip): extract and run PixelGrabber.exe.
- [Feature guide](https://github.com/KazboXIII/PixelGrabber/releases/download/v0.9.0-beta.19/FEATURE-GUIDE.txt), [beta notes](https://github.com/KazboXIII/PixelGrabber/releases/download/v0.9.0-beta.19/BETA-NOTES.txt), [tester guide](https://github.com/KazboXIII/PixelGrabber/releases/download/v0.9.0-beta.19/TESTER-GUIDE.txt) and [SHA-256 checksums](https://github.com/KazboXIII/PixelGrabber/releases/download/v0.9.0-beta.19/SHA256SUMS.txt).

## What's in Beta 19

- **Screen recording** to a looping GIF or an H.264 MP4, with pause, a timer and an optional pointer.
- **Share links** to Imgur, Catbox or your own uploader. Off by default; every upload asks first.
- **Identify font**: rank the closest fonts installed on your PC for text in an image.
- **Interface colors**: Midnight, Graphite, Slate or Black, plus any custom accent color.
- **Text in place**: type directly on the image and recolor it while typing.

Earlier betas added editable projects, on-device text extraction (Windows OCR), reference boards, automatic exports, color notations with a contrast check, and framed exports.

## Shortcuts

- **Ctrl+Shift+2:** capture a region and annotate it on screen.
- **Ctrl+Shift+3:** pick a screen color.
- **Ctrl+Shift+4:** record the screen.
- **Ctrl+Shift+1:** open the design desk.
- **Ctrl+,** or the tray menu: settings and customizable shortcuts.

## Requirements and updates

Requires Windows 10 version 1809 or newer / Windows 11, Intel or AMD x64, and .NET Framework 4.8. Text extraction and font identification need installed Windows OCR language support. ARM Windows is unsupported. The app and installer are unsigned.

Close Pixel Grabber before installing. Upgrades keep your library, settings, startup choice and install folder; data lives in `%LOCALAPPDATA%\PixelGrabber`. Installed copies check this page's releases and let you choose when to install. Settings > Updates controls automatic checks and beta releases. Downloads are checked against GitHub's SHA-256 asset digest. Portable copies need manual replacement.

## Privacy and limits

Text extraction and font identification run on your PC. Nothing is uploaded unless you set up and confirm a share link, and there is no telemetry.

**Editable projects keep the original pixels underneath redactions and outside crops.** For redacted delivery, use a flattened PNG, Copy or Drag image with opaque Cover annotations. Blur and mosaic are visual effects, not secure redaction.

This repository distributes releases and product documentation. Older releases remain available.
