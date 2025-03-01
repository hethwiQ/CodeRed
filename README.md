# CodeRed RE <img src="https://github.com/hethwiQ/CodeRed/blob/main/images/codeRedIco.png?raw=true" width="50" height="52"/>

**CodeRed RE (Repair-Preinstallation Environment)** is a refined and modernized edition of Windows 11 PE x64, crafted to empower tech enthusiasts and professionals alike. **CodeRed enables secure access to locked Windows systems**. This professional-grade environment is designed to assist in a wide range of system recovery tasks with efficiency and precision. Built for modern systems, CodeRed fully supports UEFI booting and requires a minimum of 4 GB RAM, ensuring smooth operation on contemporary hardware.

## Curated Tools for Every Need
Within CodeRed, a meticulously selected suite of free and legally distributed tools is available. Each tool is chosen for its effectiveness, ensuring users have access to high-quality utilities for troubleshooting, data recovery, and system diagnostics.

### BCD-MBR Tools
- BootIce v1.3.3
- EasyBCD v2.3

### Hard Disk Tools - Data Recovery
- CheckDisk GUI v0.3.1
- Lazesoft Data Recovery v4.7
- Puran Data Recovery v1.2.1
- Puran File Recovery v1.2.1
- Recuva v1.53.2096
- DMDE v4.0.6
- ReclaiMe build 4571
- PhotoRec v7.2
- Unstoppable Copier v5.2
- Victoria v5.37
- DiskInternals Linux Reader v4.19.2
- Paragon AppleFS for Windows v2.1.12

### Hard Disk Tools - Defrag
- Defraggler v2.22.33.995

### Hard Disk Tools - Diagnostic
- GSmartControl v1.1.4
- HDDScan v4.1
- HDTune v2.55
- WD Data Lifeguard Diagnostics v1.37
- Crystal Disk Info v9.2.2
- Test Disk v7.2

### Hard Disk Tools - Imaging
- Acronis Cyber Protect b40901
- AOMEI Backupper v7.3.3
- Lazesoft Disk Image & Clone v4.7
- Macrium Reflect PE v7.3.5925
- Runtime DriveImage XML v2.60
- Drive Snapshot v1.50

### Hard Disk Tools - Partition Tools
- AOMEI Partition Assistant v10.2.2
- Macrorit Partition Extender v2.3.1
- Macrorit Partition Expert v8.1.3
- DiskGenius v5.5.1.1508
- EaseUS Partition Master v14.5

### Hard Disk Tools - Security
- HDD Low Level Format Tool v4.40
- Eraser v6.2.0.2993
- VeraCrypt v1.26.7

### Windows Recovery
- Lazesoft Windows Recovery v4.7

### Other Tools
- FSViewer v7.8
- Free Office rev 703
- Sumatra PDF v3.5.2
- 7-Zip v23.01
- ExamDiff Pro v1.9.3
- HxD v2.5.0
- Notepad++ v8.6.2
- WinMerge v2.16.36
- VLC Media Player v3.0.20
- TreeSize v4.7.1.525
- IrfanView v4.62
- NVDA v2023.3.3 (Ctrl + Alt + N)

### Removable Drive Tools
- CDBurnerXP v4.5.8.7128
- Rufus v4.4
- ImageUSB v1.5.1006

### Security - AntiVirus
- ESET Online Scanner v3.5.6
- McAfee Stinger v13.0.0.19

### Security - KeyFinders
- ShowKeyPlus v1.0.7060

### Security - Passwords
- Lazesoft Password Recovery v4.7
- NT Password Edit v0.7
- Windows Login Unlocker v2.1

### System Tools
- CPU-Z v2.09
- GPU-Z v2.57
- HWInfo v7.68-5300
- Speccy v1.32.803
- WinNTSetup v5.3.3
- Attribute Changer v11.0
- Change Keyboard Layout v1.0.0
- Dependency Walker v2.2.6
- Registry Backup v4.0.0
- Regshot v2.0.1.70
- SysInternals Suite
- PowerShell Core v7.4.1
- Aqua Key Test
- ImDisk Virtual Disk Driver v2.0.9
- Total Commander v11.02

### Network
- Aero Admin v4.7
- Google Chrome v121.0.6167.185
- Mozilla Firefox Quantum ESR v115.3.1esr
- PENetwork v0.59.0.B12
- Anydesk 7.1.13
- WinSCP v6.1.2
- Putty v0.80

## Seamless Hardware Compatibility
Upon booting, CodeRed automatically installs drivers for critical components like graphics, sound, and network cards, ensuring full connectivity and usability without additional setup.

<img src="https://github.com/hethwiQ/CodeRed/blob/main/images/Capture.webp?raw=true" style="max-width:100%; height:auto;"/>

## Installation Guide

### Step 1: Prepare Rufus
1. Insert your USB flash drive into your computer.
2. Download the latest version of [Rufus v4.5 x64 (or x86)](https://rufus.ie/en/) and launch the application.

### Step 2: Enable Dual UEFI/BIOS Mode
1. In Rufus, press `ALT+E` to unlock the "Dual UEFI/BIOS" mode.

   **Important**:
   - Ensure that "Dual UEFI/BIOS mode enabled" is displayed at the bottom of Rufus, confirming the activation.
   - This mode remains enabled for future use, so you only need to activate it once.
   - Activate "Dual UEFI/BIOS" mode before selecting the ISO file to ensure compatibility with FAT32 formatting.

### Step 3: Select the CodeRed ISO
1. With "Dual UEFI/BIOS" mode active, choose your USB flash drive from the "Device" dropdown menu.
2. Click `SELECT` and navigate to your `CodeRed.iso` file.

### Step 4: Configure Partition Scheme and File System
1. Set the "Partition scheme" to `MBR`.
2. Choose `FAT32` as the "File system".

   **Note**:
   - For USB flash drives 32 GB or larger, select `Large FAT32` under the "File system" dropdown.
   - If "Large FAT32" is not visible, press `ALT+L` to enable "Force Large32 formatting."

### Step 5: Finalize and Start
1. Double-check all settings against the recommended configuration shown in the screenshot below.
2. Click `START` to begin the process.
3. If prompted with a warning, review the information and click `OK` to proceed.

<img src="https://github.com/hethwiQ/CodeRed/blob/main/images/capturerufus.webp?raw=true" width="320" height="410"/>

**Timing**: The creation process may take around 10 minutes, depending on your USB flash drive's write speed.
