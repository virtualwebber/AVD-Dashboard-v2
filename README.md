# AVD Live Dashboard 2026-11-11.14

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

SHA256 - 12993BF42F7CC86F1DB8966CC0DE547538CA3D062E8843348E7555228939DFEE

**VirusTotal Result**

https://www.virustotal.com/gui/file/12993bf42f7cc86f1db8966cc0de547538ca3d062e8843348e7555228939dfee/detection

0 malicious / 0 suspicious of 70 engines (existing report)

To check a download: `Get-FileHash .\AVD-Dashboard.exe -Algorithm SHA256`