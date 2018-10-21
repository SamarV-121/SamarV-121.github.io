---
layout: post
title:  Highly Compressed Source [LINEAGE][ANDROID][TWRP]
category: blog
excerpt: Compressed Source
author: Samar Vispute
---

![](http://pngimg.com/uploads/android_logo/android_logo_PNG15.png)

## What the fkuc this ?
**Its the heaven for those who have slow internet/limited bandwidth :3**

**_Basically its a Highly Compressed Android Rom source_**

### Date: 21-10-2018
* LineageOS-14.1: [Click here](https://androidfilehost.com/?w=files&flid=284194)(Total size: 8.1 GB)
* LineageOS-15.1: [Click here](https://androidfilehost.com/?w=files&flid=284193)(Total size: 11.3 GB)
* LineageOS-16.0: [Click here](https://androidfilehost.com/?w=files&flid=284093)(Total size: 13.2 GB) 
* TWRP-8.1(OMNI): [Click here](https://androidfilehost.com/?w=files&flid=284239)(Total size: 3.1 GB) 

### How to extract ? 
```
cat *.tar.xz* | tar -xvJf - -i
```

### Script: 
```
ROMNAME=lineage-14.1
LINK=https://github.com/LineageOS/android
BRANCH=cm-14.1
THREAD_COUNT_SYNC=Number of your CPU Threads

echo -e "# Installing necessary packages..."
sudo apt install bc pxz wput
echo -e "# Installed"

echo -e "# Installing repo..."
repo init -u $LINK -b $BRANCH --depth 1 -q
echo -e "# Installed"

echo -e "# Syncing..."
repo sync -c -f -q --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j$THREAD_COUNT_SYNC
echo -e "# Synced"

echo -e "# Starting Compression..."
export XZ_OPT=-9e
tar -I pxz -cf - * | split -b 4500M - $ROMNAME.tar.xz.
echo -e "# Compressed"

echo -e "# Uploading..."

echo -e "# Done"
```

#### Thanks to regalstreak For his amazing [Script](https://github.com/regalstreak/skadoosh)


