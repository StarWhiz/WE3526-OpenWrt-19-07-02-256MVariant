# Update 2022.08.10
The official firmware works for the 256MB ram variant now!

https://downloads.openwrt.org/releases/21.02.3/targets/ramips/mt7621/

Look for "zbtlink_zbt-we3526-squashfs-sysupgrade.bin"


# WE3526-OpenWrt-19-07-02-256MVariant
The current stable release (19.07.02) for WE3526 is only for the 512MB Variant. For the 256MB Variant the stable release will create a soft brick.

I built this following OpenWrt's Quick Image Building Guide specifically for the 256MB Variant. So if you have the 256MB version of the WE3526 this sysupgrade.bin will work!

The only additions are that it has luci and luci-app-sqm. I run www.stoplagging.com so the luci-app-sqm is important and highly recommended for stopping bufferbloat.

Original post of the problem with the current official stable build (19.07.02) for the WE3526
https://forum.openwrt.org/t/zbt-we3526-soft-bricks-everytime-256mb-ram-variant/61913

This got fixed in https://git.openwrt.org/1e0bbd0ce766d5 so you may see it on the official repository sometime soon.
