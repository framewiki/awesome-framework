# Awesome Framework
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of projects, tools, documentation and resources related to the Framework Laptop

## Contents
- [Disclaimer](#disclaimer) - Please read!
- [Expansion Cards](#contents)
- [Mainboard Enclosures](#mainboard-enclosures)
- [Embedded Controller Firmware Mods](#embedded-controller-firmware-mods)
- [Linux Support](#linux-support)
- [Accessories](#accessories)
  - [Chargers](#chargers)
  - [Docking Stations](#docking-stations)
  - [Cases and Sleeves](#cases)
- [Hardware Support](#hardware-support)
  - [Storage](#storage)
  - [Memory](#memory)
  - [WiFi Cards](#wifi-cards)
- [Troubleshooting](#troubleshooting)

## Disclaimer
This repository and the resources within it are **COMPLETELY UNOFFICIAL** and not in any way endorsed or supported by Framework. Your use of these guides and projects is **AT YOUR OWN RISK** and **MAY VOID YOUR WARRANTY.** We ask that you do not reach out to Framework support about problems related to these resources, but you can feel free to reach out to the community maintainers via GitHub Discussions or Issues within this repository.

> **Note**
> Parts listed as community validated are not on Framework's list of officially supported parts. While they have been tested by members of the community, there is no guarantee that they will work for you.

## Expansion Cards
- [Josh_Cook]()
  - UART [GitHub](https://github.com/jyancat/UART-Expansion-Card) and [Store](https://lectronz.com/products/uart-expansion-card) - Complete UART expansion card, available as pre-assembled from his store, or design files on GitHub.

## Mainboard Development
- [Mainboard Reference](https://github.com/FrameworkComputer/Mainboard) - Physical and electrical reference for the Mainboard (and a 3D printable enclosure).
- [WhatTheFilament](https://github.com/whatthefilament)
  - [Framework-Motherboard-Reference-CAD](https://github.com/whatthefilament/Framework-Motherboard-Reference-CAD) - To-scale CAD reference of the Mainboard.
  - [Frame-WorkStation](https://github.com/whatthefilament/Frame-WorkStation) - Desktop enclosure.
  - [Framework-Desktop-Adapter](https://github.com/whatthefilament/Framework-Desktop-Adapter) - ATX mount adapter.
  - [Framework-Tablet](https://github.com/whatthefilament/Framework-Tablet) - Tablet conversion case.
  - [FrameStation](https://github.com/whatthefilament/FrameStation) - Game console enclosure.
  - [Framework-Test-Bench](https://github.com/whatthefilament/Framework-Test-Bench) - Development/Test bench.
- [DIY Perks "Triple-Screen Laptop DONE RIGHT!"](https://www.youtube.com/watch?v=aUKpY0o5tMo) - Custom triple-screen portable computer using Framework mainboard and battery.

## Embedded Controller Firmware Mods
- [DHowett](https://github.com/DHowett) (AKA The EC Guy)
  - [Hacking your Framework Laptop’s EC for fun and profit](https://www.howett.net/posts/2022-04-adding-an-ec-feature-1/) - Great place to start hacking your EC.
  - [ECTool.EFI](https://github.com/DHowett/FrameworkHacksPkg) - EFI Shell application for flashing the EC.
- [EC Firmware Source Code](https://github.com/FrameworkComputer/EmbeddedController)

## Linux Support
- [Distro List](https://frame.work/linux) - List of officially supported distros and links to their setup guides.
- [Arch Wiki](https://wiki.archlinux.org/title/Framework_Laptop) - The arch wiki entry for the Framework Laptop.
- [LinuxLaptops Wiki](https://github.com/lhl/linuxlaptops/wiki/2022-Framework-Laptop-DIY-Edition-12th-Gen-Intel-Batch-1) - Wiki article with a ton of useful information specific to linux on the framework laptop.
- [Linux Battery Life Forum Thread](https://community.frame.work/t/linux-battery-life-tuning/6665) - This will be replaced (soon) by a page in this repo since this is outdated and (in some places) incorrect. 
- [Common Problems](/linux/common-problems.md) - A collection of common issues with running Linux on the Framework laptop and their solutions.(

## Accessories
### Chargers
- [Official Framework Power Adapter](https://frame.work/products/power-adapter?v=FRANCEPH0B) - Framework's first-party USB-PD charging adapter. 
- [Anker 65W Nano](https://www.amazon.com/dp/B08T5QN2TR) - Community validated single-port 65W PD charger.

### Docking Stations
- [Thunderbolt 4 Support](https://knowledgebase.frame.work/does-the-framework-laptop-support-thunderbolt-rkjEJn4Jt) - Official knowledgebase article on TB4 support.
- [Anker 777 TB4 Docking Station](https://www.amazon.com/gp/product/B0928W3XHD) - Community validated docking station with HDMI, USB-A, USB-C, SD and Audio. All I/O options work out-of-the-box on 12th gen Framework running Ubuntu 22.04.

### Cases and Sleeves
- [Case Logic Reflect 13"](https://www.caselogic.com/en-us/laptop-bags/laptop-sleeves/case-logic-reflect-13-laptop-sleeve-_-3204690) - Community [tested](https://github.com/Morpheus636/awesome-framework/issues/10#issuecomment-1325427414) laptop sleeve. Ensure you do NOT get the MacBook version as it will not fit.
- [Tomtoc Laptop Shoulder Bag 13-13.5"](https://www.amazon.com/dp/B072L4R2DY) - Community [validated](https://github.com/Morpheus636/awesome-framework/issues/10#issuecomment-1325465369) laptop case / shoulder bag.
- [FINPAC Hard Case for 13" MacBook](https://www.amazon.com/dp/B088WNMW8N) - Community [validated](https://github.com/Morpheus636/awesome-framework/issues/10#issuecomment-1325754958) hard laptop case.

## Hardware Support

### Storage
- [Officially Validated SSD List](https://knowledgebase.frame.work/en_us/what-storage-ssd-parts-are-compatible-with-the-framework-laptop-rJOOeHU0_)
- [SK Hynix Gold P31](https://www.amazon.com/dp/B08DKB5LWY) - Community validated SSD. Available in 500GB, 1TB and 2TB sizes.
- [Crucial P2](https://www.amazon.com/gp/product/B086BGWNY8/) - Community validated SSD. Available in 256GB, 500GB, 1TB and 2TB.

### Memory
- [Officially Validated DRAM List](https://knowledgebase.frame.work/en_us/what-memory-dram-parts-are-compatible-with-the-framework-laptop-ry_jbS8Ru)
- [Crucial CT2K16G4SFD832A](https://www.amazon.com//dp/B07Q7T9NSC) - Community validated DDR4-3200 CL22 RAM. Available in 32GB (2x16GB) kits.
- [SK Hynix HMAA1GS6CJR6N](https://www.amazon.com/dp/B0BM9YL1C5/) - Community validated DDR4-3200 RAM. Available in 8GB (1x8GB) kits.
- [SK Hynix HMA851S6CJR6N](https://www.amazon.com/dp/B092RK7KLM/) - Community validateed DDR4-3200 RAM. Available in 4GB (1x4GB) kits.

### WiFi Cards
- [Officially Validated Wifi Card List](https://knowledgebase.frame.work/en_us/what-wifi-parts-are-compatible-with-the-framework-laptop-rytGfHU0d)

## Troubleshooting

## Community
- [Framework Forums](https://community.frame.work)
- [Framework Discord](https://discord.com/invite/Framework)
- [Framework Subreddit](https://reddit.com/r/framework)

## Contributing
This list's Contribution Guidelines can be found [here.](/contributing.md)

