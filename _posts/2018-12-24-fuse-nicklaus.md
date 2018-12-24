---
layout: post
title:  Fuse-Kernel-r3 3.18.131 For Motorola Moto E4 Plus
category: blog
excerpt: Fuse-Kernel-r3
author: Samar Vispute
---

![Fuse](https://2.bp.blogspot.com/-S6utd9l5MWs/WakT7Iy6goI/AAAAAAAAFFY/3EUkZJsHDAMVud1QI8BlRS-UC9s7Ce8nQCLcBGAs/s640/fuse-asheville-logo-design.png)

### Features
* Upstreamed to Latest Linux version 3.18.131
* Compiled with Latest Linaro-7.2
* Updated MTK GPU Driver to r18p0
* ThunderQuake Engine: Vibration Intensity Controller 
* Wi-Fi Power Management Control
* WireGuard VPN tunnel support included ( visit for more info: https://www.wireguard.com )
* LZ4 compression for ZRAM enabled by default
* RGB Colour Control
* CPU optimizations
* Added Powersuspend Driver - new Power Management kernel driver for Android w/o early_suspend
* Removed safetynet flags (no need of magisk to bypass safteynet)
* Tuned interactive governor
* upports F2FS,exFAT Filesystems
* Reduced vfs cache pressure to 20 for better battery
* Increased Swappiness From 60 to 90
* Enabled L2TP VPN Protocol and SLIP TCP/IP Protocol
* Added wakelock toggles
* Enabled 5gHz band by default
* Automatic busybox installation
* Disabled Gentle fair sleepers
* Added Dynamic Fsync support
* Disabled GFS and enabled ARCH_POWER
* Disabled NOATIME and NODIRATIME by default
* Disabled crc check for 30% extra performance
* Optimized for Cortex-A53 ARM 
* Better performance
* Governors: alucard, darkness, ondemand, userspace, powersave, interactive(default), performance
* Hotplugs: alucard_hotplug, thunderplug, mako_hotplug
* I/O Schedulers: noop, deadline, cfq, bfq, fiops(default)
* TCP congestion algorithm: cubic, reno, westwood(default), bic, htcp, highspeed, vegas, veno, scalable, lp, yeah, illinois

### Kernel info
* Kernel - 3.18.131
* Chipset - MediaTek MT6737M

### Changelog
2018-12-24 (r3)
* Upstreamed to Latest Linux Kernel 3.18.131
* Merged updates from new official kernel release - https://github.com/MotorolaMobilityLLC/kernel-mtk/releases/tag/MMI-NMA26.42-162
* F2FS loopback fixed (Click here for more info)[https://github.com/SamarV-121/android_kernel_motorola_mt6735/issues/2]
* Added fiops I/O Sched
* RGB color control (MTK KCAL colout control)

2018-04-28 (r2)
* Upstreamed to Latest Linux Kernel 3.18.106
* Merged updates from new official kernel release - https://github.com/MotorolaMobilityLLC/kernel-mtk/releases/tag/MMI-NMA26.42-146
* Compiled with Linaro-7.2
* Updated MTK GPU Driver to latest r18p0
* Removed safetynet flags (no need of magisk to bypass safteynet)
* Tuned interactive governor
* Made Thunderplug as default CPU hotplug driver & Interactive as default CPU Governer ( You can change it by Kernel Auditor )
* Some more minor fixes/improvements

2018-03-23 (r1)
* Initial release 

### Downloads & sources
* Fuse - [Download](https://www.androidfilehost.com/?fid=11410963190603881393)

* Kernel Source - [View](https://github.com/SamarV-121/android_kernel_motorola_nicklaus)

### Feature controlling:
* [Modded Kernel Audiutor by bhb27](https://androidfilehost.com/?fid=962187416754468732) 
* [ThunderZap Control](https://play.google.com/store/apps/details?id=com.varun.thunderzapcontrol&hl=en_IN) Use ThunderZap Control for Wi-Fi Power Management, ThunderCharg, ThunderQuake Engine

### You can Donate Me if you like my work
* PM me on Telegram: [Click here](https://web.telegram.org/#/im?p=@SamarV121)

### Installation
1) Boot into the latest TWRP recovery

2) Flash the Kernel's zip

4) Reboot your device once the installation is done

### Device Lags a bit ?
Dont worry, it's a normal thing
* Get rid of unnecessary (background-)apps
* Try a different IO-Scheduler
* Try another profile
If you are experimenting huge lags, you have done something wrong

Remember dis, Performance ∝ Battery Consumption :v 
