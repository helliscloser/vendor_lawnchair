## vendor_lawnchair



### Lawnchair AOSP based build system

***Getting started***

1. Add this repository to your AOSP build root's <br>
`vendor/lawnchair`

2. Import lawnchair to **rom_devicecode.mk** _(Example: cherish_davinci.mk)_
> `$(call inherit-product, vendor/lawnchair/lawnchair.mk)` * inherit-product <br>
**OR**<br>
> `$(call inherit-product-if-exists, vendor/lawnchair/lawnchair.mk)` * inherit-product-if-exists

3. Remove existing launcher from the build if necessary

`ParanoidQuickStep, Launcher3QuickStep, PixelLauncher and TrebuchetQuickStep` packages are overriden from priv-app/Lawnchair/Android.mk.



#### **All Credits to [Lawnchair Team](https://github.com/LawnchairLauncher/lawnchair)**
**Credits: Themedicons by [Teamfiles](https://t.me/modulesrepo) as Lawnicons alternative (has more themed icons)**




