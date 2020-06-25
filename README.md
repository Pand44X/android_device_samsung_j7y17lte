# TWRP for the Samsung Galaxy J7 2017

### How to build ###

```bash
# Create dirs
$ mkdir twrp ; cd twrp

# Init repo
$ repo init --depth=1 -u https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-9.0

# Clone my local repo
$ git clone https://gitlab.com/android_samsung_universal7870/manifest/android_manifest_samsung_j7y17lte.git -b twrp .repo/local_manifests

# Sync
$ repo sync --no-repo-verify -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j`nproc`

# Build
$ mv device/samsung/j7y17lte/build_twrp.sh .
$ . build_twrp.sh j7y17lte
```
## Credits
2020 @Astrako

## Contact
Telegram support group: https://t.me/joinchat/D1Jk_VbieGBXOWZt2y8O7A
