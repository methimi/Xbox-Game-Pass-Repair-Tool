<div align="center">

# 🎮 Xbox Game Pass Repair Tool

### An independent Windows tool that helps find and fix Xbox app and PC Game Pass issues

🪟 Windows 10 / 11 &nbsp; • &nbsp; 🧰 Scanning and repair &nbsp; • &nbsp; ↩️ Undo support

<a href="https://github.com/methimi/Xbox-Game-Pass-Repair-Tool/releases/latest/download/XboxGamePassRepairTool_Setup.exe"><img src="https://img.shields.io/badge/Download_Now-16a34a?style=for-the-badge&logo=github&logoColor=white" alt="Download Now"></a>

**Download the latest version, extract the ZIP file to a folder, and get started.**

</div>

## 🌐 Supported Languages

- 🇬🇧 **English**
- 🇹🇷 [Türkçe](README_TR.md)

> [!IMPORTANT]
> This project is not developed, published, supported, or endorsed by Microsoft. It has no official or commercial connection with Microsoft, Xbox, or Game Pass.

## 👋 What does this app do?

When the Xbox app will not open, games will not download, Gaming Services reports an error, or Game Pass games will not start, finding the cause can be difficult.

Xbox Game Pass Repair Tool checks the related Windows components one by one, explains the results in plain language, and asks for your approval before offering repairs that can be applied safely.

The app checks areas such as:

| | Area checked | Example issues |
|---|---|---|
| 🎮 | Xbox and Game Pass | Xbox app, Gaming Services, and game packages |
| 🛍️ | Microsoft Store | Downloads, licensing, app registration, and Store services |
| 🌐 | Internet and network | DNS, proxy, VPN impact, connectivity, and access to Microsoft servers |
| 🕒 | Time and region | Incorrect time, time zone, region, and certificate mismatches |
| 🧩 | Windows components | Windows Update, BITS, AppX, and required system services |
| 💾 | Disks and user profile | Free space, game drives, folder access, and profile issues |
| 🖥️ | Gaming platform | GPU driver, DirectX, Visual C++, .NET, and shader cache |
| 🛡️ | Security and anti-cheat | Secure Boot, Defender impact, and common anti-cheat services |

## ✨ Highlights

- 🔍 A detailed full scan covering Xbox and Windows components
- 🧠 Root-cause analysis that evaluates related findings together
- ✅ Clear separation between confirmed issues, information, and results that could not be verified
- 🛠️ User-approved automatic repair for suitable issues
- 🔁 Verification after repair
- ↩️ Undo support and repair history for supported actions
- 🧾 A detailed HTML report after every scan
- 🌐 A live Xbox service status page
- 🛑 The ability to cancel an active scan safely
- 🇹🇷 Turkish and 🇬🇧 English interface

## 🚀 How to use it

### 1. Download and extract

Download the latest ZIP package from the **[Releases](https://github.com/methimi/Xbox-Game-Pass-Repair-Tool/releases)** page on GitHub and extract the entire package to a folder.

> [!WARNING]
> Do not move only the EXE file. `XboxGamePassRepairTool.exe` and the `ApplicationFiles` folder must remain together.

### 2. Open the app

Double-click `XboxGamePassRepairTool.exe`. Windows may request administrator permission for some checks and repairs.

### 3. Enter an error code if you have one

The app asks for an error code before the scan begins. This field is optional, so you can leave it empty if you do not have a code. The code you enter does not change which checks or repairs are performed.

### 4. Start the full scan

Results appear one by one during the scan. Navigation to other pages is locked while the scan is running. You can cancel the process safely if needed.

### 5. Review the results

Detected issues are separated into repairs the app can perform and actions you need to complete yourself. You can see which actions will be applied before a repair begins.

### 6. Approve the repair

The app does not start a suggested repair without your permission. When the process finishes, available checks are run again to verify whether the problem was actually resolved.

## 🚦 What do the results mean?

| Display | Meaning |
|---|---|
| ✅ Successful | The checked area appears healthy. |
| ⚠️ Issue found | A reliable issue was detected. |
| ℹ️ Information | This is not a failure, but it may be useful to know. |
| ❓ Uncertain | The app could not verify this area conclusively. This does not mean it is broken. |

Repair results are also shown in four states:

| Result | Description |
|---|---|
| ✅ Successful | The action finished and was verified again when possible. |
| 🟠 Partial | Part of the action finished, or the result could not be fully verified. |
| ⏳ Pending | A restart, Store installation, or another user action is required. |
| ❌ Failed | The repair could not be applied, or the issue remains. |

## 🛠️ What can it repair?

Depending on the findings, the app may suggest some of the following actions:

- Repairing Windows time and time zone services
- Clearing the DNS cache
- Resetting proxy layers with the user's approval
- Reconfiguring Windows Update, BITS, and Xbox services
- Refreshing the Microsoft Store cache
- Repairing Xbox app and Gaming Services registrations
- Opening the official Microsoft Store page for missing apps
- Clearing the DirectX shader cache within safe limits
- Running Windows system file repair when required

Not every issue can be fixed automatically. Account, subscription, payment, age restriction, Microsoft service outage, and some organization policy issues may require action from the user or a system administrator.

## ↩️ Repair history and undo

The app keeps the latest repair session on the **Repair History** page.

- Fully supported settings can be restored to their previous state.
- Some package and cache actions can only be partially undone.
- Installations completed through the Store or changes made by Windows cannot always be reversed.
- The undo option is shown only when a usable record is available.

If a repair is undone, the feedback survey associated with that repair is removed.

## 🔄 Restarting Windows

Some Windows service and package changes are completed only after the computer restarts. The app reports required and recommended restarts separately, and it does not restart your computer without permission.

## 🔐 Privacy and data sharing

> [!CAUTION]
> This version automatically sends a Telegram notification to the developer when a scan starts and when it finishes.

Information that may be sent includes:

- A randomly generated support ID and scan ID
- The error code, if one was entered, or a notice that no code was provided
- Scan results and the detailed HTML report
- Windows version, hardware model, processor, memory, graphics card, and driver information
- General disk capacity and free-space information
- Network adapter details, security features, and Xbox package versions
- The user's “resolved” or “not resolved” feedback
- The user's own description if “not resolved” is selected

The app does not collect the contents of personal files, passwords, or browser history for reporting purposes. Hardware serial numbers, IP addresses, and MAC addresses are not added to the system inventory. However, the report contains detailed technical system information, so make sure you accept this sharing before using the app.

## 🛡️ Safety approach

- System settings are not changed during a scan.
- User approval is required before repair actions begin.
- A single symptom is not treated as a confirmed failure without enough evidence.
- Checks that cannot be read are marked as “uncertain” instead of successful.
- High-impact actions are identified separately.
- Protected Windows databases and critical game storage records are not deleted automatically.
- Some high-impact package repairs are restricted on Windows 10 for safety.

> [!TIP]
> Close open games and apps before starting a repair. Save important work and, if possible, create a Windows restore point.

## 💻 System requirements

- 🪟 Windows 11 or Windows 10 22H2
- 🌐 Internet connection
- 🧩 Microsoft Edge WebView2 Runtime
- 👤 Administrator permission for some actions

Other operating systems are not supported. On organization-managed computers, missing components or restrictions may be intentional. In those environments, contact your system administrator instead of applying automatic repairs.

## ❓ Frequently asked questions

<details>
<summary><strong>Is this an official Microsoft tool?</strong></summary>

No. This is an independent third-party project and is not supported or endorsed by Microsoft.

</details>

<details>
<summary><strong>Does scanning change anything on my computer?</strong></summary>

The full scan only checks the current state. Repairs that can make changes are shown in a separate window and do not start without user approval.

</details>

<details>
<summary><strong>Why does it request administrator permission?</strong></summary>

Administrator permission may be required to check Windows services, system logs, and app packages correctly, and to apply approved system repairs.

</details>

<details>
<summary><strong>Is an “uncertain” result an error?</strong></summary>

No. It means the check could not reach a definite conclusion. Organization policies, the Windows version, a disabled event log, or a temporary access issue may cause this.

</details>

<details>
<summary><strong>If a repair is shown as successful, is the problem definitely fixed?</strong></summary>

The app checks the same area again after a repair whenever possible. However, if a Store installation, restart, or account action is still required, the result may remain “pending” or “partial.”

</details>

<details>
<summary><strong>Can I copy only the EXE file?</strong></summary>

No. The `ApplicationFiles` folder contains required parts of the app. The EXE and this folder must be moved together.

</details>

## ⚠️ Disclaimer

This software is under development and is provided without any warranty. It includes repairs that can change Windows services, network settings, and app packages. Read the on-screen explanations, do not apply high-impact actions you do not understand, and back up important data.

Microsoft, Windows, Xbox, Xbox Game Pass, and Microsoft Store names and trademarks belong to their respective owners. These names are used only to describe the tool's compatibility and intended scope.

---

<div align="center">

🎮 **Find the issue • Consider the safe option • Verify the result**

</div>
