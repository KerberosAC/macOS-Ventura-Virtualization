# Screenshot Guide — macOS Ventura Virtualization

Every screenshot in this repository is extracted directly from the original `macOS Group 1(1).docx` report; no stock screenshots are used.

| # | Original embedded file | GitHub filename | README placement | What it shows |
| ---: | --- | --- | --- | --- |
| 1 | `image1.png` | `screenshots/01-virtualbox-create-ventura-vm.png` | 1. Create the macOS VM | VirtualBox Create Virtual Machine wizard; guest named Macos Ventura; Mac OS X (64-bit) selected. |
| 2 | `image2.png` | `screenshots/02-ventura-installer-image-source.png` | 2. Obtain installer media | External image-download page showing 14.65 GB Ventura installer media. |
| 3 | `image3.png` | `screenshots/03-ventura-installer-file-selected.png` | 2. Select image | Windows file chooser with the downloaded installer image selected. |
| 4 | `image4.png` | `screenshots/04-virtualbox-iso-storage-attachment.png` | 3. Attach storage | VirtualBox storage view: virtual hard disk plus installer image attached to the optical drive. |
| 5 | `image5.png` | `screenshots/05-virtualbox-usb-xhci-configuration.png` | 4. USB controller | USB settings showing xHCI / USB 3.0 controller selection. |
| 6 | `image6.png` | `screenshots/06-vboxmanage-cpu-efi-smc-settings.png` | 5. VBoxManage commands | Windows Command Prompt executing VBoxManage CPU-ID, EFI DMI, and SMC-related settings. |
| 7 | `image7.png` | `screenshots/07-macos-language-selection.png` | 6. Boot / language | Language selection after VM boots into the macOS setup/recovery environment. |
| 8 | `image8.png` | `screenshots/08-macos-recovery-utilities.png` | 6. Recovery | macOS Recovery utilities window including Disk Utility. |
| 9 | `image9.png` | `screenshots/09-disk-utility-apfs-guid-format.png` | 7. Disk Utility | Disk Utility virtual disk erase dialog selecting APFS and GUID Partition Map. |
| 10 | `image10.png` | `screenshots/10-ventura-software-license.png` | 8. License | macOS 13 beta software license agreement in the installer. |
| 11 | `image11.png` | `screenshots/11-ventura-installation-destination.png` | 9. Disk selection | Install destination screen selecting MacOS Ventura virtual disk (~40.76 GB total). |
| 12 | `image12.png` | `screenshots/12-ventura-installation-progress.png` | 10. Installation progress | Apple logo/macOS installation progress bar (~29 minutes remaining shown). |
| 13 | `image13.png` | `screenshots/13-ventura-ethernet-network-setup.png` | 11. Network setup | First-run connection selection with Local network (Ethernet) chosen. |
| 14 | `image14.jpeg` | `screenshots/14-macos-ventura-desktop.jpeg` | 12. Desktop / outcome | MacOS desktop with Dock, Finder menu bar, and Ventura wallpaper. |

## Evidence cautions

- Figure 5 shows the USB 3.0 controller **selected**, not that an external device was successfully passed through.
- Figure 6 shows commands entered, not a complete compatibility or licensing validation.
- Figure 13 shows Ethernet **selected**, not a successful network test.
- Figure 14 shows a graphical desktop, but does not establish stable repeated boots or performance benchmarks.
- The report lists three authors but does not attribute each action to a specific contributor.

## Review before publishing

Inspect screenshots for local Windows usernames, paths, or other details you prefer not to publish. Do not post credentials, activation keys, or licensed installer media.
