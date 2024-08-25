# pdx234

### 08-26-2024

#### frameworks/base

* 99509c0  Spoof a valid certificate chain for hardware attestations [1/2]  [chiteroman]
* b0021a2  services: Add NPE check for updating system app from play store  [Pranav Vashi]
* 60cca2b  base: PixelPropsUtils: Add Extra  [someone5678]

#### hardware/xiaomi

* 7b1ebce  IFAAService: Add null checks  [Sebastiano Barezzi]
* 8666282  IFAAService: Include all AIDL files  [Sebastiano Barezzi]
* c18fc2f  IFAAService: Add missing license headers  [Sebastiano Barezzi]
* 280adfe  IFAAService: Don't use fqname to reference service class  [Sebastiano Barezzi]
* a3509b8  IFAAService: Drop compile SDK and version code from manifest  [Sebastiano Barezzi]
* 41cf1a7  IFAAService: Reformat manifest  [Sebastiano Barezzi]
* 069649d  vintf: Add PixelWorks Iris interfaces to FCM  [Andrey Sprynga]
* 539bc37  vintf: Add focaltech and silead FP Interfaces to FCM  [HeroBuxx]

#### packages/modules/adb

* 43ed9b4  Squashed import of adb root patches  [LuK1337]

#### vendor/certification

* 190ceca4  Spoof a valid certificate chain for hardware attestations [2/2]  [chiteroman]
* 05ffcc6  certification: libs: Clean-up before changes  [someone5678]

#### vendor/google/gms

* 0b93e97  gms: configs: Exempt Google Dialer from location indicator  [someone5678]
* b8ea073  gms: configs: Disable SystemUpdateV2Activity  [someone5678]
* e59b59f  overlay: Add GameSpace to notification listener access  [minaripenguin]
* 7258240  gms: PixelConfigOverlayCustom: Update default notif access packages  [someone5678]
* 8952d53  Revert "gms: configs: Remove Live Wallpaper module unblocking"  [someone5678]
* 753413b  gms: configs: Update process lists  [someone5678]
* 2a56ca7  gms: configs: Add and update configs for circle to search  [someone5678]

#### vendor/google/gms-common-proprietary

* b476606  gms: Use NexusLauncherRelease from P8 Pro for now  [someone5678]

#### vendor/google/mainline_modules

* 12e1ef9  mainline_modules: Directly extract google-install-constraints-package-allowlist  [someone5678]
* 559306c  mainline_modules: overlays: Update priority to 1  [someone5678]
* 1572cd4  mainline_modules: overlays: Disable gms ota components  [someone5678]

#### vendor/parasite/common

* e7f42fd  PixelPropsUtils: Add Extra  [someone5678]

### 08-25-2024

#### device/lineage/sepolicy

* 2275b98  common: add legacy vibrator AIDL  [Han Sol Jin]

#### frameworks/base

* bd6a995  SystemUI: Update track title and artist on metadata change  [alphime]

#### vendor/google/gms

* 414858a  gms: configs: It's Bugle time!  [someone5678]

### 08-24-2024

#### frameworks/base

* c3a32ce  SystemUI: Fix Island loop if suddenly close  [alphi]

#### hardware/sony

* a7c89cc  sony: sepolicy: Address AIDL NFC hal  [someone5678]

#### vendor/google/gms

* 4db25a8  Update README.md  [someone5678]
* ba0479d  gms: configs: Remove Live Wallpaper module unblocking  [someone5678]
* a88fae7  gms: configs: Unspoof AICore  [someone5678]
* 4f41ada  gms: Don't include 2024 Tensor apps  [someone5678]
* 10b6ecf  gms: configs: Add more apps to live translate blocklist  [someone5678]
* f62d2b7  gms: configs: Disable Live Translate  [someone5678]
* c0c04a0  gms: Import SettingsGoogleFutureFaceEnroll  [someone5678]
* 537863a  gms: config: Update  [someone5678]
* a7f09ca  gms: Exclude FIR proximity sensors support by default  [someone5678]
* fb61456  gms: Add monet bootanimation switch [3/2]  [someone5678]
* 76d152e  gms: Update bootanimation modification  [someone5678]
* f7ec420  gms: Import missing permissions  [someone5678]
* dbcf9a5  gms: skip_preprocessed_apk_checks for Meet  [someone5678]
* 44ef80e  gms: Update optional libraries  [someone5678]
* 1f011a4  gms: Remove leftover 2024 experience  [someone5678]
* 46b6e2f  gms: overlays: Expose 2024 experience to PixelAIPrebuilt  [someone5678]
* 197afaf  gms: Split more apps  [someone5678]

#### vendor/google/gms-common-proprietary

* c687a00  gms: Import SettingsGoogleFutureFaceEnroll  [someone5678]
* d6e8ea9  gms: Import missing firproximity.xml  [someone5678]

### 08-23-2024

#### device/lineage/sepolicy

* 26d1da8  sepolicy: label default powershare implementation  [Cosmin Tanislav]

#### device/qcom/sepolicy_vndr/sm8550

* 52e9556  sepolicy: add missing sepolicy rules for kalama  [someone5678]
* 12aff57  sepolicy: add sys_module capability for hal_wifi_default  [Hu Wang]
* 94ca800  sepolicy: Label vendor.qti.ims.factoryaidlservice.IImsFactory  [Michael Bestas]
* a387193  sepolicy: Move some AIDL rules to common policy  [Michael Bestas]

#### device/sony/pdx234

* 485a1f4  pdx234: Update  [someone5678]

#### device/sony/sm8550-common

* 414f74b  sm8550-common: Check media_codecs xml from XQ-DQ72_Customized_HK_67.1.A.2.270  [Luofan Chen]
* 6467ae8  sm8550-common: usb_compositions: Change vid and pid to sony  [Luofan Chen]

#### frameworks/base

* 4742623  base: cmds: Add monet bootanimation switch [1/2]  [someone5678]

#### hardware/lineage/interfaces

* bd66d5b  powershare: add default implementation  [Cosmin Tanislav]

#### hardware/sony

* f228bac  Disable 32 bit variants of audio libraries for 64 bit audio targets  [Arian]

#### manifest

* 5cc3f1c  manifest: lineage: Track device/qcom/sepolicy_vndr/sm8550  [someone5678]

#### packages/apps/GameSpace

* c1358f5  GameSpace: Fix the limit of only four widget apps  [YiQiu]
* 8a686a9   GameSpace: Introduce Quick Start app feature  [YiQiu]

#### packages/apps/Settings

* 378ba74  Settings: Add monet bootanimation switch [2/2]  [someone5678]

#### tools/extract-utils

* ed53b67  extract_utils: Ignore extra flags during sort  [LuK1337]

#### vendor/aosp

* 1eb7a3c  soong: add powershare configs  [Cosmin Tanislav]

#### vendor/google/gms

* 08f5b6e  gms: Update  [someone5678]

#### vendor/google/gms-common-proprietary

* 2cdc32a  gms: Update bootanimation  [someone5678]
* 1646ded  gms: Import missing permissions  [someone5678]
* 8bd2d96  gms: Update  [someone5678]
* 8c8d1e0  gms: Add SystemUIClocks-Handwritten  [someone5678]
* 5e91c16  gms: Remove SystemUIClocks-Handwritten  [someone5678]

#### vendor/google/pixel-additional

* 88911cd  pixel-additional: Update  [someone5678]
* b666d75  pixel-additional: Prepare for source change  [someone5678]

#### vendor/google/pixel-framework

* d844596  pixel-framework: Update  [someone5678]

#### vendor/parasite/common

* e147fd1  GamesPropsUtils: Spoof Brawl Stars to Mi 11T Pro  [Joey Huab]
* 665b609  GamesPropsUtils: Update model for call of duty to Lenovo Y700  [Pranav Vashi]

#### vendor/sony/pdx234

* 5b316a4  pdx234: Update  [someone5678]

#### vendor/sony/sm8550-common

* 47258be  sm8550-common: Update  [someone5678]

### 08-22-2024

#### hardware/qcom-caf/sm8550/audio/pal

* 2e928e9  Disable 32 bit variants of audio libraries for 64 bit audio targets  [Arian]

#### hardware/qcom-caf/sm8550/audio/primary-hal

* e0fe270  Disable 32 bit variants of audio libraries for 64 bit audio targets  [Arian]

#### packages/apps/Aperture

* a7f50c1  Aperture: Fix front camera intent preview mirroring  [Tommy Webb]
* 5f6aa26  Aperture: Update CameraX to 1.4.0-rc01  [LuK1337]

#### vendor/google/gms

* f772674  gms: overlay: custom_features: Expose Tensor feature to dialer  [someone5678]

