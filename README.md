# Gigabyte A320M-S2H (rev. 1.x) + R3 2200G + RX 5500 XT

<img src= "https://user-images.githubusercontent.com/81640351/205501831-c179c9d2-865f-4b35-9da1-6b2d28d5e879.png" whith = "480px"/>

**Latest working macOS**: 11.7.1
<br>
**Current OpenCore**: 0.8.6

## Complete hardware specs
- Ryzen 3 2200G @ Stock
- Gigabyte A320M-S2H (rev. 1.x) @ BIOS F30
- RX 5500 XT - 51 RISC
- 1x 4Gb DDR4 2400Mhz Hyperx, 1x 8Gb DRR4 2666Mhz Juhor
- Wifi USB Wireless N 300Mbps, TP-Link, TL-WN821N

## What works
- macOS Big Sur and macOS Monterey
- HDMI/DP
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- Audio, has minimal noise on spotify

## Working
- Map USB ports
- Audio
- macOS Ventura Stability

## Kexts used:
- AMDRyzenCPUPowerManagement.kext
- AppleALC.kext
- AppleMCEReporterDisabler.kext
- Lilu.kext
- RtWlanU.kext
- RtWlanU1827.kext
- SMCAMDProcessor.kext
- VirtualSMC.kext
- WhateverGreen.kext

## Geekbench Results:
- Coming soon

## Notices
- To use WIFI-USB, you need to check the compatibility and installation of the .dmg file, see the Wireless-USB-OC credits

## Thanks/Credits
- [BASE EFI - for Ryzen Gen and Threadripper](https://github.com/luchina-gabriel/BASE-EFI-AMD-RYZEN-THREADRIPPER)

- [Wireless-USB-OC](https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter)