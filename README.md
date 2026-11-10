# AVD Live Dashboard 2026-11-10.18

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

AVD-Dashboard.exe (59.9 MB, standalone - nothing to install)

**Checksums**

SHA256 - 16172747AF0493B30B4856B71B202AE891F4C32D5D56A256AD193EBE5B0F1BA6

**VirusTotal Result**

https://www.virustotal.com/gui/file/16172747af0493b30b4856b71b202ae891f4c32d5d56a256ad193ebe5b0f1ba6/detection

0 malicious / 0 suspicious of 70 engines

To check a download: `Get-FileHash .\AVD-Dashboard.exe -Algorithm SHA256`