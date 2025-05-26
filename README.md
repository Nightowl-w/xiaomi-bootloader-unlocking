# xiaomi-bootloader-unlocking

# 🚀 Xiaomi Bootloader Unlock & TWRP Flash Guide

Comprehensive and beginner-friendly instructions for unlocking the bootloader and flashing TWRP custom recovery on **Xiaomi devices**, including Redmi, Poco, and Mi models.

---

## 📋 Table of Contents

- [About](#about)
- [Disclaimer](#disclaimer)
- [Requirements](#requirements)
- [Bootloader Unlock Guide](#bootloader-unlock-guide)
- [TWRP Flashing Guide](#twrp-flashing-guide)
- [Device-Specific Guides](#device-specific-guides)
- [Troubleshooting](#troubleshooting)
- [License](#license)

---

## ℹ️ About

This repository contains:
- Step-by-step guides for unlocking Xiaomi bootloaders
- Official Xiaomi Unlock Tool usage
- Device-specific TWRP flash instructions
- TWRP image files
- Common troubleshooting tips

---

## ⚠️ Disclaimer

> Unlocking your bootloader **voids warranty** and may brick your device. Proceed only if you know the risks. This guide is for **educational purposes only**.

---

## 🧰 Requirements

- Xiaomi phone with internet access
- A computer (Windows/Linux/macOS)
- USB Cable
- [Xiaomi Mi Unlock Tool](mi-unlock-tool.md)
- [ADB & Fastboot (platform-tools)]( use my bat file to downlaod adb drivers )
- Specific TWRP image for your device
- Xiaomi account (for unlock authorization)

---

## 🔓 Bootloader Unlock Guide

1. **Enable Developer Options**
   - Go to `Settings > About phone`
   - Tap `MIUI version` 7 times

2. **Enable OEM Unlock and USB Debugging**
   - Go to `Settings > Additional settings > Developer options`
   - Enable `OEM unlocking` and `USB debugging`

3. **Bind Your Mi Account**
   - Go to `Settings > Mi Unlock status`
   - Tap `Add account and device`

4. **Boot to Fastboot**
   ```bash
   adb reboot bootloader
