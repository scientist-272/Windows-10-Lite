# Windows-10-Lite
A lightweight Windows 10 project optimized for low-end and older PCs.
# 🪟 Windows 10 Lite

### A lightweight Windows 10 project for older and low-end PCs.

---

# ⬇️ DOWNLOAD WINDOWS 10 LITE

## 🚀 Latest Version

### 👉 [⬇️ DOWNLOAD WINDOWS 10 LITE — LATEST RELEASE](../../releases/latest)

**Recommended:** Always download the latest release unless you specifically need an older version.

> ⚠️ The download is provided through the GitHub Releases system. Check the release notes and SHA-256 checksum before installation.

---

# ⚠️ BEFORE YOU INSTALL

Please read:

* [💻 System Requirements](docs/requirements.md)
* [📖 Installation Guide](docs/installation.md)
* [🔐 SHA-256 Verification](#-verify-your-download)

**Back up your important files before installing Windows.**

A clean installation can erase existing files and partitions.

---

# 💻 SYSTEM REQUIREMENTS

| Component    |      Minimum | Recommended |
| ------------ | -----------: | ----------: |
| CPU          | 1 GHz 64-bit |    2+ cores |
| RAM          |         2 GB |      4–8 GB |
| Storage      |        32 GB |      64 GB+ |
| USB          |         8 GB |       16 GB |
| Architecture |          x64 |         x64 |
| Firmware     |    BIOS/UEFI |        UEFI |

Actual performance depends on the hardware and the particular Lite build.

👉 **[View complete requirements](docs/requirements.md)**

---

# ⚡ FEATURES

Windows 10 Lite is intended to provide a lighter Windows environment for compatible older hardware.

### Current project goals

* ⚡ Reduced unnecessary components
* 💾 Lower storage requirements
* 🧠 Lower background resource usage
* 🚀 Improved responsiveness on compatible hardware
* 🧹 Cleaner installation
* 💻 Designed with older hardware in mind
* 🔐 SHA-256 release verification
* 📦 Versioned releases

Features can change between releases.

Always read the release notes for the version you download.

---

# 📥 HOW TO INSTALL

## Step 1 — Download

Click:

### 👉 [⬇️ DOWNLOAD WINDOWS 10 LITE](../../releases/latest)

Download the ISO from the latest release.

---

## Step 2 — Verify the ISO

After downloading, calculate its SHA-256 hash.

Open PowerShell:

```powershell
Get-FileHash "C:\Path\Windows10-Lite.iso" -Algorithm SHA256
```

Compare the result with the checksum published with the release.

The hashes should match exactly.

---

## Step 3 — Create a Bootable USB

You will need:

* Windows 10 Lite ISO
* USB flash drive
* At least 8 GB USB
* A working Windows computer
* Rufus or another suitable USB creation tool

⚠️ Creating installation media can erase the USB drive.

---

## Step 4 — Boot From USB

Insert the USB into the target computer.

Restart the PC and open its boot menu.

Common boot-menu keys include:

```text
F12
F11
F9
Esc
F8
```

The correct key depends on the computer manufacturer.

Select your USB device.

---

## Step 5 — Windows Setup

When Windows Setup starts:

1. Select language.
2. Select time/currency format.
3. Select keyboard.
4. Click **Install now**.
5. Follow the installation instructions.

---

## Step 6 — Select the Installation Drive

For a clean installation, select the appropriate target partition.

⚠️ **WARNING**

Formatting or deleting a partition can permanently delete data.

Make a backup before continuing.

---

# 📖 FULL INSTALLATION GUIDE

For the detailed guide with screenshots:

### 👉 [📖 Open Installation Guide](docs/installation.md)

---

# 📸 INSTALLATION PICTURES

## 1. Download

![Download](docs/images/01-download.png)

## 2. Rufus

![Rufus](docs/images/02-rufus.png)

## 3. Boot Menu

![Boot Menu](docs/images/03-boot-menu.png)

## 4. Windows Setup

![Windows Setup](docs/images/04-windows-setup.png)

## 5. Installed Desktop

![Desktop](docs/images/05-desktop.png)

---

# 🎬 VIDEO TUTORIAL

## Windows 10 Lite Installation

🎥 **Video tutorial**

> Video will be added here.

When the video is published, the link will be placed here.

---

# 🔐 VERIFY YOUR DOWNLOAD

Every release should provide a SHA-256 checksum.

Example:

```text
Windows10-Lite-v1.0.0-x64.iso

SHA256:
YOUR_SHA256_HASH_HERE
```

To calculate the hash in PowerShell:

```powershell
Get-FileHash ".\Windows10-Lite-v1.0.0-x64.iso" -Algorithm SHA256
```

Compare your result with the hash published by the release.

---

# 📦 RELEASES

### 👉 [View All Windows 10 Lite Releases](../../releases)

Each release contains:

* Version number
* Release date
* ISO download
* SHA-256 checksum
* Changes
* Known issues
* Installation information

---

# 🆕 LATEST RELEASE

## Windows 10 Lite v1.0.0

**Status:** Initial Release

### Changes

* Initial Windows 10 Lite release
* Installation documentation
* USB installation instructions
* SHA-256 verification

### Known Issues

No known issues currently documented.

---

# 🛠️ TROUBLESHOOTING

## USB does not appear

Try:

1. Reconnect the USB.
2. Try another USB port.
3. Enter BIOS/UEFI.
4. Check boot configuration.
5. Recreate the USB.
6. Try another USB drive.

---

## Windows Setup cannot detect the drive

Possible causes include:

* Storage controller configuration
* Missing storage driver
* BIOS/UEFI configuration
* Disk configuration

Check your computer manufacturer's documentation.

---

## Installation fails

Check:

* ISO SHA-256
* USB drive
* RAM
* Storage health
* BIOS/UEFI configuration

---

# 🧪 TESTING

Each release should be tested for:

* Booting
* Windows Setup
* Disk detection
* USB
* Keyboard
* Mouse
* Network
* Audio
* Display
* Restart
* Shutdown
* Sleep/wake
* Common applications

---

# 📜 DISCLAIMER

Windows is proprietary software owned by Microsoft.

This project does not claim ownership of Windows or Microsoft's intellectual property.

Only distribute installation media that you are legally permitted to distribute.

Users are responsible for having an appropriate Windows license.

Use the project at your own risk.

Always back up important data before installing an operating system.

---

# 👤 PROJECT

**Windows 10 Lite**

Maintained by **Scientist272**

⭐ Star the repository if you find the project useful.

🐛 Report bugs through GitHub Issues.

💡 Suggestions and improvements are welcome.
