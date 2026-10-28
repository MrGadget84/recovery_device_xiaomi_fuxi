# OrangeFox Recovery for Xiaomi 13

| Device Tree | Link | Branch
| ------------ | -------------------- | ------------ |
| fuxi | https://github.com/MrGadget84/recovery_device_xiaomi_fuxi | ofox_12.1

Xiaomi 13 (codenamed _"fuxi"_) is a high-end smartphone from Xiaomi.

It was announced & released on December 2022.

## Device Info

![Xiaomi 13](https://cdn.cnbj0.fds.api.mi-img.com/b2c-shopapi-pms/pms_1670745532.86084186.png)

Basic   | Spec Sheet
-------:|:-------------------------
SoC     | Snapdragon® 8 Gen 2 (SM8550)
CPU     | 1x3.2 GHz Cortex-X3 & 2x2.8 GHz Cortex-A715 & 2x2.8 GHz Cortex-A710 & 3x2.0 GHz Cortex-A510
GPU     | Adreno 740
Memory  | 8/12 GB RAM
Storage | 128/256/512 GB
Display | 1080 x 2400 pixels, 20:9 ratio (~414 ppi density), 6.36 inches, OLED, 120Hz, Dolby Vision, HDR10+, 1200 nits (HBM), 1900 nits (peak)
Camera  | 50 MP Leica lens (wide), 10 MP (telephoto), 12 MP (ultrawide), 32 MP (front-wide)
Battery | Li-Ion 4500 mAh, non-removable, graphene-enhanced
Shipped Android Version | 13 with MIUI 14, Upgrade to 16 with HyperOS 3

## Features

Works:

- [X] ADB
- [X] Decryption
- [X] Display
- [X] Fasbootd
- [X] Flashing
- [X] MTP
- [X] Sideload
- [X] USB OTG
- [X] Vibrator

## To use it:

```
fastboot flash recovery_ab recovery.img
```

or

```
adb sideload recovery.zip
```