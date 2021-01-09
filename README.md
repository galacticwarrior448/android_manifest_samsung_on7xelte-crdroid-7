# android_manifest_samsung_on7xelte-crdroid-7
Manifest file for on7xelte for building crDroid 7. (forked from https://github.com/samsungexynos7870/android_manifest_samsung_on7xelte )
# crDroid

### How to build ###

```bash
# Create dirs
$ mkdir crDroid ; cd crDroid

# Init repo
$ repo init --depth=1 -u repo init -u git://github.com/crdroidandroid/android.git -b 11.0

# Clone my local repo
$ git clone https://gitlab.com/android_samsung_universal7870/manifest/android_manifest_samsung_on7xelte.git -b evox .repo/local_manifests

# Sync
$ repo sync

# Build
$ . build/envsetup.sh && lunch lineage_on7xelte-userdebug && brunch lineage_on7xelte-userdebug
```

## Credits
2019 @Astrako

## Contact
Telegram support group: https://t.me/joinchat/D1Jk_VbieGBXOWZt2y8O7A
