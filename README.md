# Stamp4Doc Desktop

> Privacy-first PDF desktop toolkit — watermark, encrypt, and convert. Everything runs locally; your files are never uploaded.

[![License](https://img.shields.io/badge/license-proprietary-blue.svg)](https://github.com/dean-coding/stamp4doc-desktop)
[![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Windows-lightgrey.svg)](#)
[![Version](https://img.shields.io/badge/version-1.0.7-green.svg)](#)

## Overview

Stamp4Doc Desktop is a PDF processing application for individuals and teams. All file operations are performed entirely on your local machine — nothing is ever uploaded to a server, keeping your documents private by design.

Core features:

- 🖼️ **PDF Watermarking** — Add text or image watermarks with customizable opacity, rotation, and tiling density
- 🔒 **PDF Encryption** — Password-protect PDFs with AES encryption
- 📝 **Markdown to PDF** — Render Markdown into professionally typeset PDFs
- 💻 **Code to PDF** — Export source code to PDF with syntax highlighting
- 📦 **Batch Processing** — Watermark or encrypt multiple files at once
- 💾 **Template Manager** — Save watermark templates for one-click reuse

## Download & Install

Grab the installer for your platform from the [Releases](https://github.com/dean-coding/stamp4doc-desktop/releases) page:

| Platform | Architecture | File |
|----------|--------------|------|
| macOS | Apple Silicon (arm64) | `stamp4doc-arm64.dmg` |
| macOS | Intel (x64) | `stamp4doc-x64.dmg` |
| Windows | x64 | `stamp4doc-x64.exe` |

### macOS

Open the `.dmg` file and drag Stamp4Doc into your Applications folder.

> If macOS warns that the developer cannot be verified, go to **System Settings → Privacy & Security** and click **Open Anyway**.

### Windows

Run the `.exe` installer and follow the prompts.

## Local-First & Privacy

Stamp4Doc Desktop is built on a **local-first** principle:

- ✅ All PDF processing happens locally — files are never uploaded
- ✅ No document content is collected
- ✅ No third-party analytics or tracking
- ✅ Works offline (except for license activation)

## Licensing

Stamp4Doc Desktop is commercial software and requires a license key to activate. Purchase a license from the [Stamp4Doc website](https://stamp4doc.netlify.app).

License tiers:

- **Personal** — single device
- **Team** — multiple devices, team collaboration

## Building from Source

This repository contains release artifacts only. To view or modify the source code, please contact the development team.

Build scripts:

```bash
# Build macOS installer
npm run dist:mac

# Build Windows installer
npm run dist:win

# Build all platforms
npm run dist
```

## Tech Stack

- **Framework**: Electron + React 19
- **Bundler**: Vite + electron-vite
- **PDF Engine**: native local PDF engine
- **Packager**: electron-builder

## System Requirements

- **macOS**: 11.0 or later
- **Windows**: 10 or later

## Feedback & Support

- Issues: [GitHub Issues](https://github.com/dean-coding/stamp4doc-desktop/issues)
- Website: [stamp4doc.netlify.app](https://stamp4doc.netlify.app)

## Changelog

See the [Releases](https://github.com/dean-coding/stamp4doc-desktop/releases) page.

---

© 2026 Stamp4Doc. All rights reserved.
