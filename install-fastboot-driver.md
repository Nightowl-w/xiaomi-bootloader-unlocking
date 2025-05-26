📦 [How to install Fastboot drivers in Windows](install-fastboot-driver.md)

## 🧰 Install Fastboot Drivers via Device Manager (Windows)

> 📌 **Use this if your phone is not detected in Fastboot (`fastboot devices` shows nothing)**

### ✅ Requirements:
- Windows PC
- USB cable
- Android phone in **Fastboot mode** (power off → hold Volume Down + Power)
- [Download latest Google USB Drivers](https://gofile.io/d/55czhL)

---

### 🪛 Step-by-Step Process:

1. **Connect your phone in Fastboot mode**
   - Power off the phone.
   - Hold **Volume Down + Power** until the Fastboot logo appears.
   - Connect it to your PC via USB.

2. **Open Device Manager**
   - Press `Windows + X` → select **Device Manager**
   - If you **don’t see your device**, click **"View" > "Show hidden devices"** in the top menu.

3. **Find the Unknown or Android device**
   - You might see it under:
     - **Other devices** → `Android`, `Android Bootloader Interface`, or `Unknown Device`
     - Or under **Universal Serial Bus devices**

4. **Right-click the device** → Select **“Update driver”**

5. Choose **“Browse my computer for drivers”**

6. Then choose **“Let me pick from a list of available drivers”**

7. Click **“Have Disk…”** → Browse to where you extracted the **Google USB Driver**
   - Usually it’s: `usb_driver\android_winusb.inf`

8. Select:
   - **Android Bootloader Interface** or **Android ADB Interface**
   - Click **Next**

9. Windows will show a warning — click **Yes / Install Anyway**

10. Once installed, you should see:
    - **Android Bootloader Interface** under **Android Devices**

---

### 🧪 Test the Fastboot Connection

Open Command Prompt and type:

```bash
fastboot devices
```

✅ If it shows a device ID, you're ready to flash.

❌ If still not detected:
- Try another USB port
- Try USB 2.0 instead of 3.0
- Use an original or good quality USB cable
- Restart PC and phone, and try again
