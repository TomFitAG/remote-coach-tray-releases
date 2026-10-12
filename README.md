# Remote Coach tray app

Releases of the Remote Coach tray app for TOM·FIT coaches, for macOS (Apple Silicon and Intel) and Windows.
This repository holds the release files only.

## Install or update

macOS, in Terminal:

```bash
curl -fsSL https://github.com/TomFitAG/remote-coach-tray-releases/releases/latest/download/install.sh | bash
```

Windows, in PowerShell:

```powershell
irm https://github.com/TomFitAG/remote-coach-tray-releases/releases/latest/download/install.ps1 | iex
```

Run the same command again to update to the latest release. The installer checks the download against its
SHA-256 checksum and installs nothing when it does not match.

## Uninstall

macOS, in Terminal:

```bash
curl -fsSL https://github.com/TomFitAG/remote-coach-tray-releases/releases/latest/download/uninstall.sh | bash
```

Windows, in PowerShell:

```powershell
irm https://github.com/TomFitAG/remote-coach-tray-releases/releases/latest/download/uninstall.ps1 | iex
```
