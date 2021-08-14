# Hackintosh with Opnecore (z370 i7-8700k rx580 8G 32gb ram)
<p align="center">
  <img src="./system.png" alt="System specs">
</p>

## Version
* <a href="https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/0ee84c4"><img src="https://is4-ssl.mzstatic.com/image/thumb/Purple124/v4/09/59/3d/09593d0e-188a-77eb-4c38-ca40bedd5cff/ProductPageIcon.png/460x0w.webp" height="32px"/></a>[macOS 11.5.2 Big Sur](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/0ee84c4)

* <a href="https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/0ee84c4"><img src="https://raw.githubusercontent.com/acidanthera/OpenCorePkg/master/Docs/Logos/LogoApprox.svg" height="34px"/></a>[OpenCore 0.7.2](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/0ee84c4)

## setup
* [How to decide](https://dortania.github.io/OpenCore-Install-Guide/extras/smbios-support.html#how-to-decide)
* reboot select reset nvram
* boot from macOS

## source
* https://www.tonymacx86.com/threads/success-ga-z370-aorus-gaming-7-i7-8700k-rx5700xt-oc.299852/
* https://www.tonymacx86.com/threads/amd-radeon-performance-enhanced-ssdt.296555/

## Hardware

* Intel Core i7-8700K Coffee Lake
* Gigabyte Z370 AORUS Gaming 7
* Gigabyte Radeon RX 580 GAMING 8G
* 2x16GB HyperX FURY DDR4 3466Mhz HX434C17FB4/16
* SSD CRUCIAL MX500 CT500MX500SSD1
* PCI-e Broadcom BCM4360 WiFi ac + USB Bluetooth 4.2

## ACPI
* SSDT-AWAC.aml
* SSDT-EC-USBX.aml
* SSDT-PLUG.aml
* SSDT-RX580.aml
* SSDT-UIAC.aml

## Kexts
* AirportBrcmFixup.kext
* AppleALC.kext
* AtherosE2200Ethernet.kext
* DAGPM.kext
* IntelMausi.kext
* IntelSnowMausi.kext
* Lilu.kext
* SMCProcessor.kext
* SMCSuperIO.kext
* USBPorts.kext
* VirtualSMC.kext
* WhateverGreen.kext

## Drivers
* AudioDxe.efi
* OpenHfsPlus.efi
* OpenCanopy.efi
* OpenRuntime.efi

## Tools
* OpenShell.efi

## BIOS (Download from folder restore in BIOS)
* F15b (BIOS babckup)
* Profiles 0.7 (Profiles backup)

### Other version
#### f34b94f
* [macOS 11.5 Big Sur](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/f34b94f)
* [OpenCore 0.7.2](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/f34b94f)
#### 7c9881a
* [macOS 11.4 Big Sur](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/7c9881a)
* [OpenCore 0.7.0](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/7c9881a)
#### 9e52064
* [macOS 11.3 Big Sur fix usb mapping](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/9e52064)
* [OpenCore 0.6.8](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/9e52064)
#### 95410af
* [macOS 11.2.3 Big Sur](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/95410af)
* [OpenCore 0.6.8](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/95410af)
#### 652d15a
* [macOS 11.2.2 Big Sur](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/652d15a)
* [OpenCore 0.6.7](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/652d15a)
#### 4a7d29a
* [macOS 11.2 Big Sur](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/4a7d29a)
* [OpenCore 0.6.6](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/4a7d29a)
#### 908baab a7e27f6
* [macOS 11.0.1 Big Sur](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/908baab)
* [OpenCore 0.6.5](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/908baab)
* [OpenCore 0.6.3](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/a7e27f6)
#### 2af5c9
* [macOS 10.15.7 Catalina](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/2af5c9)
* [OpenCore 0.6.3](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/2af5c9d)
#### ba1036b 66c2799
* [macOS 10.15.6 Catalina](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/ba1036b)
* [OpenCore 0.6.2](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/ba1036b)
* [OpenCore 0.6.1](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/66c2799)
# ALAC1220 (顯示由上而下)
## 1 
  Linein k
  Linein j
  耳機 n 前板插入斷聲音 還是耳機
## 2
  Linein o
  Linein m
  耳機 n
  前板 內建
## 7
  Linein j
  Linein k
  耳機 n 沒聲音
  前板 內建
## 11
  Linein j
  Linein  k
  耳機 n 沒聲音
  前板 內建
## 16
  Linein k
  Linein j
  耳機 前板
  內建 n
## 27
  Linein j
  Linein k
  Linein 沒聲音
  (n 沒聲音)
  內建 前板
## 28
  Linein j
  Linein k
  內建 n (需手動切換)
  內建 前板 (需手動切換)
## 29
  Linein j
  Linein k
  耳機 n 沒聲音
  內建 前板