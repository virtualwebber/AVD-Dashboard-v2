# AVD Live Dashboard 2026-11-10.28

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

SHA256 - 4FF830BF52EBF14260B5D0281F140F9D3F073386222E4F8442A0D8397B5C8466

**VirusTotal Result**

https://www.virustotal.com/gui/file/4ff830bf52ebf14260b5d0281f140f9d3f073386222e4f8442a0d8397b5c8466/detection

0 malicious / 0 suspicious of 70 engines

To check a download: `Get-FileHash .\AVD-Dashboard.exe -Algorithm SHA256`