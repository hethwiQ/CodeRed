# CodeRed RE <img src="https://github.com/hethwiQ/CodeRed/blob/main/images/codeRedIco.png?raw=true" width="50" height="52"/>

**CodeRed RE (Repair-Preinstallation Environment)** is a refined and modernized edition of Windows 11 PE x64, crafted to empower tech enthusiasts and professionals alike. **CodeRed enables secure access to locked Windows systems**. This professional-grade environment is designed to assist in a wide range of system recovery tasks with efficiency and precision. Built for modern systems, CodeRed fully supports UEFI booting and requires a minimum of 4 GB RAM, ensuring smooth operation on contemporary hardware.

## Curated Tools for Every Need
Within CodeRed, a meticulously selected suite of free and legally distributed tools is available. Each tool is chosen for its effectiveness, ensuring users have access to high-quality utilities for troubleshooting, data recovery, and system diagnostics.

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

## Screenshots

<img src="https://raw.githubusercontent.com/hethwiQ/CodeRed/refs/heads/main/images/codered%20sc/installing%20drivers.webp" style="max-width:100%; height:auto;"/>
<img src="https://raw.githubusercontent.com/hethwiQ/CodeRed/refs/heads/main/images/codered%20sc/programs.webp" style="max-width:100%; height:auto;"/>
<img src="https://raw.githubusercontent.com/hethwiQ/CodeRed/refs/heads/main/images/codered%20sc/chrome.webp" style="max-width:100%; height:auto;"/>
<img src="https://raw.githubusercontent.com/hethwiQ/CodeRed/refs/heads/main/images/codered%20sc/check%20disk%20gui.webp" style="max-width:100%; height:auto;"/>
<img src="https://raw.githubusercontent.com/hethwiQ/CodeRed/refs/heads/main/images/codered%20sc/macrum.webp" style="max-width:100%; height:auto;"/>
<img src="https://raw.githubusercontent.com/hethwiQ/CodeRed/refs/heads/main/images/codered%20sc/network%20manager.webp" style="max-width:100%; height:auto;"/>
<img src="https://raw.githubusercontent.com/hethwiQ/CodeRed/refs/heads/main/images/codered%20sc/aomei%20backup.webp" style="max-width:100%; height:auto;"/>
<img src="https://raw.githubusercontent.com/hethwiQ/CodeRed/refs/heads/main/images/codered%20sc/aomei%20disk%20assist.webp" style="max-width:100%; height:auto;"/>
<img src="https://raw.githubusercontent.com/hethwiQ/CodeRed/refs/heads/main/images/codered%20sc/scan.webp" style="max-width:100%; height:auto;"/>
<img src="https://raw.githubusercontent.com/hethwiQ/CodeRed/refs/heads/main/images/codered%20sc/password%20edit.webp" style="max-width:100%; height:auto;"/>

## Demo Video

[![Watch the demo](https://img.youtube.com/vi/kSvIeGjeG-c/hqdefault.jpg)](https://youtu.be/kSvIeGjeG-c)

