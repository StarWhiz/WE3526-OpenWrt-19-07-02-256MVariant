# WE3526-OpenWrt-19-07-02-256MVariant
The current stable release (19.07.02) for WE3526 is only for the 512MB Variant. For the 256MB Variant the stable release will create a soft brick.

I built this following OpenWrt's Quick Image Building Guide specifically for the 256MB Variant. So if you have the 256MB version of the WE3526 this sysupgrade.bin will work!

The only additions are that it has luci and luci-app-sqm. I run www.stoplagging.com so the luci-app-sqm is important and highly recommended for stopping bufferbloat.

Original post of the problem with the current official stable build (19.07.02) for the WE3526
https://forum.openwrt.org/t/zbt-we3526-soft-bricks-everytime-256mb-ram-variant/61913
