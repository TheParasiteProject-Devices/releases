# pdx234

### 09-08-2024

#### frameworks/base

* 478f524  IslandView: Fix dismissal and cleanup resources when not needed  [minaripenguin]
* ad4888a  services: Implement exit app animation boost  [minaripenguin]
* ad47270  services: Implement activity boost optimization  [minaripenguin]
* 27c790a  services: Implement transition boosting  [minaripenguin]
* c753028  services: Implement scroll gesture boosting  [minaripenguin37]
* 45f79ed  Revert "[SQUASH] services: Boost gesture flings"  [someone5678]

### 09-07-2024

#### vendor/google/gms

* 45c92e9  gms: configs: Expose gemini in messages setting  [someone5678]

### 09-06-2024

#### vendor/google/dexopt_profiles

* cb9f742  dexopt_profiles: Update  [someone5678]

### 09-05-2024

#### build/make

* 19823f5  Merge tag 'android-14.0.0_r71'  [someone5678]

#### frameworks/av

* 8ef6306  Merge tag 'android-14.0.0_r71'  [someone5678]

#### frameworks/base

* 7d66ba0  Merge tag 'android-14.0.0_r71'  [someone5678]

#### manifest

* 4267d79  Merge tag 'android-14.0.0_r71'  [someone5678]
* fdfe2f1  Manifest for Android 14.0.0 Release 71  [The Android Open Source Project]
* e9e2a15  Manifest for Android 14.0.0 Release 70  [The Android Open Source Project]
* f38ade4  Manifest for Android 14.0.0 Release 69  [The Android Open Source Project]
* c666ee5  Manifest for Android 14.0.0 Release 68  [The Android Open Source Project]
* 16d4749  Manifest for Android 14.0.0 Release 67  [The Android Open Source Project]

#### packages/apps/Settings

* 9de75a2  Merge tag 'android-14.0.0_r71'  [someone5678]

#### packages/services/Telecomm

* d5b8189  Merge tag 'android-14.0.0_r71'  [someone5678]

#### vendor/google/dexopt_profiles

* fd43283  dexopt_profiles: Update  [someone5678]

#### vendor/google/gms

* 51bd7a1  gms: Update  [someone5678]
* c75500e  gms: Remove SystemUIClocks-Handwritten  [someone5678]
* 66198ee  gms: Prepare to switch to komodo  [someone5678]

#### vendor/google/gms-common-proprietary

* 350215c  gms: Use NexusLauncherRelease from P8 Pro for now  [someone5678]
* 1f49f1d  gms: Update  [someone5678]

#### vendor/google/mainline_modules

* 11a47b8  mainline_modules: Update  [someone5678]

#### vendor/google/pixel-additional

* b189332  pixel-additional: Update  [someone5678]

### 09-04-2024

#### bootable/recovery

* 5947f64  [SQUASH] recovery: Integrate prebuilt module loading into AOSP Recovery  [glikched]
* 816b875  recovery: Always consider builds to be debuggable  [Pranav Vashi]

#### build/soong

* 8b8c0a9  soong: cc: allow -u linker flag  [nift4]

#### device/parasite/sepolicy

* 11f0185  sepolicy: Allow shell to run dmesg on recovery only  [someone5678]
* 41a9c7b  sepolicy: Import twrp sepolicy  [someone5678]
* eab2ea9  sepolicy: Allow recovery to set ro.adb.secure.recovery and shell prop  [someone5678]

#### device/qcom/sepolicy_vndr/sm8550

* 806cb93  sepolicy_vndr: Allow init/vendor_init to write proc firmware config  [Luofan Chen]
* cd38198  sepolicy_vndr: Label proc firmware config node  [Luofan Chen]

#### device/sony/sm8550-common

* 76daae0  sm8550-common: Update symlink name  [someone5678]

#### frameworks/base

* 0c9f3c2  base: PowerOffAlarmService: Avoid NullPointerException  [someone5678]
* 5020ec2  Island: Remove notification when swiped dismiss  [minaripenguin]
* 26f0a13  Island: Fix focused top-app detection  [minaripenguin]
* f03c6c0  PinnerService: Try to pin SystemUIGoogle if SystemUI fails  [AnierinB]

#### hardware/google/camera

* 8cd170f  camera: Guard with soong namespace  [Michael Bestas]

#### hardware/qcom-caf/common

* d67755a  libqti-perfd-client: Do not log if any of value is NULL  [someone5678]
* b054148  libqti-perfd-client: Define dummy perf_hint_renew method  [chaptsand]
* b6fe5c2  common: Add nfc 1.2  [Landry GAIFFE]
* bbadf2e  libqti-perfd-client: Correct report values and types of methods  [someone5678]
* 31572c1  common: Add support for pineapple boards  [Venkat Yadlapati]
* 6c4fa01  qcom: Allow a device to manually override which HALs it wants to use  [Akhil Narang]

#### manifest

* 6168cb7  manifest: Switch to our fork of hardware/google/camera  [Michael Bestas]
* f02f472  Revert "manifest: lineage: Track device/qcom/sepolicy_vndr/sm8550"  [someone5678]

#### system/sepolicy

* 02d18f6  sepolicy: Allow shell to access dmesg on recovery only  [someone5678]
* ed7243e  adbd: Allow adb root on user builds  [Alexander Winkowski]
* 6790c93  Allow permissive backuptool domain on user builds  [Alexander Winkowski]
* 45264cb  Allow system server to access tmpfs files  [minaripenguin]
* 89c2adf  Allow ueventd to read apexd property  [Suchang Woo]
* 7dd4e5b  sepolicy: Allow permissive in recovery on user builds  [Pranav Vashi]
* d5d7c10  sepolicy: Also allow vendor_init to get/set bluetooth_prop  [someone5678]
* 182747a  sepolicy: Allow hal_audio_default to get/set bluetooth_prop for a2dp offloading.  [someone5678]
* 633cc3f  Resolve neverallow in retrofit devices  [Michael Bestas]
* d6891c6  Allow ignore neverallows in user builds  [Zhenxiang]
* b934153  sepolicy: allow fastbootd to operate devpts  [Randall Huang]
* 6c8a4d3  sepolicy: allow system app to access sysfs_leds  [Marko Man]

#### vendor/aosp

* 556e18c  apn: Set correct apn for `Grameenphone`  [hipexscape]

#### vendor/sony/sm8550-common

* a8c0d4b  sm8550-common: Update symlink name  [someone5678]
* ab4e802  sm8550-common: Update  [someone5678]

