---
layout: post
title:  Fuse-Kernel 3.10.108 For Android One 1st Gen
category: blog
excerpt: Fuse Kernel
author: Samar Vispute
---

![Fuse](https://2.bp.blogspot.com/-S6utd9l5MWs/WakT7Iy6goI/AAAAAAAAFFY/3EUkZJsHDAMVud1QI8BlRS-UC9s7Ce8nQCLcBGAs/s640/fuse-asheville-logo-design.png)

### Features
* Upstremed to latest Linux Kernel 3.10.108
* Oreo support added
* ThunderCharge Fast Charge Driver (enabled by default)(AC and USB current increased to 1000mA)
* Optimized SLUB
* Added exFAT support
* char: Add Frandom
* Asynchronous Fsync: initial extraction of Async Fsync from
* Enabled L2TP VPN Protocol and SLIP TCP/IP Protocol
* Added exFat Filesystem support
* Added advance TCP congestion algos like westwood, highspeed etc
* Added WireGuard VPN support
* Switched to Linaro 7.2.x toolchain
* Wakelock blocker added
* Cortex A7 optimisations
* Added power suspend driver
* Reduced vfs cache pressure to 20 from 100 for better battery
* tick: don't update idle time if cpu offline
* writeback: increase bdi_min_ratio to 5 in light of the latest writeback commit
* Increased Swappiness From 60 to 90
* Kernel Compressed with XZ
* power: wakeup: add wakelock toggles
* ThunderSonic Sound Control Engine
* WiFi Power management control
* Full GPU control
* DoubleTap2Wake and Sweep2Wake
* Dynamic Fsync Control
* Improved filesystem mounting flags - NOATIME and NODIRATIME
* ThunderQuake Engine 1.0 - Vibration Intensity Controller for MTK vibrators
* Huge update to kernel.org mainline 3.10.89
* ThunderPlug CPU Hotplug replacement
* init.d support
* Automatic busybox installation
* Disabled Gentle fair sleepers
* Enabled arch power
* Optimizations to SLUB memory allocator
* Patches to block and mm to significantly improve ssd IO performance.
* Dynamic entropy setting based on usage
* Dynamic management of dirty page writebacks
* block: Added SIO IOScheduler
* block: Add BFQ IOScheduler
* block: Add fiops scheduler
* cpufreq: ThunderX power saving CPU governor
* fs: added Samsung's F2FS support
* Reduce logger device RAM allocation to 128K
* Set MM Linux read ahead size to 256K
* Patches from upstream to optimize memory writeback
* Disabled CRC check in MMC for 30% extra performance with IO
* Reduced VFS cache pressure for better battery
* Optimized square root algorithm
* Governors enabled: ondemand, interactive
* Speedup /proc/net/unix interface access
* Mali GPU cache Optimizations
* Mali: Increase L2 cache max read size
* Mali: Disable state tracking
* Mali: Reduce GPU utilization timeout
* Mali: increase kernel memory buffer size
* Aggressive multicore power savings
* ARM: Cortex A7 compiler optimizations
* MTK: removed HUGE HUGE trail of stupid MTK kernel logging
* ARM: Removed various debug traces
* Added more features

### Kernel info
* Kernel - 3.10.xx
* Chipset - MediaTek MT6582

### Downloads & sources
* Fuse - [Download](https://www.androidfilehost.com/?fid=962187416754461009)

* Kernel Source - [View](https://github.com/SamarV-121/fuse_kernel_mediatek_sprout)

### You can Donate Me if you like my work
* PM me on Telegram: [Click here](https://web.telegram.org/#/im?p=@SamarV121)

### Installation
1) Boot into the latest TWRP recovery

2) Flash the Kernel's zip

4) Reboot your device once the installation is done

<!-- Begin Comments JavaScript Code --><script type="text/javascript" async>function ajaxpath_5b504428f1cab(url){return window.location.href == '' ? url : url.replace('&s=','&s=' + escape(window.location.href));}(function(){document.write('<div id="fcs_div_5b504428f1cab"><a title="free comment script" href="http://www.freecommentscript.com">&nbsp;&nbsp;<b>Free HTML User Comments</b>...</a></div>');fcs_5b504428f1cab=document.createElement('script');fcs_5b504428f1cab.type="text/javascript";fcs_5b504428f1cab.src=ajaxpath_5b504428f1cab((document.location.protocol=="https:"?"https:":"http:")+"//www.freecommentscript.com/GetComments2.php?p=5b504428f1cab&s=#!5b504428f1cab");setTimeout("document.getElementById('fcs_div_5b504428f1cab').appendChild(fcs_5b504428f1cab)",1);})();</script><noscript><div><a href="http://www.freecommentscript.com" title="free html user comment box">Free Comment Script</a></div></noscript><!-- End Comments JavaScript Code -->
