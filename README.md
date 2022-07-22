# x570-monterey

EFI for Installing MacOS Monterey on AMD x570 boards.

#### Spoiler

I was able to successfully [install Mac OS Monterey](https://www.reddit.com/r/hackintosh/comments/w174zt/amd_3900x_amd_6600_xt_build_monterey/), except for ethernet everything I need worked out of the box. I have been using it in my primary machine and surprisingly it is more stable than any linux distro i have used in the past. If you run into any issues each out to me, I will try to you help as best as I can.

### Instructions

1. Follow the guide [here](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/) to get MacOS Recovery files.

2. You can copy my EFI folder directly, or you can follow the open core guide to create a USB stick yourself.

3. If you decide to use my EFI, please user [this guide](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#platforminfo) to generate SMBIOS.

#### My Build

CPU: AMD 3900X - 12C/16T
GPU - MSI 6600XT 8 GB 0C
RAM: 128 GB (32 GB x 4 Hyper @ 3600 MHz)
Motherboard: Gigabyte Aorus X570 Pro Wi-Fi (rev 1.2)

##### What Works

[x] All NVMe / SATA Drive
[x] USB ports (at least all the ones I use)
[x] Microphone (I use a USB microphone)
[x] Audio (I Use line-out from the motherboard)
[x] Wi-Fi & Bluetooth - Through OpenIntelWireless
[x] Ethernet work now by skipping DHCP (setting static IP in mac and router) - with AppleGB kext

##### What doesn't work

[ ] Continuity
