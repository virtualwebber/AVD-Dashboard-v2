# AVD Live Dashboard 2026-11-10.35

**Release Date** 10 November 2026

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

**Checksums**

SHA256 - 1B4832B6BE6B3F9F1FA2A5926E8AD71A0F89AE1A8BEB9DC85B32464AB1A88D92

**VirusTotal Result**

https://www.virustotal.com/gui/file/1b4832b6be6b3f9f1fa2a5926e8ad71a0f89ae1a8beb9dc85b32464ab1a88d92/detection

0 malicious / 0 suspicious of 70 engines

To check a download: `Get-FileHash .\AVD-Dashboard.exe -Algorithm SHA256`