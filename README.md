# Cortina Photo

A desktop photo editor for **Windows** and **Linux**: layers, masks, brushes, editable type, transforms and filters. It runs fully offline, with no account and no cloud.

**Website & downloads:** https://cortinaos.com/apps/cortina-photo/

## Download

Get the latest installer from the [Releases](../../releases/latest) page.

| Platform | File |
|---|---|
| Windows 10/11 (64-bit) | `CortinaPhoto-<version>-Setup-win-x64.exe` (installer) or `-Portable-win-x64.exe` |
| Linux (64-bit) | `CortinaPhoto-<version>-linux-x86_64.AppImage` or `cortina-photo_<version>_amd64.deb` |

Every release lists a **SHA-256 checksum** for each file. You can check that your download is genuine:

```bash
# Linux
sha256sum CortinaPhoto-*.AppImage
# Windows (PowerShell)
Get-FileHash .\CortinaPhoto-*-Setup-win-x64.exe -Algorithm SHA256
```

> **Windows note:** while the app is new, Windows SmartScreen may show "Windows protected your PC". Click **More info → Run anyway**. Only do this for files downloaded from this page or cortinaos.com.

## Install on Linux

```bash
sudo apt install ./cortina-photo_<version>_amd64.deb
# or
chmod +x CortinaPhoto-<version>-linux-x86_64.AppImage && ./CortinaPhoto-<version>-linux-x86_64.AppImage
```

## About this repository

This repository hosts **official release builds only**. The source code is not published here.

Cortina Photo is an independent product and is not affiliated with Adobe.

Made by Lexcore · © Lexcore Enterprises
