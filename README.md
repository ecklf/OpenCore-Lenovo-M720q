# OpenCore - Lenovo M720Q Tiny

<!-- <p align="center"> -->
<!--     <img height="auto" width="auto" src="images/screenshot.png" /> -->
<!-- </p> -->

## Configuration for macOS 15 Sequoia

**For educational purposes**

I don't take any responsibility for you voilating the Apple ToS and/or damaging your device.

## Installation

```
PlatformInfo -> Generic -> Add Serial, SystemUUID and MLB for SMBIOS Macmini8,1
```

## Base Specs

- CPU: i3-8100T
- GPU: Intel HD630 (DP, HDMI)
- Motherboard: Intel B360
- Audio Codec: ALC235
- WiFi & Bluetooth: Intel AX210

## BIOS

```md
Secure Boot - Disabed
Serial Port - Disabled
USB Support - Enabled
USB Legacy Support - Disabled
USB Enumeration Delay - Disabled
Front USB Ports , Rear USB Ports - Enabled
SATA Controller - Enabled
Configure SATA as - AHCI
Hard-disk Pre Delay - Disabled
```

## Limitations 

- No AirDrop support due to Intel WiFi (can be fixed by using _BCM_ card and _OCLP_).
- No compatibility for software that requires T2 chip. Such as Apple Inteligence, iPhone Mirroring etc.

## Notes

WiFi will be shown as Ethernet Interface. Joining networks requires [HeliPort](https://github.com/OpenIntelWireless/HeliPort).
