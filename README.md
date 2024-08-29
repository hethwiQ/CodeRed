# CodeRed PE <img src="https://github.com/hethwiQ/CodeRed/blob/main/images/codeRedIco.png?raw=true" width="50" height="52"/>



**CodeRed PE (Preinstallation Environment)** is a refined and modernized edition of Windows 11 PE x64, crafted to empower tech enthusiasts and professionals alike. This sleek environment is your go-to solution for tackling a wide array of computer challenges with ease. Designed for today's cutting-edge systems, CodeRed PE fully supports UEFI booting and requires a minimum of 4 GB RAM, ensuring smooth and efficient operation on modern hardware.

## Curated Tools for Every Need
Within CodeRed PE, you'll find a meticulously selected suite of the finest free tools available. Each tool is chosen for its effectiveness, reflecting our commitment to providing only free and legally distributed software. Whether you're troubleshooting, recovering data, or performing system diagnostics, CodeRed PE equips you with the essential tools to get the job done right.

## Seamless Hardware Compatibility
Upon booting, CodeRed PE takes the hassle out of setup by automatically installing drivers for critical components like graphics, sound, and network cards. This ensures that you can connect to a WIFI or Ethernet network without missing a beat.

<img src="https://github.com/hethwiQ/CodeRed/blob/main/images/Capture.webp?raw=true" width="800" height="450"/>

## Installation Guide

### Step 1: Prepare Rufus
1. Insert your USB flash drive into your computer.
2. Download the latest version of [Rufus v4.5 x64 (or x86)](https://rufus.ie/en/) and launch the application.

### Step 2: Enable Dual UEFI/BIOS Mode
1. In Rufus, press `ALT+E` to unlock the "Dual UEFI/BIOS" mode.

   **Important**: 
   - Ensure that "Dual UEFI/BIOS mode enabled" is displayed at the bottom of Rufus, confirming the activation.
   - This mode remains enabled for future use, so you only need to activate it once.

   **Tip**: Activate "Dual UEFI/BIOS" mode before selecting the ISO file to ensure compatibility with FAT32 formatting.

### Step 3: Select the CodeRed ISO
1. With "Dual UEFI/BIOS" mode active, choose your USB flash drive from the "Device" dropdown menu.
2. Click `SELECT` and navigate to your `CodeRed.iso` file.

### Step 4: Configure Partition Scheme and File System
1. Set the "Partition scheme" to `MBR`.
2. Choose `FAT32` as the "File system".

   **Note**: 
   - For USB flash drives 32 GB or larger, opt for `Large FAT32` under the "File system" dropdown.
   - If "Large FAT32" is not visible, press `ALT+L` to enable "Force Large32 formatting."

### Step 5: Finalize and Start
1. Double-check all settings against the recommended configuration shown in the screenshot below.
2. Click `START` to begin the process. 
3. If prompted with a warning, review the information and click `OK` to proceed.

<img src="https://github.com/hethwiQ/CodeRed/blob/main/images/capturerufus.webp?raw=true" width="320" height="410"/>

   **Timing**: The creation process may take around 10 minutes, depending on your USB flash drive's write speed.

