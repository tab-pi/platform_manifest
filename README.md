# Sync Android Source (AOSP)

 $ repo init -u https://github.com/tab-pi/platform_manifest -b nougat

 $ git clone https://github.com/android-rpi/local_manifests .repo/local_manifests

 $ repo sync

## Build for Raspberry Pi3
 https://github.com/android-rpi/device_brcm_rpi3

Use -j[n] option on sync & build steps, if build host has a good number of CPU cores.

Graphics HAL of this build : https://github.com/anholt/mesa/wiki/VC4
