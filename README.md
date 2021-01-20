# LEGION-Y520-macOS
files necessary to boot macOS on Lenovo Legion Y520

Catalina (10.15.X):
- Clover r5122
- OpenCore v0.6.5

Big Sur (11.X):
- OpenCore v0.6.5

### Specifications

- CPU: i5 7300HQ
- RAM: 8GB 2400Mhz (1x8GB)
- GPU: Intel HD 630 & Nvidia GTX 1050Ti 4G (Nvidia disabled in macOS)
- WIFI: DW1560/BCM94352Z

### Usage

Update SMBIOS with generated data before using.

**NOTE: SSDTs that are pre-generated are specific to the machine that this repo is based on and may not work properly for another machine.**

### TODO

- implement script to fetch/build needed resources from source
- fix trackpad physical buttons
- rebuild SSDT with OS conditional (booting Windows from OC makes it bootloop)

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
