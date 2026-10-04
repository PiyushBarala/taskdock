# TaskDock

**A lightweight Windows tray app for tasks and focus sessions. Add, choose, focus, finish.**

TaskDock lives in your system tray. Press `Ctrl+Space`, type a task, pick what to do next, and run a focus session. Everything stays on your computer: no account, no internet required, no telemetry, no cloud sync.

> This repository only distributes installers for released versions. It contains no source code, accepts no pull requests and is not a place to discuss code.

## Download

**[Download the latest version](https://taskdock.piyushbarala.site/download/)** from the website, or get it directly from the [Releases page](../../releases/latest).

| File | For |
|---|---|
| `TaskDock_<version>_x64-setup.exe` | Most people. Per-user installer, no administrator rights needed. |
| `TaskDock_<version>_x64_en-US.msi` | IT teams and scripted installs. |

Every release also includes a `SHA256SUMS.txt` file with the checksum of each installer.

### Verify your download

Open PowerShell in the folder where you saved the installer and run:

```powershell
Get-FileHash .\TaskDock_<version>_x64-setup.exe -Algorithm SHA256
```

Compare the result with the matching line in `SHA256SUMS.txt` on the release page. If they differ, delete the file and download it again.

### Windows SmartScreen

Early builds are not code-signed, so Windows may show "Windows protected your PC". If you downloaded the file from this repository or the official website, choose **More info**, then **Run anyway**.

## Requirements

- Windows 10 (version 2004 or later) or Windows 11, 64-bit
- WebView2 runtime (already included in Windows 11 and current Windows 10)

## Features

- Global shortcut (`Ctrl+Space`) to add a task from anywhere
- Pick your next task, then run a focus session
- Upcoming, Projects, History and Calendar views
- Screen-share privacy: hide the window from screen sharing and recordings, and blur task names until you point at them
- Works fully offline, with no account

## Privacy

TaskDock stores your tasks only on your computer and makes no network requests of its own. Read the [Privacy Policy](https://taskdock.piyushbarala.site/privacy/).

The screen-share privacy option reduces what viewers can see, but it is not a guarantee against every capture method.

## Legal and help

- [Privacy Policy](https://taskdock.piyushbarala.site/privacy/)
- [Terms and Conditions](https://taskdock.piyushbarala.site/terms/)
- [End-user agreement](https://taskdock.piyushbarala.site/eula/)
- [Third-party notices](https://taskdock.piyushbarala.site/notices/)
- [Support and contact](https://taskdock.piyushbarala.site/support/)
- [Documentation](https://taskdock.piyushbarala.site/docs/)

## License

TaskDock is free to use. All rights are reserved by its publisher except as stated in the [End-user agreement](https://taskdock.piyushbarala.site/eula/).
