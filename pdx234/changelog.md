# pdx234

### 05-29-2024

#### build/make

* fd072b4  make: sysprop.mk: Treat dev-keys as release-keys  [Ido Ben-Hur]
* cc91b5e  Revert "build: Always use release-keys"  [someone5678]

#### build/soong

* fd2ec63  allowlists: support inline signing for U [1/2]  [John Galt]

#### device/sony/sm8550-common

* f2a72d5  sm8550: Signing build with custom key  [someone5678]

#### external/exfatprogs

* a7b8f72  Fixing issues in METADATA file external_updater expects string in METADATA file but it couldn't find any to update the project.  [Sadaf Ebrahimi]
* d9929c2  [LSC] Add LOCAL_LICENSE_KINDS to external/exfatprogs  [Bob Badour]
* 99d0baa  ANDROID: Add metadata files  [Daniel Rosenberg]

#### hardware/sony

* ab6b411  XperiaDisplay: Add vendor.semc.hardware.display up to 2.5  [someone5678]
* d2d4481  XperiaDisplay: Make sure it's not enable by default on first boot  [lolipuru]
* 66f5b5c  XperiaDisplay: Drop livedisplay  [lolipuru]

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

#### vendor/parasite

* 85930bb  PixelPropsUtils: Spoof NestBox to Pixel 6 Pro  [someone5678]

#### vendor/parasite-signatures

* 5770db6  Update README.md  [someone5678]
* 239a085  signing: support inline signing for U [2/2]  [John Galt]
* 8f7e98f  common: BoardConfigSign: Clean-ups  [someone5678]
* f016fbc  common: config: Setup PRODUCT_OTA_PUBLIC_KEYS  [someone5678]
* d722d54  common: BoardConfigSign: Remove OTA key path  [someone5678]
* 2a3ef4f  common: Remove BUILD.bazel symlink  [someone5678]

### 05-28-2024

#### manifest

* b68491d  manifest: parasite: Track vendor/parasite-signatures  [someone5678]

#### vendor/parasite

* 0479f7d2  parasite: Include signature configs if exists  [someone5678]

#### vendor/parasite-signatures

* 035674e  Update README.md  [someone5678]
* 2dbcd7f  common: generate.sh: Check whether dir exists  [someone5678]
* a9683aa  common: Generate build files  [someone5678]
* 62a89a5  common: Cleanup and restructure  [someone5678]
* dc652fb  common: setup-buildfiles.sh: Auto setup PRODUCT_CERTIFICATE_OVERRIDES  [someone5678]
* 8642433  common: generate.sh: Cat certificate file list  [someone5678]
* 0ddf8e2  common: Add auto makefile and symlinks setup script  [someone5678]
* 87e3fdb  common: Support build signing  [someone5678]
* ce31d49  common: Make certificate directory overridable  [someone5678]
* edebad4  Update README.md  [someone5678]
* f2abbc5  Update symlinks  [someone5678]
* e28c2b3  Update README.md  [someone5678]
* 41ea361  make_key: Do not set password  [someone5678]
* 812e923  common: Adapt to current project  [someone5678]
* 4f58e61  common: bin: Add avbroot updater  [someone5678]
* 52ac047  common: Import avbroot  [someone5678]
* f6cd76b  common: Update structure  [someone5678]
* b1a6e61  Update README.md  [someone5678]
* 656d3b1  Initial commit  [AnierinB]
* c3d4605  Initial commit  [someone5678]

### 05-27-2024

#### frameworks/base

* 77d4c5b  EdgeBackGestureHandler: Change back gesture height intervals  [Anushek Prasal]

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

#### vendor/aosp

* cfda495  Revert "Implement immersive navigation to navbar no hint overlay"  [someone5678]
* f7ac5d0  Revert "Also set avb key path for recovery"  [someone5678]

#### vendor/google/dexopt_profiles

* aebb8a9  dexopt_profiles: Update  [someone5678]

#### vendor/google/pixel-framework

* b69006c  SystemUIGoogle: Do not shrink resources  [minaripenguin]

#### vendor/parasite-prebuilts

* 4d47336  parasite-prebuilts: Ship Gramophone by default  [someone5678]
* 2aa3371  parasite-prebuilts: Import Gramophone  [someone5678]
* 004b1b2  parasite-prebuilts: Prepare for import Gramophone  [someone5678]

### 05-26-2024

#### prebuilts/tools-parasite

* ee103e9  tools-parasite: Add avbroot  [someone5678]

### 05-25-2024

#### bionic

* 0c0e0e7  system_properties: Update pihook props  [someone5678]
* 314f249  system_properties: Introduce native PropImitationHooks  [Adithya R]

#### system/core

* e7442aa  init: Adapt snet spoof changes to A14 QPR2  [someone5678]
* 4927a27  init: Add ro.oem_unlock_supported  [someone5678]

#### vendor/certification

* 62f0ccf  certification: Clean-up  [someone5678]

#### vendor/parasite

* 86f32bc  PixelPropsUtils: Check whether values are empty before put into map  [someone5678]
* 04c1d65  PixelPropsUtils: Move certified props to a string resource  [Ido Ben-Hur]
* 3cb56c8  PixelPropsUtils: Clean up and update  [Joey]

