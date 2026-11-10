# AVD Live Dashboard 2026-11-10.49

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

SHA256 - 60E1C3C1AA0E16418C968FF01989A7F4DE05FA99068BCB270C8F2D918D965CB5

**VirusTotal Result**

https://www.virustotal.com/gui/file/60e1c3c1aa0e16418c968ff01989a7f4de05fa99068bcb270c8f2d918d965cb5/detection

0 malicious / 0 suspicious of 70 engines

To check a download: `Get-FileHash .\AVD-Dashboard.exe -Algorithm SHA256`