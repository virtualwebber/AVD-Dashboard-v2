# AVD Live Dashboard 2026-11-11.12

**Release Date** 11 November 2026

---

**Overview**

A live dashboard for Azure Virtual Desktop. One window shows your host pools, session hosts, user sessions,
workspaces and app groups, scaling plans, images, costs and more, and lets you act on them (drain, start,
restart, add hosts, create host pools and so on). It is a native Windows app and the C# edition of the
PowerShell AVD Live Dashboard.

**Requirements**

- Windows 10 or 11 (64-bit), or Windows Server 2016 or later. Nothing to install - the .NET runtime is inside the exe.
- An Azure account (Microsoft Entra ID sign-in, MFA supported) with access to the subscription. Viewing needs read access; changes need the matching permissions.
- Internet access to Azure (Azure Resource Manager and Microsoft Entra sign-in). Updates are checked on GitHub.
- A config file (`*.psd1`) in a `config` folder next to the exe, or in `%APPDATA%\AVDDashboard\config`.

---

**Executable**

AVD-Dashboard.exe (60 MB, standalone - nothing to install)

Download: https://github.com/virtualwebber/AVD-Dashboard-v2/releases/latest

**Checksums**

SHA256 - 1EB01ED1D2C3237D954EC7DC54A73B17B22BA2F75A21BC090EAA0EDC814CA37C

**VirusTotal Result**

https://www.virustotal.com/gui/file/1eb01ed1d2c3237d954ec7dc54a73b17b22ba2f75a21bc090eaa0edc814ca37c/detection

0 malicious / 0 suspicious of 70 engines (existing report)

To check a download: `Get-FileHash .\AVD-Dashboard.exe -Algorithm SHA256`