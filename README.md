# Gigabyte Z490 UD Comet Lake Hackintosh

Opencore Bootloader EFI and config.plist file with all required Drivers and Kexts for Gigabyte Z490 UD. (Tested With i5-10600).

$$ NOTE: Current 'master' branch is only tested on macOS 11 Big Sur $$

## Included Software

| Library        | Version |
| -------------- | ------- |
| OpenCore       | 0.6.9   |
| -------        | ------- |
| AppleALC       | 1.6.0   |
| Lilu           | 1.5.3   |
| NVMeFix        | 1.0.7   |
| RealtekRTL8111 | 2.4.2   |
| VirtualSMC     | 1.2.3   |
| WhateverGreen  | 1.4.9   |

## BIOS SETTINGS

OS Mode: _Other OS with UEFI Only_ or, _Windows 8/10 (CSM Disabled)_

Secure Boot: _Disabled_

Aboce 4G Decode: _Enabled_

Resizable BAR: _Disabled_

SuperIO: _Disabled_

VD-x: _Enabled_

VT-d: You can leave it _disabled_ or _enable_ it if you need it for Other OS. (MacOS can't/doesn't use VT-d)

## What's Working

1. Boot Logo
2. Onboard Audio
3. iGPU UHD630 with HDMI-output
4. Hardware Decoding using iGPU
5. Xcode and Android Studio
6. Netflix
7. Sleep/Wake, Shutdown, Powercycle (Restart)
8. Tested with macOS 10.15.7 (Latest Build)

## What's NOT Working

2. Back panel audio input & output

## What's Not Tested

1. iServices

## My Hardware Config

- CPU: Intel Core i5-10600
- Motherboard: Gigabyte Z490 UD (Z490 Chipset)
- RAM: 2x8GB G.Skill Ripjaws X
- SSD: Samsung NVMe 970 Evo Plus 512 GB

## Licenses & Attribution

Most of the Included stuffs here are BSD-3-Clause Licensed and developed by `acidanthera` developers and other open source community developers. Config files and EFI partition prepared by following `dortania - Hackintosh Guides` and some trial & errors.

Github user `xingzai96` for figuring out the HDMI framebuffer config.

Enjoy.
