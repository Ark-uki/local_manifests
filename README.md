# local_manifests
Local manifest for xiaomi note 12 5G and poco x5 (stone).

# Usage
```
cd /path/to/your/source/.repo && git clone https://github.com/Ark-uki/local_manifests.git
```
then,
```
repo sync -c -j$(nproc) --force-sync --no-clone-bundle --optimized-fetch --prune
```

# Credits
- [kernel_xiaomi_stone_rebase](https://github.com/mayuresh2543/kernel_xiaomi_stone_rebase)
- [device_xiaomi_stone_new](https://github.com/mayuresh2543/device_xiaomi_stone_new)
- [vendor_xiaomi_stone](https://github.com/mayuresh2543/vendor_xiaomi_stone)
- [android_hardware_xiaomi](https://github.com/LineageOS/android_hardware_xiaomi)

Thanks to all stone devs.
