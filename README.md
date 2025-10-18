# Android Debloater

This repository contains a **batch script** to remove pre-installed apps (bloatware) from **Android devices** using **ADB** (Android Debug Bridge).  
It is designed to safely remove extra apps while keeping **critical system apps intact** (Phone, Contacts, Messages, Settings, Launcher, and Keyboard).  

> ⚠️ **Warning:** This script only works on **unrooted devices**. Some system apps are protected and cannot be removed. Use at your own risk.  

---

## Features

- Uninstalls Google apps like YouTube, Chrome, Gmail, Google Drive, Google Play Games, and more.  
- Removes extra system apps like Calculator, Sound Recorder, Gallery, etc.  
- Keeps essential apps to ensure your device remains functional.  
- Works for **user 0 only** (does not modify the system partition).  

---

## Requirements

- Windows PC (for the `.bat` script)  
- [ADB installed](https://developer.android.com/studio/command-line/adb)  
- USB Debugging enabled on your Android device  

---

## Usage

1. Connect your Android device to your PC via USB.  
2. Open a command prompt in the folder containing the batch script.  
3. Run the script:  

```bat
debloater.bat
