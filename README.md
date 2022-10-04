# LEGION-Y520-macOS
EFI for Lenovo Legion Y520

**OpenCore 0.8.4**

Known to work on:
- Monterey 12.6
- Big Sur 11.7

### Specifications

- CPU: i5 7300HQ
- RAM: 24GB 2400Mhz (1x16GB + 1x8GB)
- GPU: Intel HD 630 & Nvidia GTX 1050Ti 4G (Nvidia disabled in macOS)
- WIFI: DW1560/BCM94352Z
- SSD: Samsung 970 Pro 1TB (known TRIM issues, NVMeFix.kext can be removed if not needed)

### Usage

Update SMBIOS with generated data before using.

**NOTE: SSDTs that are pre-generated are specific to the machine that this repo is based on and may not work properly for another machine.**

### TODO

- implement script to fetch/build needed resources from source
- fix trackpad physical buttons
- rebuild SSDT with OS conditional (booting Windows from OC can make it 
bootloop)

### Credits
- [abdulilah99](https://github.com/abdulilah99) (original HS guide)
- [the-braveknight](https://github.com/the-braveknight)
- [acidanthera](https://github.com/acidanthera)
- [RehabMan](https://github.com/RehabMan)
- [vit9696](https://github.com/vit9696)
- [Mieze](https://github.com/Mieze)
- Clover Team
- OpenCore Team
- others
