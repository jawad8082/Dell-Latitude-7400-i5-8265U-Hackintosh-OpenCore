# Dell-Latitude-7400-i5-8265U-OC-Hackintosh

OpenCore based EFI for Dell Latitude 7400 i5-8265U


## MacOS Version

- macOS BigSur
- macOS Monterey
- macOS Ventura
- macOS Sonoma
- macOS Sequoia

I am currently using macOS Ventura and will not upload EFI configs for any of the older versions or latest. If you want to install older or latest OS you need to put the appropriate Wi-fi/BT kexts.

## System Configuration

- CPU:  Intel Core i5-8265U
- iGPU: Intel UHD Graphics 620 (Whiseky Lake)
- RAM:  24GB DDR4 2666Mhz
- SSD:  512 GB PC SN730 NVMe WDC
- WiFi: Intel AC7265
- Display: 14" 1920*1080 FullHD IPS
- Sound Card: Realtek ALC295


### BIOS Version

1.24.0


### Bootloader

OpenCore



## BIOS Settings

- Boot mode: UEFI
- Fast Boot: Minimal
- SecureBoot: Disable
- SATA Mode: AHCI 
- Intel SGX: Software Controlled


## What's working

 
 - [x] CPU Speedstep

 - [x] iGPU acceleration

 - [x] Battery Management
 
 - [x] Sleep/Wake
 
 - [x] Internal Speakers
 
 - [x] Internal Microphone
 
 - [x] Audio Jack - Working with ALCPlugFix-Swift - https://github.com/black-dragon74/ALCPlugFix-Swift
 
 - [x] WiFi (2.4Ghz + 5Ghz)
 
 - [x] Bluetooth

 - [x] HDMI + audio over HDMI

 - [x] Touchpad with Gestures + Buttons
 

 - [x] Web Camera

 - [x] USB 3.0

 - [x] MicroSD card reader 

 - [x] Native hotkeys support with Fn keys (Screen Brightness Fn + B/S)
 
 - [x] USB-C charging

 - [x] USB-C DP-alt Mode
  
 - [x] USB-C Data transfer
 
 - [x] Thunderbolt (needs to plug a device before boot)
 
 


## What's not working

- Everything is working great so far!

## What's not tested yet

- WWAN card