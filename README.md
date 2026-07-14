# Elite HyperOS

A comprehensive systemless enhancement module for **HyperOS** that brings together multiple premium features into a single package. Fully compatible with **Magisk**, **KernelSU**, and **KernelSU Next**, this module enables a Xiaomi EU-style **About Device** interface, applies the **HyperOS 3** themed About Device layout by default, enables **Google Mobile Services (GMS)** on supported Chinese ROMs, and includes several additional HyperOS optimizations to improve the overall user experience.

Unlike a standard flash-and-use module, **Elite HyperOS** requires a one-time configuration before installation to correctly display your device specifications in the About Device section.

---

## Features

- ✨ Xiaomi EU-style **About Device** specifications
- 🎨 HyperOS 3 themed About Device interface
- 🌐 Enables **Google Mobile Services (GMS)** on supported Chinese ROMs
- ⚡ Additional HyperOS system tweaks and optimizations
- 📱 Supports Xiaomi, Redmi, and POCO devices
- 🔒 Fully compatible with **Magisk**, **KernelSU**, and **KernelSU Next**
- ♻️ Systemless installation
- 🚀 Lightweight, stable, and optimized for daily use

---

## Requirements

- HyperOS
- Root access
- **Magisk**, **KernelSU**, or **KernelSU Next**

---

## Important

> **⚠️ Do NOT flash this module directly.**

Before installation, you **must** edit the included configuration file with your own device specifications. Otherwise, the Xiaomi EU-style About Device section will not display the correct information.

---

## Installation Guide

### Step 1

Download the latest release and extract **Elite_HyperOS.zip** using a file manager such as:

- MiXplorer
- MT Manager

### Step 2

Navigate to:

```text
/system/product/etc/
```

Locate the following file:

```text
device_info.json
```

### Step 3

Open `device_info.json`.

You will find something similar to:

```json
{
  "basic": {
    "CPU": "",
    "Battery": "",
    "Camera": "",
    "Screen": "",
    "Resolution": ""
  },
  "camera": {
    "front_camera": "",
    "rear_camera": ""
  }
}
```

### Step 4

Fill each empty field with your own device specifications.

Example:

```json
{
  "basic": {
    "CPU": "Dimensity 9400",
    "Battery": "6000mAh",
    "Camera": "50MP + 8MP",
    "Screen": "6.67-inch AMOLED",
    "Resolution": "2712 × 1220"
  },
  "camera": {
    "front_camera": "20MP",
    "rear_camera": "50MP + 8MP"
  }
}
```

### Step 5

Save the edited file.

### Step 6

Repack all extracted files into a ZIP archive while preserving the original folder structure.

### Step 7

Flash the newly created ZIP using:

- Magisk
- KernelSU
- KernelSU Next

### Step 8

Reboot your device.

Your customized Xiaomi EU-style About Device page, HyperOS 3 theme, CN GMS support, and additional HyperOS enhancements will now be applied.

---

## Compatibility

- Xiaomi devices
- Redmi devices
- POCO devices
- Supported HyperOS versions

> Compatibility may vary depending on the device model and HyperOS version.

---

## Credits

The original MI-EU Specs UI module was created by **Harsh10R - https://t.me/AboutHarshZXR **.

This project is an enhanced adaptation that integrates the original functionality with additional HyperOS improvements, HyperOS 3 styling, CN GMS support, and other optimizations.

Special thanks to **Harsh10R** for the original project.

---

## Disclaimer

This module is provided **as-is** without any warranty. Flashing root modules and modifying system components always carries some level of risk. You are solely responsible for any bootloops, data loss, or device issues resulting from the installation or use of this module. Always create a full backup before making system modifications.

---

## License

Please respect the original author's work and any applicable licenses associated with the original project.
