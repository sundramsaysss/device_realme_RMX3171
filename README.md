Realme Narzo 30A Device Tree - RMX3171
================================================================


Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (2x2.2 GHz Cortex-A75 & 6x1.8 GHz Cortex-A55)
Chipset | MediaTek Helio G85 (12 nm)
GPU     | Mali-G52 2EEMC2
Memory  | 3/4 GB
Shipped Android Version | Android 10, realme UI 1.0 
Storage | 32/64 GB (eMMC type)
MicroSD | Up to 512 GB 
Battery | Li-Po 6000 mAh, non-removable
Dimensions | 164.4 x 75 x 9 mm (6.47 x 2.95 x 0.35 in)
Display | 720 x 1560 pixels, 6.50" IPS LCD, 20:9 ratio (~270 ppi density)
Rear Camera  | Dual : 13 MP; 2MP(depth)
Front Camera | Single: 8 MP
Release Month | 2021

![Realme Narzo 30A](https://fdn2.gsmarena.com/vv/pics/realme/realme-narzo-30a-1.jpg "Realme Narzo 30A")


Patches needed:

1. Needed to boot: https://github.com/SamarV-121/android_vendor_extra/blob/lineage-18.1/patches/external/selinux/0001-Revert-libsepol-Make-an-unknown-permission-an-error-.patch
2. Needed for AV fix: https://github.com/phhusson/platform_frameworks_av/commit/624cfc90b8bedb024f289772960f3cd7072fa940.patch

Copyright (C) 2021 Lineage OS
