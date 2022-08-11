# vendor_lawnchair
Lawnchair 12.x


Lawnchair AOSP based build system

Getting started
1. Add this repository to your AOSP build root's vendor/lawnchair

2. Import lawnchair to rom_devicecode.mk

$(call inherit-product-if-exists, vendor/lawnchair/lawnchair.mk)

3. Remove existing launcher from the build if necessary

ParanoidQuickStep, Launcher3QuickStep, PixelLauncher and TrebuchetQuickStep packages are overriden from priv-app/Lawnchair/Android.mk.


** Unofficial Builds taken from: https://t.me/LawnchairDevUpdates

** Using Themedicons by Teamfiles https://t.me/modulesrepo as Lawnicons alternative (has more themed icons)

Thanks to Lawnchair Team


