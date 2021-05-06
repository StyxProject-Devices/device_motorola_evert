<p> Copyright 2018 - 2021 LineageOS Project </p>
<p> Copyright 2020 - 2021 StyxOS Project </p>

# Device configuration for Motorola G6 Plus (evert)

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core 2.2 GHz Cortex-A53
CHIPSET | Qualcomm SDM630 Snapdragon 630
GPU     | Adreno 508
Memory  | 4GB or 6GB
Shipped Android Version | 8.0 (Oreo)
Storage | 64GB or 128GB
Battery | 3200 mAh
Dimensions | 160 x 75.5 x 8 mm
Display | 1080 x 2160 pixels, 5.9" IPS LCD
Rear Camera  | 12 MP (f/1.7) + 5 MP (f/2.2), (PDAF, dual pixel)
Front Camera | 8 MP (f/2.2)

## Get Started 🚀

This is the GitHub repository for <b>Motorola Moto G6 Plus</b> with Snapdragon 630. Contains the necessary configurations to build the Android system

## Requeriments 📋
To get started with Android, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html)

## Building 🔧

First, enter your work environment. This is an example to build <b> StyxOS </b>
```
:~$ cd roms/StyxOS
:~/roms/StyxOS$
```

Then clone this repository into <b> device/motorola/evert </b>

```
:~/roms/StyxOS$ git clone -b R https://github.com/StyxProject-Devices/device_motorola_evert.git device/motorola/evert
Cloning into 'device/motorola/evert'...
remote: Enumerating objects: 18661, done.
remote: Total 18661 (delta 0), reused 0 (delta 0), pack-reused 18661
Receiving objects: 100% (18661/18661), 5.73 MiB | 40.06 MiB/s, done.
Resolving deltas: 100% (11586/11586), done.
:~/roms/StyxOS$
```
## Features 🌐

Among the features that you can add to your environment, there are applications and features that will give the device an appearance in the style of the original ROM. Among the features that can be found here, it is your option to include it in your development environment. Clone them and build!

### Motorola Camera 2 📸

- Launch the camera with just a twist of your wrist and turn again to switch cameras.
- Moto's smart cameras automatically adjust to lighting and motion conditions to deliver crystal-clear results.
- Full integration in Google Photos. Select the thumbnail to share, edit, and backup.
- The portrait mode of the dual cameras allows you to apply a blur to the background.
- Crop mode for selected dual cameras to crop the lens in the foreground and add your own background image.
- 360 ° panoramic photo and group selfie modes allow you to capture more parts of your photo than before.
- The automatic scanning of the QR code puts the information at your fingertips: just place the camera on the QR code and select whether you want to search or copy.
- Launch directly into Google Lens to find what you see, take action faster, and interact with the world.
- AR Stickers

<b> Source Code: </b> 
``` 
git clone https://gitlab.com/NemesisDevelopers/moto-camera/motorola_camera2_primary.git -b eleven-arm64 packages/apps/MotCamera2
git clone https://gitlab.com/NemesisDevelopers/moto-camera/motorola_camera2_overlay.git -b ten packages/apps/MotCamera2-overlay
```

### Moto Signature App 🔧

The Moto Signature App is an attractive platform where you can find all the features that make Motorola phones easy and enjoyable to use.Every time you open a Moto app, you will see information about the functions it provides. If MotoSignatureApp is not included in the source, the features will not work on the system you build.

<b> Source Code: </b> 
``` 
git clone https://gitlab.com/NemesisDevelopers/motorola/motorola_motosignatureapp.git -b eleven packages/apps/MotoSignatureApp
```

### After you have cloned the other repositories, you are ready to your development! 🛠️

## Copyright 📄
```
/*
 * Copyright (C) 2018 - 2021 The LineageOS Project
 * Copyright (C) 2020 - 2021 The StyxOS Project
 *
 * This program is free software: you can redistribute it and/or modify
 * it under the terms of the GNU General Public License as published by
 * the Free Software Foundation, either version 3 of the License, or
 * (at your option) any later version.
 *
 * This program is distributed in the hope that it will be useful,
 * but WITHOUT ANY WARRANTY; without even the implied warranty of
 * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 * GNU General Public License for more details.
 *
 * You should have received a copy of the GNU General Public License
 * along with this program.  If not, see <http://www.gnu.org/licenses/>.
 *
 */
```

