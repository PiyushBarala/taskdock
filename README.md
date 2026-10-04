# TaskDock

**A lightweight Windows tray app for tasks and focus sessions. Add, choose, focus, finish.**

TaskDock lives in your system tray. Press `Ctrl+Space`, type a task, pick what to do next, and run a focus session. Everything stays on your computer: no account, no internet required, no telemetry, no cloud sync.

> **This is not an open-source project.** This repository only stores the installers for released versions. It contains no source code, accepts no pull requests and is not a place to discuss code.

## Download

Get the latest installer from the website: **<https://taskdock.piyushbarala.site/download/>**

Or take it straight from this repository: the [`release`](release) folder holds every published version.

| File | For |
|---|---|
| `TaskDock_<version>_x64-setup.exe` | Most people. Per-user installer, no administrator rights needed. |
| `TaskDock_<version>_x64_en-US.msi` | IT teams and scripted installs. |

`release/latest.json` always describes the newest version, with each file's size and SHA-256 checksum. The website reads that file to offer the latest download.

### Verify your download

```powershell
Get-FileHash .\TaskDock_<version>_x64-setup.exe -Algorithm SHA256
```

Compare the result with the checksum on the download page or in `release/latest.json`.

### Windows SmartScreen

Early builds are not code-signed, so Windows may show &ldquo;Windows protected your PC&rdquo;. Choose **More info**, then **Run anyway**, if you downloaded the file from the links above.

## Requirements

- Windows 10 or 11, 64-bit
- WebView2 runtime (already part of Windows 11 and current Windows 10)

## Privacy

TaskDock stores your tasks only on your computer and makes no network requests of its own. Read the [Privacy Policy](https://taskdock.piyushbarala.site/privacy/).

## Legal and help

- [Privacy Policy](https://taskdock.piyushbarala.site/privacy/)
- [Terms and Conditions](https://taskdock.piyushbarala.site/terms/)
- [End-user agreement](https://taskdock.piyushbarala.site/eula/)
- [Third-party notices](https://taskdock.piyushbarala.site/notices/)
- [Support and contact](https://taskdock.piyushbarala.site/support/)
- [Documentation](https://taskdock.piyushbarala.site/docs/)

TaskDock is free to use. All rights are reserved by its publisher except as stated in the End-user agreement.
