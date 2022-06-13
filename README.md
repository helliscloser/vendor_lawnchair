# vendor_lawnchair
Lawnchair 12.x


Lawnchair AOSP based build system

Getting started
1. Add this repository to your AOSP build root's vendor/lawnchair

2. Import vendor/lawnchair/lawnchair.mk

$(call inherit-product-if-exists, vendor/lawnchair/lawnchair.mk)

3. Remove existing launcher from the build

ParanoidQuickStep, Launcher3QuickStep, PixelLauncher and TrebuchetQuickStep packages are overriden from priv-app/Lawnchair/Android.mk.

If your existing launcher uses a different name, either remove it from the build manually or post a pull-request.

4. Build Android
