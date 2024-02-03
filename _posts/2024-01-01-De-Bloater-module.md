---

layout: blog
title: De-Bloater Magisk and KSU Module Streamline Your Android Experience
date: 2024-01-01
lang: eng
tagline: Enhance your Android device by removing bloatware with the De-Bloater Magisk and KSU Module.

---

## De-Bloater: A Systemless App De-bloating Solution

## Introduction

**De-Bloater** is an application that leverages the power of **Magisk** to remove unwanted system apps in a **systemless** manner. If you're tired of pre-installed bloatware cluttering your device, this module provides an efficient way to reclaim space and streamline your Android experience.

## Features

- **Easily Remove System Apps**: De-Bloater allows you to remove system apps from the following directories:
    - `/system`
    - `/vendor`
    - `/product`

## Requirements

Before using De-Bloater, ensure you meet the following requirements:

1. **Root Access**: Your device must be rooted.
2. **Magisk Environment**: De-Bloater requires a fully functional Magisk environment, including modules. It won't work with other rooting solutions or in Magisk core-only mode.

## How to Use

1. **Download the Module**: Grab the De-Bloater module from the [official GitHub repository](https://github.com/sunilpaulmathew/De-Bloater/releases/download/v0.26/app-release.apk).
2. **Install via Magisk**: Install the module through the Magisk app (not TWRP).
3. **Open the App**: Launch De-Bloater.
4. **Remove Unwanted Apps**: Click the "Remove" button next to each app you want to get rid of. These apps will be removed systemless-ly after a reboot.
5. **Restore Apps**: To restore an app, either use the "Reset Module" option in the top menu or selectively restore from the second page.

Remember that changes take effect after a restart.

## Troubleshooting

- **Bootloop Recovery**: If you accidentally remove essential apps and your phone enters a bootloop, delete `/data/adb/modules/De-bloater` via recovery.

## Acknowledgments

De-Bloater wouldn't be possible without the contributions of various individuals:

- **Grarak**: Code contributions (some borrowed from Kernel Adiutor)
- **John Wu**: libsu & Magisk
- **MONSTER_PC**: Russian & Ukrainian Translations
- **Emre**: Turkish Translations
- **Firerust96**: Spanish Translations
- **lay4play**: Italian Translations
- **Axel Schaab**: German Translations
- **alex**, **Ktosspl**, & **Valdnet**: Polish Translations
- **Reno** & **Ebolateam**: French Translations
- **Hoa Gia Đại Thiếu** & **ひきたり**: Vietnamese Translations
- **Hongle** & **qiaoxin**: Chinese (Hong Kong) Translations
- **MMETMA**: Arabic Translations
- Many others contributed via POEditor
