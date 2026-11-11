# AVD Live Dashboard 2026-11-11.11

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

SHA256 - 52D1D3C1E75FE6590E07BABFAD6FA66EFCC3712BA809679E064096BDB773A65B

**VirusTotal Result**

https://www.virustotal.com/gui/file/52d1d3c1e75fe6590e07babfad6fa66efcc3712ba809679e064096bdb773a65b/detection

0 malicious / 0 suspicious of 65 engines (existing report)

To check a download: `Get-FileHash .\AVD-Dashboard.exe -Algorithm SHA256`