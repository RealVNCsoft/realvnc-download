<div align="center">

<img src="realvnc-logo.webp" alt="RealVNC" width="300">

# RealVNC Viewer &amp; Server for Windows

### One package. Two tools for remote access.

Original Windows installers for **RealVNC Viewer 8.5.3** and **RealVNC Server 2.4.1**, together in one ZIP.

[![Latest release](https://img.shields.io/github/v/release/RealVNCsoft/realvnc-download?label=latest%20release&color=3157d5)](https://github.com/RealVNCsoft/realvnc-download/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/RealVNCsoft/realvnc-download/total?color=3157d5)](https://github.com/RealVNCsoft/realvnc-download/releases)
[![Windows](https://img.shields.io/badge/platform-Windows-3157d5)](#package-contents)
[![Signed installers](https://img.shields.io/badge/installers-Authenticode%20signed-16865b)](#integrity-checks)

[⬇️ Download package](https://github.com/RealVNCsoft/realvnc-download/releases/latest) ·
[📋 All releases](https://github.com/RealVNCsoft/realvnc-download/releases) ·
[🌐 Product page](https://realvncsoft.github.io/)

</div>

---

## 📦 Package contents

| Product | Version | Included installer | Use |
|---|---:|---|---|
| **RealVNC Viewer** | `8.5.3` | `RealVNC-Connect-Viewer-8.5.3-Windows.msi` | Connect from a Windows computer to a computer you are authorized to access. |
| **RealVNC Server** | `2.4.1` | `VNC-Server-Installer-2.4.1-Windows.exe` | Enable remote access on a computer you own or are authorized to manage. |

Viewer and Server are separate products and can be installed independently. The release ZIP contains both original installers without modifications.

## ⬇️ Download

Choose **RealVNC Viewer 8.5.3 + Server 2.4.1** on the [Releases page](https://github.com/RealVNCsoft/realvnc-download/releases/latest) and download:

- `RealVNC-Connect-Windows-8.5.3-2.4.1.zip` — the two Windows installers.
- `SHA256SUMS.txt` — SHA-256 checksums for the ZIP and both installers.

## 🚀 Quick start

1. Download the ZIP package and extract it.
2. To connect to another computer, run `RealVNC-Connect-Viewer-8.5.3-Windows.msi`.
3. To enable access on a computer you manage, run `VNC-Server-Installer-2.4.1-Windows.exe`.
4. Follow the setup prompts and sign in or configure access as required by your RealVNC subscription.

Only configure or connect to computers you own or are authorized to manage.

## 🛡️ Integrity checks

Both installer files have valid Authenticode signatures from **RealVNC Ltd**. Check the package checksum before extracting:

```powershell
Get-FileHash .\RealVNC-Connect-Windows-8.5.3-2.4.1.zip -Algorithm SHA256
```

Compare the result with the ZIP entry in [`SHA256SUMS.txt`](SHA256SUMS.txt). To verify the extracted installers too:

```powershell
Get-FileHash .\RealVNC-Connect-Viewer-8.5.3-Windows.msi -Algorithm SHA256
Get-FileHash .\VNC-Server-Installer-2.4.1-Windows.exe -Algorithm SHA256
```

## 📜 License and trademarks

RealVNC Viewer and Server are proprietary software. Use is governed by the applicable [RealVNC End User License Agreement](https://www.realvnc.com/en/legal/) and subscription terms. RealVNC and VNC are trademarks of RealVNC Ltd.

## 🔗 Links

| Resource | Link |
|---|---|
| Latest download | [GitHub Releases](https://github.com/RealVNCsoft/realvnc-download/releases/latest) |
| Release history | [All releases](https://github.com/RealVNCsoft/realvnc-download/releases) |
| Product page | [realvncsoft.github.io](https://realvncsoft.github.io/) |
| Profile | [RealVNCsoft](https://github.com/RealVNCsoft) |
