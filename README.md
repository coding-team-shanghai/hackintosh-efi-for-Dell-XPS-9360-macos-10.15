# macOS on Dell XPS 9360
Installiation method for dell xps 9360 in macOS Catalina on my device.
This repo's license is GNUv3. It means that you can get this repo out for your own repo or anything, but you need to have the address of this repo.
This repo is based on [the darkvoid](https://github.com/the-darkvoid/XPS9360-macOS)

## Used Hardware Configuration
- Dell XPS 9360
  - Intel i7-8550U
  - 16GB RAM
  - Sharp `SHP144` `LQ133Z1` QHD+ (3200x1800) Touchscreen display
  - [Western Digital Black 512GB SSD](http://a.co/8JOsXFG) (WDS512G1X0C-00ENX0) on latest firmware
    - Formatted for APFS with 4K sectors, using [nvme-cli](https://github.com/linux-nvme/nvme-cli) using this [guide](https://www.tonymacx86.com/threads/guide-sierra-on-hp-spectre-x360-native-kaby-lake-support.228302/)
  - Dell DW1560 Wireless (eBay)
    - Wi-Fi device ID [`14e4:43b1`], shows as Apple Airport Extreme due to `FakePCIID_Broadcom_WiFi.kext`
    - Bluetooth device ID [`0a5c:216f`], chipset `20702A3` with firmware `v14 c5882` using `BrcmPatchRAM2.kext`
  - Sonix Technology Webcam, device ID [`0c45:670c`], works out of the box
  - Validity Inc. Finger print scanner, device ID [`138a:0091`], [linux open-source project](https://github.com/hmaarrfk/Validity91)
  - Disabled devices
    - Touchscreen (though it works out of the box if enabled)
    - SD card reader, [macOS open-source project](https://github.com/sinetek/Sinetek-rtsx)

- Firmware Revisions
  - BIOS version `2.9.0`
  - Thunderbolt Controller firmware version `NVM 26`
