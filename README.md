# Just CAF

## Getting started

To sync and build Just CAF, Android N:
```
repo init -u git://github.com/Just-CAF/platform_manifest.git -b n-8992
```
Then to sync up:
```
repo sync -c --no-tags --no-clone-bundle -j$(nproc --all)
```

## Devices

Just CAF is designed for LGE Nexus 5X, msm8992.
