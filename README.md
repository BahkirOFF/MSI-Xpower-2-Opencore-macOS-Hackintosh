# Opencore 0.5.5 EFI for MSI Xpower II (Xpower 2)

![Image](https://sun9-60.userapi.com/c857420/v857420692/1919ba/xsmozCcWno8.jpg)

My Open Core 0.5.5 EFI for macOS High Sierra 10.13.6 and Catalina 10.15.3
Not ideal, but it works

## My config

**CPU:** Intel i7 3930K

**MB:** MSI Xpower II

**RAM:** 32GB 1600MHz (8x4)

**GPU:** Nvidia GTX 1080ti

**SSD:** Corsair 250Gb

## ACPI
SSDT-HPET.aml

## Patches
change EUSB to EH01, change USBE to EH02

## Kext
Lilu, VirtualSMC, AppleALC, WhateverGreen, USBInjectAll, SMCProcessor, SMCSuperIO, IntelMausiEthernet, VoodooTSCSync, FakePCIID, GenericUSBXHCI

## Kernel patches
USB 10.13.6+ by PMHeart, AppleUSBXHCIPCI

## Boot args
-v debug=0x100 keepsyms=1 npci=0x2000 alcid=1
