# Samsung F41 Kernel Builder (Android 16 QPR2)

[![Build Kernel](https://github.com/yourusername/f41-kernel-build/actions/workflows/build.yml/badge.svg)](https://github.com/yourusername/f41-kernel-build/actions/workflows/build.yml)

Automated kernel builds for Samsung Galaxy F41 running Android 16 QPR2 (BP4A.251205.006).

## Sources
- **Kernel Source:** https://github.com/neeleshhh03/android_kernel_samsung_universal9611
- **Device Tree:** https://github.com/Parbindar7/android_device_samsung_f41
- **Android Version:** BP4A.251205.006 (android-16.0.0_r4)

## Features
- 🚀 Automated GitHub Actions builds
- 📦 Flashable AnyKernel3 ZIP
- 🔧 Proton Clang toolchain
- 📱 Samsung Exynos 9611 support
- 🔄 Weekly scheduled builds

## Download
Go to [Actions](https://github.com/yourusername/f41-kernel-build/actions) → Select latest workflow run → Download artifacts

## Installation
1. Download the latest kernel ZIP
2. Boot to custom recovery (TWRP/OrangeFox)
3. Flash the kernel ZIP
4. Wipe Dalvik/Cache
5. Reboot

## Manual Build
```bash
# Trigger manual build via GitHub Actions
# Or download and flash pre-built kernel
