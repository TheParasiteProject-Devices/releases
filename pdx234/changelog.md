# pdx234

### 10-01-2024

#### vendor/aosp

* 43a5e7d  vendor: BlackTheme: Rework shades of system container  [Pranav Vashi]

#### vendor/google/overlays/ThemeIcons

* fa14551  ThemeIcons: Import Lawnicons  [someone5678]
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

#### vendor/aosp

* 9b1ac8b  vendor: AndroidBlackTheme: Turn colors_material bg colors to black  [someone5678]

### 09-29-2024

#### hardware/xiaomi

* 6dab5e6  interfaces: com.fingerprints: Add `IFpcFingerprintAuthenticator`  [Giovanni Ricca]
* 99c1459  sensors: Implement double tap sensor  [Cosmin Tanislav]
* db04d3c  sensors: Implement single tap sensor  [Arian]
* c8ecac6  sensors: Implement udfps long press sensor  [Arian]
* be08171  sensors: Let the reading of poll fd be configurable  [Arian]
* 65b8870  vibrator: Add support for TEXTURE_TICK effect  [someone5678]
* d37d84f  dolby: Add intelligent equalizer setting  [Adithya R]
* 4b36612  dolby: Remove deprecated PlainTooltipBox  [Pranav Vashi]
* 1e0e296  dolby: Introduce graphical equalizer  [Adithya R]
* cc67888  dolby: Add launcher icon  [Pranav Vashi]
* 3259e71  fixup! dolby: Restore all settings upon bootup  [Adithya R]
* 6bc197e  dolby: Override AudioFx  [Pranav Vashi]
* c76a613  dolby: Use all shared resources from devicesettings  [Bruno Martins]
* 921a18c  dolby: Fix build with kotlinc 1.9.0  [basamaryan]
* 79fc21a  dolby: Restore current profile _after_ resetting profiles  [Adithya R]
* 1f0a442  dolby: Do not set volume leveler amount  [Adithya R]
* b67f0e5  dolby: Restore all settings upon bootup  [Adithya R]
* 7f97359  dolby: Rewrite in Kotlin  [Adithya R]
* 1dcd26f  dolby: Revert "Re-enable speaker virtualization after bootup"  [Adithya R]
* 3be5d01  dolby: Convert to SwitchPreferenceCompat  [Michael Bestas]
* dabe9dc  DolbyManager: Migrate to CompoundButton.OnCheckedChangeListener  [Chaohui Wang]
* eb1d971  dolby: Enable use_resource_processor for all sysui deps  [Peter Kalauskas]
* 29df320  xiaomi: Introduce Dolby Atmos  [Adithya R]
* 3b8c736  vintf: Add IMiSys HAL in compatibility matrix  [Piotr Kozimor]
* e95432e  vintf: Add more hals to fcm  [Adithya R]
* b748d56  XiaomiEuicc: Remove references to EuiccPixel  [Bruno Martins]
* 4fa5518  XiaomiEuicc: Move to priv-app and grant required permissions  [someone5678]
* 8d932b5  XiaomiEuicc: Disable EuiccGoogle when GMS and GSF are not installed  [Peter Cai]
* f07c7eb  Introduce XiaomiEuicc  [Bruno Martins]
* 2e8fda6  hidl: biometrics: fingerprint: Set thread to high CFS priority  [Nauval Rizky]
* 2064bd0  hidl: sensors: 2.1: Add additional pick-up sensor name  [bengris32]
* 66ebac4  hidl: sensors: 1.0: Add additional pick-up sensor name  [bengris32]
* 5f470c8  vintf: Merge FPC fingerprint HIDL interfaces altogether  [Hadad]
* bdb82fc  vintf: Add legacy Goodix to FCM.  [Hadad]
* 51bb873  vintf: Add FPC 2.0 version to FCM.  [Hadad]
* 9356e8d  interfaces: Add vendor.goodix.hardware.fingerprint@1.0  [Giovanni Ricca]
* 613dfc6  interfaces: Add fingerprints extension 2.0  [Dhina17]
* 9929c6a  interfaces: Move fingerprints extension@1.0 types to types.hal  [Dhina17]
* 1f09af7  interfaces: fxtunnel: Add fxtunnel 1.0 interface  [bengris32]
* 91af720  interfaces: mfidoca: Add mfidoca 1.0 interface  [bengris32]
* 5a88d85  interfaces: mtdservice: Add mtdservice 1.3 interface  [bengris32]
* fff59ed  Drop 2.1 sensors HIDL  [ralph950412]
* e743eba  aidl: sensors: Standardize xiaomi pickup sensor  [Cosmin Tanislav]
* da9e56f  aidl: sensors: Avoid target name conflicts  [Cosmin Tanislav]
* 67564b7  aidl: sensors: Change default applicable license to Android-Apache-2.0  [Arian]
* 895ee90  aidl: sensors: Import 2.X sensors hal proxy  [ralph950412]
* b8298ba  aidl: sensors: Import aidl sensors MultiHal  [ralph950412]

#### vendor/aosp

* 0f54f67  vendor: BlackTheme: Affect more background colors  [Ido Ben-Hur]

### 09-28-2024

#### vendor/parasite/prebuilts

* 0255c5d  prebuilts: Update Gramophone  [someone5678]

### 09-27-2024

