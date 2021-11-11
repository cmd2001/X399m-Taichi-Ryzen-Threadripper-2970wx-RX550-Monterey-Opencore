# X399m-Taichi-Ryzen-Threadripper-2970wx-RX550-Monterey-Opencore

Monterey EFI(Opencore 0.7.4) for X399m Taichi Threadripper 2970wx GTX Titan Black


## My Hardware

* CPU: AMD Ryzen Threadripper 2970wx
* Graphics Card: AMD Radeon RX550 4G
* Motherboard: Asrock X399m Taichi
* Wi-Fi & Bluetooth: Intel AX200 (replaced motherboard's original AC3168)
* Network Adapter: Intel i211 x2
* Audio Card: Realtek ALC1220 (AppleALC Layout: 1)

## Tested macOS Version

macOS 11 Monterey (12.0-12.0.1)

## Compatibility

* AMD Ryzen Threadripper 2970wx (theoretically compatible with all 1st and 2nd generation Threadripper processors)
* All AMD & Nvidia Graphics Card works with whatevergreen.kext (maybe you have to edit boot arguments)
* All Intel WiFi & Bluetooth
* All Intel Network Adapter
* All Realtck Audio Card (maybe you have to edit AppleALC layout-id)

## What Works

* Video Acceleration
* Audio
* USB ports
* CPU Temperature and Voltage/Wattage
* Sleep
* WiFi
* Bluetooth
* Wired Network
* iMessage
* Handoff (sometimes works)
* Universal Clipboard
* Virtualization (Oracle Virtual Box)

## What does not Work

* Airdrop
* Connect to Hidden SSID (refer to airportitlwm)

## What will never Work

* Things do not work on AMD Vanilla

## BIOS Settings

* Turn on: AMD SVM, IOMMU, SR-IOV, Above 4G Decoding, WHQL Driver
* Turn off: CSM
* **If your motherboard does not support Above 4G Decoding, you should add npci=0x2000 in boot arguments**

# SMBios Settings

* Model: iMacPro 1,1
* **This EFI does not contain Model Settings, you need to add it by OC Configurator before first boot**