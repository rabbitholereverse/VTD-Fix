# VT-d Disabler

This package is provided as-is and is based on collective community contributions. It has been repackaged and documented for easier use and understanding.

## Setup Instructions

1. Reboot into BIOS and:
   - Disable **VT-d**
   - Disable **Secure Boot**
2. Format a USB drive to **FAT32**
3. Extract **all files** from this archive into the **root directory** of the USB drive
4. Shut down the computer
5. Insert the USB drive and **boot from it** (e.g., press **F11** for Boot Menu on MSI, then select your USB drive)
6. When prompted with the bootloader screen, do **nothing** — it will automatically boot into your original OS
7. Once in the OS, you may safely remove the USB drive

> To apply the VT-d fix on each boot, simply insert the USB drive and repeat step 5.

## Credits

Special thanks to those in the community who provided essential insights, including DMAR table references and EFI configuration strategies.

---

## Disclaimer

This tool is intended for educational and testing purposes only. Use at your own risk.
