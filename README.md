# Hackintosh EFI Coffee lake

![alt text](https://github.com/renopp/hackintosh-efi/blob/main/thumbnail.png)

## How to fix Issue

- Fix Wake Up / Sleep Issue after sleep

1. Go to Preference - Energy Saver
2. Disable PowerNap and set turn off display 1 min

## Build 1 Used By [@renopp](https://github.com/renopp)

| PC Specs            | Information                          |
| ------------------- | ------------------------------------ |
| Processor           | Intel Core i7 8700                   |
| Integrated Graphics | Intel UHD 630                        |
| CPU Cooler          | Cooler MasterLiquid ML240R RGB       |
| Motherboard         | Gigabyte Intel Z390 Aorus Elite      |
| Memory              | Adata DDR4 XPG Spectrix 2666Mhz 16GB |
| Storage             | Samsung SSD 970 EVO M.2 250GB        |
| Wireless USB        | Archer T2U Plus                      |
| Bootloader          | OpenCore 0.6.2                       |
| Monitor             | ViewSonic VX3276-2K-mhd              |
| Headphone           | dbE GM500                            |

### Result:

- Shutdown ✅
- Restart ✅
- Sleep ✅
- Update OTA ✅
- Ethernet (untested) ⚠️

---

## Build 2 Used By [@GeuntaBuwono](https://github.com/GeuntaBuwono)

| PC Specs            | Information                                   |
| ------------------- | --------------------------------------------- |
| Bootloader          | OpenCore 0.6.4                                |
| Processor           | Intel Core i9 9900K                           |
| Integrated Graphics | Intel UHD 630 1536 MB                         |
| CPU Cooler          | Noctua NH-D15                                 |
| Motherboard         | Gigabyte Intel Z390 Aorus Master              |
| Memory              | Corsair CMK32GX4M2B3200C16 DDR4 3200Mhz 32GB  |
| Memory              | Corsair CMK16GX4M2A2666C16 DDR4 2666Mhz 16GB  |
| Storage             | Samsung 970 EVO Plus NVME M.2 500GB           |
| Monitor             | DELL U2715H (2560x1440)                       |
| Headphone           | HyperX Cloud II - 7.1 Surround Gaming Headset |

### Result:

- Shutdown ✅
- Restart ✅
- Update OTA ✅
- Ethernet ✅
- Develop iOS App (Xcode) with Real Device (iPhone XR) ✅

### Issue

- Build in Wi-Fi and Bluetooth Aorus Master ❌ (expected because new Intel CNVi that macOS doesn't support)

---

## Build 3 Used By [@99ridho](https://github.com/99ridho)

| PC Specs            | Information                        |
| ------------------- | ---------------------------------- |
| Processor           | Intel Core i7 9700K                |
| Integrated Graphics | Intel UHD 630                      |
| CPU Cooler          | be quiet! Dark Rock 4              |
| Motherboard         | Gigabyte Intel Z390 Aorus Elite    |
| Memory              | Adata DDR4 XPG Gammix 3000Mhz 32GB |
| Storage             | Adata SX6000LNP M.2 250GB          |
| Wireless Card       | BCM943602CS PCI-E                  |
| Bootloader          | OpenCore 0.6.2                     |
| Monitor             | MSI Optix G241                     |
| Headphone           | HyperX Cloud Alpha S               |

### Result:

- Shutdown ✅
- Restart ✅
- Sleep ✅
- Update OTA (untested)
- Ethernet ✅
- Bluetooth ✅
- Wifi ✅
- Continuity (Airdrop, Call, etc) ✅
