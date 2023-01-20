# Gigabyte A320M-S2H (rev. 1.x) + R3 2200G + RX 5500 XT

<img src= "https://user-images.githubusercontent.com/81640351/213814234-b3c4fd41-c80a-4ca4-98a6-8aed7aa6da3d.png" whith = "480px"/>

**Latest working macOS**: 13.1
<br>
**Current OpenCore**: 0.8.8

## Complete hardware specs
- Ryzen 3 2200G @ Stock
- Gigabyte A320M-S2H (rev. 1.x) @ BIOS F30
- RX 5500 XT - 51 RISC
- 1x 4Gb DDR4 2400Mhz Hyperx, 1x 8Gb DRR4 2666Mhz Juhor
- Wifi USB Wireless N 300Mbps, TP-Link, TL-WN821N
- Vention USB Audio Card

## What works
- macOS Big Sur, macOS Monterey and macOS Ventura
- HDMI/DP
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- N/A

## Working
- N/A

## Kexts used:
- AMDRyzenCPUPowerManagement.kext
- AppleALC.kext
- AppleMCEReporterDisabler.kext
- FeatureUnlock.kext
- Lilu.kext
- RadeonSensor.kext
- RealtekRTL8111.kext
- RtWlanU.kext
- RtWlanU1827.kext
- SMCAMDProcessor.kext
- SMCRadeonGPU.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext

## Geekbench Results:
- <a href="https://browser.geekbench.com/v5/cpu/20000551">iMacPro1,1</a>

## Notices
- To use WIFI-USB, you need to check the compatibility and installation of the .dmg file, see the Wireless-USB-OC credits

## Thanks/Credits
- [BASE EFI - for Ryzen Gen and Threadripper](https://github.com/luchina-gabriel/BASE-EFI-AMD-RYZEN-THREADRIPPER)

- [Wireless-USB-OC](https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter)
