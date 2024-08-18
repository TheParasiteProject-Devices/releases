# pdx234

### 08-19-2024

#### frameworks/base

* 85de605  fixup! base: Hide ADB and developer setting enable status [1/2]  [someone5678]
* 51c6399  base: PixelPropsUtils: Move configs to rro [1/2]  [someone5678]

#### packages/apps/KProfiles

* bacbf69  KProfiles: Mark the QS tile as toggleable  [Ido Ben-Hur]

#### packages/apps/Settings

* a093495  Settings: Use MainSwitchPreference for network traffic monitor  [someone5678]

#### vendor/aosp

* 4aa819d  aconfig: Set RELEASE_ACONFIG_FLAG_DEFAULT_PERMISSION to RW  [someone5678]
* e7dfa3c  Revert "vendor: props: Enable PixelPropsUtils by default"  [someone5678]

#### vendor/certification

* fee4f0e  certification: Update  [someone5678]
* 83ab1fa  libs: Hide CertHook class  [someone5678]
* d4e877a  libs: Allow to disable CertHook  [someone5678]

#### vendor/google/gms

* 79d54a1  device_config: Disable qs tile search  [someone5678]
* 42f194a  device_config: Update launcher configs  [someone5678]
* 8fc636a  PixelPropsUtils: Move configs to rro [3/2]  [someone5678]
* fffffdc  gms: overlay: Hide Live Translate settings  [someone5678]
* dbc28e9  phenotype_flags: Hide Gemini setting in Messages  [someone5678]

#### vendor/parasite/common

* c6a091d  PixelPropsUtils: Move configs to rro [2/2]  [someone5678]
* 9f9e0bb  PixelPropsUtils: Update gms process list  [someone5678]
* 32189b1  PixelPropsUtils: Make CertHook more independent  [someone5678]

### 08-18-2024

#### vendor/google/gms

* 5da196b  [TMP] gms: Ship Tensor 2024 features for now  [someone5678]
* 01064bd  gms: Ship Tensor Pixel configs by default  [someone5678]

### 08-17-2024

#### device/sony/pdx234

* cc1465f  pdx234: SonyPDX234NfcNciRes: Add targetName and move to vendor  [Luofan Chen]

#### frameworks/base

* f67ef78  fixup! Allow to suppress notifications sound/vibration if screen is ON [1/2]  [Pranav Vashi]
* 4dc2891  base: Add PhenotypeFlagsUtils [2/2]  [someone5678]

#### vendor/google/gms

* 8f2e31e  gms: Add PhenotypeFlagsUtils [3/2]  [someone5678]

#### vendor/parasite/common

* 3f1a186  libs: Add PhenotypeFlagsUtils [1/2]  [someone5678]

### 08-16-2024

#### frameworks/base

* 9f97027  SystemUI: Reduce keyguard indication text padding  [minaripenguin]
* 42a2975  SystemUI: Don't enforce Island notif on landscape  [someone5678]
* 8c2168c  SystemUI: Show island notification on landscape  [minaripenguin]
* a24ba6a  Island: Recycle icon bitmap to avoid memory leak  [minaripenguin]

#### packages/apps/GameSpace

* 174fd13  GameSpace: Show correct default settings  [Dhina17]
* 0a0532f  GameSpace: Don't add floating action if game closed too quickly  [Dhina17]

#### vendor/google/gms

* 6415eb2  gms: Update comment of proprietary-files*.txt  [someone5678]
* aa8fd35  gms: Add symlink to blob  [someone5678]
* 003651f  Update README.md  [someone5678]
* ab55742  gms: Import makefiles from common blobs  [someone5678]
* 16b94e6  Update README.md  [someone5678]
* 75714a0  gms: vendorsetup.sh: Remove previously merged apks before merge  [someone5678]
* b18c96c  gms: vendorsetup.sh: Guard it  [someone5678]
* 04178e8  gms: Split blobs going over 100MB  [Omkar Chandorkar]
* 67a1b3d  gms: Kill git lfs  [someone5678]
* 5a73587  gms: Add symlink to blob repo  [someone5678]
* 0978876  pixel-style: Add new setupwizard props from caiman  [Joey Huab]

#### vendor/parasite/common

* 32d26bc  PixelPropsUtils: Spoof Weather to recent Pixel  [someone5678]
* 6946bac  PixelPropsUtils: Move to Pixel 9 Pro  [someone5678]

### 08-15-2024

#### manifest

* 90fea1f  manifest: parasite: Track gms-common-proprietary  [someone5678]

#### vendor/certification

* 773c7cb  certification: Update  [someone5678]

#### vendor/google/gms

* ea12b14  gms: Allow to ship dse choice screen feature config via flag  [someone5678]
* 662f0da  gms: overlay: Turn it into static RRO  [someone5678]
* 8cebbbf  gms: Matching AccessibilityMenum overlay name to other overlays  [someone5678]
* 46a477f  gms: Add DreamlinerOverlay  [someone5678]
* 1cb8cab  pixel-style: Add rro to enable clear calling on supported devices  [AnierinB]
* 59f6071  gms: Remove now-auto extracted PixelSfpsOverlay  [someone5678]
* 48f5684  gms: Import PixelSfpsOverlay  [someone5678]
* 3b28486  gms: Import missing preinstalled packages config  [someone5678]
* 87b807f  fixup! gms: Add support for DSE search engine choice screen and EEA device features  [someone5678]
* cf97e62  gms: Import UdfpsOverlay  [someone5678]
* 8be5ffb  gms: Disable ro.storage_manager.enabled  [someone5678]
* 08ab2a3  gms: Add support for DSE search engine choice screen and EEA device features  [someone5678]
* 22e761f  gms: Move ThemeIcons under vendor/google  [someone5678]
* 5c567b2  gms: Enable app cloning building blocks config  [someone5678]
* daf1d74  fixup! gms: Initial configs from previous repo  [someone5678]
* 4ee8aee  gms: Initial configs from previous repo  [someone5678]
* 08f2e51  halcyonUI: overlay: Disable Google Dialer Call recording TTS  [HeroBuxx]
* b954596  DeviceConfig: Set Google photos as cloud picker provider  [aswin7469]
* 9b967aa  Revert "dont hurt pokemon"  [someone5678]
* ff85fcc  Revert "DeviceConfig: Enable Cinematic wallpaper effects"  [someone5678]
* 2058562  gms: Import default-permissions_pixelsupport.xml  [someone5678]
* c0f1e3f  gms: vendorsetuh.sh: Guard it  [someone5678]
* 0e9936f  gms: Extract dark bootanimation directly from firmware  [someone5678]
* afaae6f  gms: Import missing permission for Search Selector  [someone5678]
* 2d13c0a  gms: Update gmscore makefile  [someone5678]
* 13f43e2  fixup! gms: Update  [someone5678]
* 3739e05  gms: Prepare for update  [someone5678]
* 8ad3370  gms: vendor/pixel-framework can be unexisted  [someone5678]
* a59dcb8  gms: Remove SystemUIClocks-Handwritten  [someone5678]
* 5358bcd  gms: Prepare for update  [someone5678]
* 72fd2fd  DeviceConfig: Enable Cinematic wallpaper effects  [aswin7469]
* 8ad79e3  config: Allow SetupWizard Rotation in Tablets  [citrine]
* 823a6d8  gms: props: Enable assist gesture training  [someone5678]
* 95a8a3c  gms: Move dex preopt configs for PixelFW  [someone5678]
* e7bc711  gms: props: Set SetupWizard theme to glif_v4  [someone5678]
* db15ed6  dont hurt pokemon  [aswin7469]
* 46303e2  gms: Update gms guard  [someone5678]
* 276a9d3  gms: Clean-up PRODUCT_GMS_CLIENTID_BASE  [someone5678]
* 5a26fe8  gms: Exclude config_defaultModuleMetadataProvider  [someone5678]
* 47d07f7  device_config/overlay: Force enable Now Playing for all  [minaripenguin]
* 53bca25  device_config: Enable Cloud Media provider  [aswin7469]
* 0744cb9  gms: overlay: Correct target package and move some overlays to non-RRO  [someone5678]
* f01065d  gms: Add support for excludes gms for testing purposes  [someone5678]
* 2450216  gms: Add more blobs  [someone5678]
* 671dfcd  overlay: Disable a couple more OTA upgrade components  [Alexander Koskovich]
* 170f0f7  overlay: Disable OtaUpdateActivity component  [Alexander Koskovich]
* 8854042  device_config: Update some values  [aswin7469]
* 93710c0  device_config: Correct value  [someone5678]
* bc98151  gms: overlay: Add BtHelper to location extra package  [someone5678]
* c8058f7  device_config: Refactor and update  [jhenrique09]
* cd3f611  device_config: Enable Circle to Search feature  [Joey Huab]
* aa4a71a  gms: Ship Pixel framework permissions  [someone5678]
* 9d79638  gms: Signing TelephonyGoogle with platform key  [someone5678]
* 4b35919  gsm: Add vendorsetup.sh  [someone5678]
* 7924956  gms: flags: Enable various flags  [someone5678]
* b8cdcc2  gms: overlay: Move all frameworks resources overlay into RRO  [someone5678]
* 70f1d3c  gms: Exclude config_repairModeSupported  [someone5678]
* 68d7017  gms: Move related overlays into LineageOS SDK resources  [someone5678]
* 8afe66d  gms: Move TARGET_INCLUDE_PIXEL_FRAMEWORKS to pixel-fw repo  [someone5678]
* e188b78  overlays: Expose aspect ratio settings  [minaripenguin]
* bf5bcba  Revert "gms: Import Repair Mode"  [someone5678]
* ee941b4  gms: Import Repair Mode  [someone5678]
* f4502ac  gms: Import more blobs  [someone5678]
* 3e8b056  gms: Update  [someone5678]
* e1a2ed7  overlay/SimpleDeviceConfig: do not override max cached processes  [Richard Chang]
* 52dbb8b  overlay: Define launcher_overlayable_package  [jhenrique09]
* 9ed7119  gms: Remove ModuleMetadata section from blob list  [someone5678]
* b2cf374  SystemUIClocks: Import SystemUIClocks-Handwritten from barbet_beta-user-14-UPB4.230623.005  [Sarthak Roy]
* b24d929  device_config: Enable Adaptive Sound  [someone5678]
* ea18f84  Revert "[TMP] Pin AOSP SystemUI for now"  [someone5678]

#### vendor/google/gms-common-proprietary

* d0aa49d  gms-common: Initial import  [someone5678]
* f8b9d14  gms-common: Add .gitignore  [someone5678]
* 929cb3d  Initial commit  [someone5678]

#### vendor/parasite/common

* 9c2655e  PixelPropsUtils: Spoof update and search to recent pixel  [someone5678]

