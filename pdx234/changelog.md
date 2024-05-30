# pdx234

### 05-30-2024

#### device/sony/extra

* 914bc91  extra: Import gaming components  [someone5678]
* 0debff2  extra: Unpin all modified apks  [someone5678]

#### device/sony/sm8550-common

* 92d88d7  sm8550-common: vibrator: Rename to avoid conflicts  [someone5678]
* feb6aed  sm8550-common: Update powerhint.json nodes to kalama  [someone5678]
* 6d37bfa  sm8550-common: Use HintManager for HWUI  [Vaisakh Murali]
* f8e087f  sm8550-common: rootdir: Kill WALT CPU boosting  [Sugakesshaa]
* 40b23c8  sm8550-common: powerhint: Drop CPU freqs boosting on INTERACTION  [bheatleyyy]
* 7a9275a  sm8550-common: powerhint: Follow taro's CPU freqs for little cluster  [bheatleyyy]
* 593c932  sm8550-common: rootdir: Do not allow foreground tasks to run on CPU7  [Jake Weinstein]
* 0e6df47  sm8550-common: rootdir: Move background cpuset to CPU0-1  [Jake Weinstein]
* 5350224  sm8550-common: rootdir: Set restricted cpuset to the same CPUs as system-background  [Jake Weinstein]
* 0b3b3e0  sm8550-common: sepolicy: Allow powerhal write to /proc  [Sugakesshaa]
* 44e8e6a  sm8550-common: rootdir: Enable powerhint parsing after boot completion  [Bruno Martins]
* 41ae819  sm8550-common: powerhint: Adapt and tune for SM8475 (cape)  [bheatleyyy]
* cc79f9b  sm8550-common: Import powerhint.json from lahaina  [bheatleyyy]
* 9b1e682  sm8550-common: Provide a static lib for power mode extension  [Arian]
* 29aeaed  sm8550-common: Migrate to common libqti-perfd-client and power-libperfmgr  [Bruno Martins]
* 32bf502  sm8550-common: Remove QTI perfd  [Wei Wang]
* e062953  sm8550-common: Move init.qcom.post_boot.sh here  [someone5678]
* 1947676  sm8550: Signing build with custom key  [someone5678]

#### frameworks/base

* efcc58c  JobSchedulerService:fix arrayIndexOutOfBoundsException to aviod systemServer crash.  [lijilou]
* 43e374b  Vibrator: Force to return a non-zero duration  [flakeforever]
* 808a05d  Reapply "Make dun APNs as read-only by default."  [ShevT]
* 37631c7  Fix NPE when traversing viewgroup display list  [minaripenguin]
* 3064955  BatteryStatsImpl: Guard against OOB  [Ido Ben-Hur]
* 7a691c9  core: Broadcast intent when display power state changes  [Adithya R]

#### hardware/qcom-caf/common

* 29e63ca  libqti-perfd-client: Add more dummy methods  [someone5678]
* 40a7e32  qcom: Allow a device to manually override which HALs it wants to use  [Akhil Narang]

#### manifest

* afb908d  [TMP] manifest: parasite: Track hardware/qcom-caf/common diff --git a/snippets/lineage-caf.xml b/snippets/lineage-caf.xml index 378758192..56136b36c 100644  [someone5678]

#### packages/apps/Settings

* 0ff16ee  DataProcessor: Do not skip and replace screen on component with screen on time  [minaripenguin]
* 4d1c781  Settings: add animation to dark mode preference  [minaripenguin]
* bde2d9f  NightDisplay Settings: Use List Preference for NightLight settings  [Akash]
* f8a80e6  DarkMode Settings: Use List Preference rather ugly Drop Down  [Pranav Vashi]

#### vendor/google/gms

* 92f42be  device_config: Update Live Caption model  [aswin7469]

#### vendor/parasite

* 93957a5  PixelPropsUtils: Spoof Gboard and Ai Wallpapers to husky  [Joey]

#### vendor/parasite-signatures

* 0a1f334  common: generate.sh: Allow to skip prompt  [someone5678]
* c1b11a9  common: BoardConfigSign: Do not generify avb algorithm  [someone5678]
* ef0c61b  common: Run setup-buildfiles.sh  [someone5678]
* 2eb3bcc  common: Regularly generate releasekey  [someone5678]
* 5c13aea  Update README.md  [someone5678]
* f60a47f  common: Run setup-buildfiles.sh  [someone5678]
* eef4220  keys: Initialize  [AnierinB]
* ec1dccb  common: Run setup-buildfiles.sh  [someone5678]
* 47bedcd  common: setup-buildfiles.sh: Create symlink for avb_pkmd.bin  [someone5678]
* f9f4522  common: generate.sh: Generate avb_pkmd.bin  [someone5678]
* cab39a3  common: Import prebuilt avbtool  [someone5678]
* f3dd844  common: generate.sh: Remove rsa option  [someone5678]
* e659883  common: make_key: Only generates rsa key  [someone5678]
* 1fbb5d5  common: Generate build files  [someone5678]
* 784ebc8  keys: Update lists and force RSA 4096 for APEX  [AnierinB]
* 0f5a361  Update README.md  [someone5678]
* e756e81  signing: support inline signing for U [2/2]  [John Galt]
* 023f590  common: BoardConfigSign: Clean-ups  [someone5678]
* e97768d  common: config: Setup PRODUCT_OTA_PUBLIC_KEYS  [someone5678]
* 30482a3  common: BoardConfigSign: Remove OTA key path  [someone5678]
* ca73b6b  common: Remove BUILD.bazel symlink  [someone5678]
* 25a5093  Update README.md  [someone5678]
* 9958ecf  common: generate.sh: Check whether dir exists  [someone5678]
* e63aa07  common: Generate build files  [someone5678]
* cb49bfc  common: Cleanup and restructure  [someone5678]
* 78d16b2  common: setup-buildfiles.sh: Auto setup PRODUCT_CERTIFICATE_OVERRIDES  [someone5678]
* eec35f4  common: generate.sh: Cat certificate file list  [someone5678]
* 67e5e75  common: Add auto makefile and symlinks setup script  [someone5678]
* 0346f69  common: Support build signing  [someone5678]
* 7b7d46f  common: Make certificate directory overridable  [someone5678]
* e34fe93  Update README.md  [someone5678]
* 04cb9e3  Update symlinks  [someone5678]
* df35089  Update README.md  [someone5678]
* b4ccfcb  make_key: Do not set password  [someone5678]
* ed6ffc2  common: Adapt to current project  [someone5678]

#### vendor/sony/extra

* 5394f0f  extra: custom: Disable uses library checks  [someone5678]
* 8de0a7c  extra: Import gaming components  [someone5678]
* 2fef11c  extra: custom: ThreeSixtyRASystem: Make it usable  [someone5678]
* 4aafdc9  extra: custom: SoundEnhancement: Show under audio settings  [someone5678]
* d0519b3  extra: custom: Reapply previous cusomisations  [someone5678]
* 4a6d48d  extra: custom: Inital decomp  [someone5678]
* 146c769  extra: Inital custom SoundEnhancement & ThreeSixtyRASystem  [someone5678]
* e96c189  extra: Unpin all modified apks  [someone5678]

### 05-29-2024

#### frameworks/base

* 07b6413  Allow signature spoofing for microG Companion/Services  [LuK1337]
* 4501da7  SystemUI: Add FingerprintInteractiveToAuthProvider implementation  [Adithya R]
* 563e9e7  SettingsLib: Use framework resource for headline font  [Adithya R]
* 1420fcd  SystemUI: Fix lottie malformed json crashes  [minaripenguin]

#### hardware/sony

* ab6b411  XperiaDisplay: Add vendor.semc.hardware.display up to 2.5  [someone5678]
* d2d4481  XperiaDisplay: Make sure it's not enable by default on first boot  [lolipuru]
* 66f5b5c  XperiaDisplay: Drop livedisplay  [lolipuru]

#### vendor/aosp

* 8f6ab31  soong: Add power libperfmgr extension config  [Arian]

#### vendor/google/pixel-additional

* a2371ee  TurboAdapter_NoBatt: Throws remote exception  [someone5678]

#### vendor/sony/extra

* 9fce5c0  extra: custom: daxService: Update tile name  [someone5678]

#### vendor/sony/sm8550-common

* 43e5b7b  sm8550-common: Remove QTI perfd  [someone5678]
* 4b4030b  sm8550-common: Move init.qcom.post_boot.sh to device tree  [someone5678]

### 05-28-2024

#### build/make

* fd072b4  make: sysprop.mk: Treat dev-keys as release-keys  [Ido Ben-Hur]
* cc91b5e  Revert "build: Always use release-keys"  [someone5678]

#### build/soong

* fd2ec63  allowlists: support inline signing for U [1/2]  [John Galt]

#### external/exfatprogs

* a7b8f72  Fixing issues in METADATA file external_updater expects string in METADATA file but it couldn't find any to update the project.  [Sadaf Ebrahimi]
* d9929c2  [LSC] Add LOCAL_LICENSE_KINDS to external/exfatprogs  [Bob Badour]
* 99d0baa  ANDROID: Add metadata files  [Daniel Rosenberg]

#### vendor/aosp

* 89ec324  vendor: tools: changelog: Use bash  [someone5678]

#### vendor/google/gms

* 1925d8b  gms: overlay: Properly override SettingsLib's headline font  [someone5678]

#### vendor/google/mainline_modules

* 3eb5d72  mainline_modules: Enable virtualization support by default  [someone5678]
* 3704a32  Enable virtualization support  [Oliver Scott]

#### vendor/google/pixel-framework

* b35f1b1  Revert "SettingsGoogle: Apply R8 optimization based on SystemUI"  [someone5678]
* 77fbe2d  SystemUIGoogle: Remove R8 optimizations  [minaripenguin]

### 05-27-2024

#### device/qcom/sepolicy_vndr/legacy-um

* 326c4a9  msmnile: Label multiimgqti_[ab]  [Sebastiano Barezzi]

#### lineage/scripts

* 1a0a5e8  build-webview: Update default webview to 125.0.6422.113  [Kevin F. Haggerty]

#### manifest

* b68491d  manifest: parasite: Track vendor/parasite-signatures  [someone5678]

#### vendor/parasite

* 0479f7d2  parasite: Include signature configs if exists  [someone5678]

#### vendor/parasite-prebuilts

* 4d47336  parasite-prebuilts: Ship Gramophone by default  [someone5678]

#### vendor/parasite-signatures

* f6cd76b  common: Update structure  [someone5678]
* b1a6e61  Update README.md  [someone5678]
* 656d3b1  Initial commit  [AnierinB]
* c3d4605  Initial commit  [someone5678]

### 05-26-2024

#### frameworks/base

* 77d4c5b  EdgeBackGestureHandler: Change back gesture height intervals  [Anushek Prasal]

#### hardware/qcom-caf/thermal

* a1bb7a3  thermal-hal: Enable thermal_hal support for yupik variants  [Gopala Krishna Nuthaki]

#### kernel/sony/sm8550

* 31c91eb  configs: pdx234: Build KProfiles as LKM  [someone5678]
* d6be0c4  drivers: misc: Import KernelSU  [someone5678]
* 0913acc  configs: pdx234: Configure KProfiles  [Mohammad Sayful Islam]
* f4902f2  configs: pdx234: Enable Kprofiles  [someone5678]
* b4e2974  drivers: misc: Import Kprofiles  [someone5678]
* db4db4b  drivers: qcom: Make CONFIG_QCOM_SOC_SLEEP_STATS_ON_SYSFS depend on DEBUGFS  [Luofan Chen]
* 64c984f  Makefile.lib: Lower kernel gzip compression to fastest  [Angelo G. Del Regno]
* 8ee49ff  configs: sony: Enable ZRAM writeback  [Luofan Chen]
* 38e253a  arch: configs: sony: Disable CONFIG_QCOM_SOC_SLEEP_STATS_ON_SYSFS  [Luofan Chen]
* 192528d  configs: Move sony specific config to its fragment  [Luofan Chen]
* e30cef8  sony: config: Use 1M for kernel log  [Juhyung Park]
* c04369b1  sony: config: Disable most of the debugging configs  [Pranav Vashi]
* c9f30d8  sony: config: Disable wcd-usbss  [Bruno Martins]
* fa6ed72  sony: config: Unset all configs related with crow chipset  [Bruno Martins]
* 4cafe85  power: Import wakeup_irq_debug driver  [Luofan Chen]
* cec89022  ARM64: dts: vendor: Add symlink to sm8550-devicetrees  [Bruno Martins]
* fc60b89  et6xx: Align implementation in sm8550  [Luofan Chen]
* 77a4edd  et6xx: Remove reference to hardware_info  [Luofan Chen]
* 35875f9  drivers: sony: Import et6xx driver from 68.0.A.0.768  [Luofan Chen]
* 0393c84  drivers: Import sony drivers to build inline  [Luofan Chen]
* 353da8f  tools/resolve_btfids: Skip unresolved symbol warning for empty BTF sets  [Kumar Kartikeya Dwivedi]
* 53ec986  minimal sony changes  [Luofan Chen]

#### lineage/scripts

* f15373e  device-deps-regenerator: Ignore sm8475-devicetrees  [LuK1337]

#### prebuilts/tools-parasite

* ee103e9  tools-parasite: Add avbroot  [someone5678]

#### vendor/aosp

* cfda495  Revert "Implement immersive navigation to navbar no hint overlay"  [someone5678]
* f7ac5d0  Revert "Also set avb key path for recovery"  [someone5678]

#### vendor/google/dexopt_profiles

* aebb8a9  dexopt_profiles: Update  [someone5678]

#### vendor/google/pixel-framework

* b69006c  SystemUIGoogle: Do not shrink resources  [minaripenguin]

#### vendor/parasite-prebuilts

* 2aa3371  parasite-prebuilts: Import Gramophone  [someone5678]
* 004b1b2  parasite-prebuilts: Prepare for import Gramophone  [someone5678]

