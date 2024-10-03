# pdx234

### 10-03-2024

#### packages/apps/Updater

* d1eec91  Updater: Fix broken download ETA/progress  [Salvo Giangreco]

#### prebuilts/tools-parasite

* 459a56f  Update APKEditor  [someone5678]

### 10-02-2024

#### external/openssh

* 60ca886  ssh program now resides in /product/bin  [Yumi Yukimura]

#### lineage/scripts

* 888f784  pixel: extract-utils: implement V1 image unpacking in fbpack  [Cosmin Tanislav]

#### packages/apps/Aperture

* 822ce5c  Automatic translation import  [LineageOS Infra]

#### prebuilts/extract-tools

* b126753  linux-x86: remove qc_image_unpacker  [Cosmin Tanislav]

#### vendor/aosp

* 80f26b9  kernel: Allow to override toolchain prefix used for vDSO32 building  [Alex Winkowski]

#### vendor/google/gms

* 420a6ba  gms: Overrides AOSP SoundPicker with SoundPickerPrebuilt  [someone5678]
* 10c0ed5  gms: config: Update package list  [someone5678]

#### vendor/google/overlays/ThemeIcons

* 49c187a  ThemeIcons: Update Lawnicons  [someone5678]
* a25315c  workshop: Automatically update resources and xml  [someone5678]
* 05a7c16  workshop: Update drwtochange  [someone5678]
* cca0296  Update README.md  [someone5678]
* 1bfda14  ThemeIcons: Import Lawnicons  [someone5678]

#### vendor/parasite/common

* 174e91c  PixelPropsUtils: Update spoofing  [someone5678]

### 10-01-2024

#### hardware/qcom-caf/sm8550/audio/primary-hal

* 99ae016  hal: Guard primary audio HAL in case target provides prebuilt  [Bruno Martins]

#### vendor/aosp

* 43a5e7d  vendor: BlackTheme: Rework shades of system container  [Pranav Vashi]

#### vendor/google/overlays/ThemeIcons

* d13a086  Update README.md  [someone5678]
* 069850b  ThemeIcons: Initial lawnicons-workshop  [someone5678]
* edffbcf  ThemeIcons: Clean-up before import  [someone5678]

### 09-30-2024

#### bootable/recovery

* 8387dfd  minui: drm: Add support for DRM_FORMAT_XRGB8888  [Yumi Yukimura]
* 7345b22  install: fuse_install: Browse directory using std::filesystem  [Yumi Yukimura]
* 9dfdbbd  volume_manager: Add support for ISO9660/UDF CD-ROM  [Yumi Yukimura]

#### device/qcom/sepolicy_vndr/sm8550

* 16b4946  sepolicy_vndr: Allow init/vendor_init to write proc firmware config  [Luofan Chen]
* cb57a5f  sepolicy_vndr: Label proc firmware config node  [Luofan Chen]

#### device/sony/sm8550-common

* 97f8862  sm8550-common: Commonize dynamic partition configs  [someone5678]
* b57789e  sm8550-common: Automatically cacluate dynamic partition size  [someone5678]
* 682f4c5  sm8550-common: Automatically calculate BOARD_FLASH_BLOCK_SIZE  [someone5678]

#### device/xiaomi/sweet

* 5dafa68  sweet: Correct BOARD_AVB_VBMETA_SYSTEM_ROLLBACK_INDEX_LOCATION  [someone5678]
* 7338d54  sweet: Correct BOARD_AVB_RECOVERY_ROLLBACK_INDEX  [someone5678]
* 7f3da54  sweet: Build LED based vibrator  [someone5678]
* 629bf55  sweet: Switch to armv9-a ARCH variant  [Pranav Vashi]
* 5f58626  sweet: Match CPU arch configs with CLO  [Bruno Martins]
* 6279514  sweet: Automatically calculate BOARD_FLASH_BLOCK_SIZE  [someone5678]
* 17f45c2  sweet: Automatically cacluate dynamic partition size  [someone5678]
* 58cc144  sweet: Commonize dynamic partition configs  [someone5678]

#### external/ntfs-3g

* d1351b8  config.h: Update version to 2022.10.3  [someone5678]
* 03edc90  config.h: Update version to 2022.5.17  [Michael Bestas]
* 1b22b3e  Ignore Waddress-of-packed-member warnings  [Michael Bestas]
* a977595  ntfs-3g: Fix argument parsing issue of Android 8.0  [Chih-Wei Huang]
* c5d4323  ntfs-3g: Fix compilation warning  [Steve Kondik]
* f7d089c  ntfs-3g: Add support for android builds  [Michael Bestas]
* f5b860c  ntfs-3g: Add .gitupstream  [someone5678]

#### kernel/sony/sm8550

* 374cea3  ARM64: configs: Enable kprobes  [LuK1337]

#### kernel/xiaomi/sweet

* 17e30d18  sweet: Enable OverlayFS support in kernel  [ahnet-69]
* db165fc  ARM64: configs: Enable kprobes  [LuK1337]

#### manifest

* e8ff1af  manifest: parasite: Track external/ntfs-3g  [someone5678]
* 57056e0  Revert "manifest: parasite: Track sm8450/8550 sepolicy_vndr"  [someone5678]
* fd80dd4  Reapply "manifest: lineage: Track device/qcom/sepolicy_vndr/sm8550"  [someone5678]

### 09-29-2024

#### hardware/qcom-caf/sm8250/display

* 58c486b  Add missing libc++ includes  [Tomasz Wasilczyk]

#### vendor/aosp

* 9b1ac8b  vendor: AndroidBlackTheme: Turn colors_material bg colors to black  [someone5678]

