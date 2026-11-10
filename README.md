# AVD Live Dashboard 2026-11-10.48

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

SHA256 - 83F6760E6FF85DF1DA0C73A89D09647E1B594A31C01EC84F5EDE48F66CD9FF2D

**VirusTotal Result**

https://www.virustotal.com/gui/file/83f6760e6ff85df1da0c73a89d09647e1b594a31c01ec84f5ede48f66cd9ff2d/detection

0 malicious / 0 suspicious of 68 engines

To check a download: `Get-FileHash .\AVD-Dashboard.exe -Algorithm SHA256`