# xiaomi-bootloader-unlocking

# 🚀 Xiaomi Bootloader Unlock & TWRP Flash Guide

Comprehensive and beginner-friendly instructions for unlocking the bootloader and flashing TWRP custom recovery on **Xiaomi devices**, including Redmi, Poco, and Mi models.

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

- Xiaomi phone with internet access `Turn off your wifi`
- A computer (Windows/Linux/macOS)
- USB Cable `Original`
- [Xiaomi Mi Unlock Tool](https://xdaforums.com/attachments/miflash_unlock_en_7-6-727-43-zip.6097046/)
- [platform-tools](https://gofile.io/d/eGVJcQ)
- [ADB 15 Seconds](https://androidmtk.com/download-15-seconds-adb-installer) `Download the latest version`
- [FastBoot Drivers](https://gofile.io/d/55czhL) 
- Xiaomi account (for unlock authorization)

---

## 🔓 Bootloader Unlock Guide
**Go In your Android mobile 
1. **Enable Developer Options**
   - Go to `Settings > About phone`
   - Tap `MIUI version` 7 times

2. **Enable OEM Unlock and USB Debugging**
   - Go to `Settings > Additional settings > Developer options`
   - Enable `OEM unlocking` and `USB debugging`

3. **Bind Your Mi Account**
   - Go to `Settings > Mi Unlock status`
   - Tap `Add account and device`

4. **Confirm Your account**
- Go to `Developer Option`
- Tap on `Mi Unlock Status` Then in bottom click on verify after you get a sucessfull message then try to unlock bootloader if you get any error just type your error on chrome or youtube to slove that 
5. **Adb Setup**
   ```bash
   Then go in adb folder which is in Your C drive `C:\adb`
