# MSIxpower2macOS
Opencore hackintosh macos for MSI Xpower II (Xpower 2)

Open Core 0.5.5
macOS High Sierra 10.13.6

ACPI:
SSDT-HPET.aml

Patches:
change EUSB to EH01
change USBE to EH02

Kext:
Lilu
VirtualSMC
AppleALC
WhateverGreen
USBInjectAll
SMCProcessor
SMCSuperIO
IntelMausiEthernet
VoodooTSCSync
FakePCIID
GenericUSBXHCI

Kernel patches:
USB 10.13.6+ by PMHeart
AppleUSBXHCIPCI

Boot args:
-v debug=0x100 keepsyms=1 npci=0x2000 alcid=1
