# 📖 Windows 10 Lite Installation Guide

## 1. Download the ISO

Go to:

**[Download Latest Windows 10 Lite Release](../releases/latest)**

Download the ISO from the latest release.

---

## 2. Verify the ISO

Open PowerShell:

```powershell
Get-FileHash "Windows10-Lite.iso" -Algorithm SHA256
```

Compare the result with the SHA-256 checksum published with the release.

---

## 3. Prepare USB

Use an appropriate USB-writing utility such as Rufus.

You need:

* ISO
* USB flash drive
* Working computer

⚠️ The USB may be erased during this process.

---

## 4. Configure USB

Select:

```text
Device: Your USB
Boot selection: Windows 10 Lite ISO
Partition scheme: GPT or MBR
Target system: UEFI or BIOS
```

The correct configuration depends on the target computer.

---

## 5. Boot From USB

Insert the USB.

Restart the computer.

Open the boot menu.

Select:

```text
UEFI: USB
```

or the corresponding USB device.

---

## 6. Start Windows Setup

Follow Windows Setup.

Select:

* Language
* Region
* Keyboard

Then continue.

---

## 7. Select Installation Type

For a clean installation:

```text
Custom: Install Windows only
```

---

## 8. Select the Target Disk

Select the correct partition.

⚠️ Do not delete or format a partition unless you have backed up its contents and are certain it is the correct disk.

---

## 9. Complete Installation

Windows will copy the files and restart several times.

Follow the setup instructions until you reach the desktop.

---

## 10. After Installation

Recommended:

1. Install hardware drivers.
2. Connect to the internet.
3. Check Device Manager.
4. Check activation.
5. Install required applications.
6. Create a restore/recovery strategy.
7. Test audio, network, USB and display.

---

## 🎬 Video

Video tutorial:

**Coming soon**

---

## 📸 Screenshots

Screenshots will be added as the guide is completed.
