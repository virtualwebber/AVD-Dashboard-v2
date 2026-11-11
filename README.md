# AVD Live Dashboard 2026-11-11.7

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

SHA256 - 0A294B970D67432C2F53E648808A4C15A81B07B6DBEA4A7F4DDFCD240C1FF33B

**VirusTotal Result**

https://www.virustotal.com/gui/file/0a294b970d67432c2f53e648808a4c15a81b07b6dbea4a7f4ddfcd240c1ff33b/detection

0 malicious / 0 suspicious of 65 engines

To check a download: `Get-FileHash .\AVD-Dashboard.exe -Algorithm SHA256`