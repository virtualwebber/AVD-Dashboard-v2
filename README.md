# AVD Live Dashboard 2026-11-12.14

**Release Date** 12 November 2026

---

**Overview**

A live dashboard for Azure Virtual Desktop. One window shows your host pools, session hosts, user sessions,
workspaces and app groups, scaling plans, images, costs and more, and lets you act on them (drain, start,
restart, add hosts, create host pools and so on). 

**Screenshots**

Sample data (Contoso); light and dark themes.

| Light | Dark |
| --- | --- |
| ![Per Host Pool](screenshots/dashboard.png) | ![Per Host Pool, dark theme](screenshots/dashboard-dark.png) |
| *Per Host Pool: summary strip, host pools and the selected pool's details and actions* | |
| ![Session Hosts](screenshots/session-hosts.png) | ![Session Hosts, dark theme](screenshots/session-hosts-dark.png) |
| *Session Hosts: status, sessions and users, CPU / memory / disk / input delay heat map* | |

**Several subscriptions at once**

Pick more than one in Switch subscription: each gets a card (with a switch to hide it) and a Subscription column.

![Per Host Pool, three subscriptions](screenshots/dashboard-3subs.png)

![Session Hosts, three subscriptions](screenshots/session-hosts-3subs.png)

**Requirements**

- Windows 10 or 11 (64-bit), or Windows Server 2016 or later. Nothing to install - the .NET runtime is inside the exe.
- An Azure account (Microsoft Entra ID sign-in, MFA supported) with access to the subscription. Viewing needs read access; changes need the matching permissions.
- Internet access to Azure (Azure Resource Manager and Microsoft Entra sign-in). Updates are checked on GitHub.
- A config file (`*.psd1`) in a `config` folder next to the exe, or in `%APPDATA%\AVDDashboard\config`.

---

**Executable**

AVD-Dashboard.exe (60.2 MB, standalone - nothing to install)

Download: https://github.com/virtualwebber/AVD-Dashboard-v2/releases/latest

**Checksums**

SHA256 - A73D968C2D2CF2E5AB80341C1DD573036557F31E93D59868DAB4EEFA8EE0F7B2

**VirusTotal Result**

This build was not scanned.

To check a download: `Get-FileHash .\AVD-Dashboard.exe -Algorithm SHA256`