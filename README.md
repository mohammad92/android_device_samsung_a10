## Recovery Device Tree for the Samsung Galaxy A10 (Exynos)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_a10-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_a105f
