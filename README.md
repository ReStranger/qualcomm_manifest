# msm-5.15

Used tag: LA.VENDOR.13.2.1.r1-13800-DIVAR.QSSI16.0

# Sync
- Init

```
repo init -u https://github.com/ReStranger/qualcomm_manifest -b upstream -g default,-mips,-darwin,-notdefault
```

- Sync

```
repo sync -c -j$(nproc --all) --current-branch --no-clone-bundle --optimized-fetch --prune --force-sync --no-tags
```
# Build
```

```
