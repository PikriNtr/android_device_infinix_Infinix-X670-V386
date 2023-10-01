this is for build only 
its already been modify like the twrp flags and more

to build this you need to clone manifest

just paste this

```repo init -u https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git -b twrp-12.1```

and then you need to sync

```repo sync```

after that clone this repository
and move this repo to device/Infinix/Infinix-X670


after that just start build it with this command
```. build/envsetup.sh```
```lunch omni_X670-eng```
```mka bootimage```
