# pdx234

### 09-04-2024

#### bootable/recovery

* 816b875  recovery: Always consider builds to be debuggable  [Pranav Vashi]

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

#### hardware/qcom-caf/common

* d67755a  libqti-perfd-client: Do not log if any of value is NULL  [someone5678]
* b054148  libqti-perfd-client: Define dummy perf_hint_renew method  [chaptsand]
* b6fe5c2  common: Add nfc 1.2  [Landry GAIFFE]
* bbadf2e  libqti-perfd-client: Correct report values and types of methods  [someone5678]
* 31572c1  common: Add support for pineapple boards  [Venkat Yadlapati]
* 6c4fa01  qcom: Allow a device to manually override which HALs it wants to use  [Akhil Narang]

#### manifest

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

#### vendor/sony/sm8550-common

* a8c0d4b  sm8550-common: Update symlink name  [someone5678]
* ab4e802  sm8550-common: Update  [someone5678]

### 09-03-2024

#### build/soong

* ba58efc  soong: Increase heap size to 8GB for R8 and D8  [someone5678]

#### kernel/sony/sm8550

* 33b88eb  configs: sony: Enable Kallsyms  [someone5678]
* 06fa5fc  drivers: qcom: Make CONFIG_QCOM_SOC_SLEEP_STATS_ON_SYSFS depend on DEBUGFS  [Luofan Chen]
* 544834a  Makefile.lib: Lower kernel gzip compression to fastest  [Angelo G. Del Regno]
* daa911b  configs: sony: Enable ZRAM writeback  [Luofan Chen]
* 354c0af0  arch: configs: sony: Disable CONFIG_QCOM_SOC_SLEEP_STATS_ON_SYSFS  [Luofan Chen]
* b0bb9f9  configs: Move sony specific config to its fragment  [Luofan Chen]
* 132b624  sony: config: Use 1M for kernel log  [Juhyung Park]
* 2781ffb  sony: config: Disable most of the debugging configs  [Pranav Vashi]
* efbaa2c  sony: config: Disable wcd-usbss  [Bruno Martins]
* 0be3420  sony: config: Unset all configs related with crow chipset  [Bruno Martins]
* eace1c3  power: Import wakeup_irq_debug driver  [Luofan Chen]
* 4d71f14  ARM64: dts: vendor: Add symlink to sm8550-devicetrees  [Bruno Martins]
* baac276  et6xx: Align implementation in sm8550  [Luofan Chen]
* 1e75ba5  et6xx: Remove reference to hardware_info  [Luofan Chen]
* ddccb85  drivers: sony: Import et6xx driver from 68.0.A.0.768  [Luofan Chen]
* 4984f6f  drivers: Import sony drivers to build inline  [Luofan Chen]
* 7ab8ad6  tools/resolve_btfids: Skip unresolved symbol warning for empty BTF sets  [Kumar Kartikeya Dwivedi]
* 4e81268  minimal sony changes  [Luofan Chen]

#### kernel/sony/sm8550-modules

* f364fb9  dp_display: Fix compile after merge  [Luofan Chen]
* d57ce4e  camera-kernel: Fixup after import sony changes  [someone5678]
* 45e6537  sm8550-modules: qcom: wlan: Remove git merge conflicts leftover from dp_mon.h  [someone5678]
* b1109d2  sm8550-modules: Add .gitignore  [someone5678]
* 6136250  display-drivers: Set display brightness after entering AOD  [Luofan Chen]
* fa463b9  dsi_panel: Add dsi_panel_get_backlight  [Demon000]
* 443fd26  sony: sony_camera: Fix clang compile error  [Luofan Chen]
* c903232  camera-kernel: Import changes from sony  [someone5678]
* a002a15  Android.bp: Change kernel path  [Luofan Chen]
* b5b19e7  sony: Import modules from sony  [Luofan Chen]
* ec83091  video-driver: Import changes from sony  [Luofan Chen]
* 5b7f0ba  securemsm-kernel: Import changes from sony  [Luofan Chen]
* 4812e87  graphics-kernel: Import changes from sony  [Luofan Chen]
* 8f26cf8  display-driver: Import changes from sony  [Luofan Chen]
* 324b14d  bt-kernel: Import changes from sony  [Luofan Chen]
* 51b8ade  audio-kernel: Import changes from sony  [Luofan Chen]
* 10b5e50  Merge remote-tracking branch 'linaro/qca-wifi-host-cmn/wlan-cmn.driver.lnx.2.0.r61-rel'  [someone5678]

#### system/core

* ce5af0f  toolbox/libmodprobe: add toolbox to vendor_ramdisk  [Junki Min]

### 09-02-2024

#### kernel/sony/sm8550

* 550678f  Merge tag 'KERNEL.PLATFORM.2.0.r1-18400-kernel.0' of https://git.codelinaro.org/clo/la/kernel/msm-5.15 into HEAD  [Bruno Martins]

#### kernel/sony/sm8550-modules

* 8476703  Merge tag 'LA.VENDOR.13.2.0.r1-24300-KAILUA.QSSI15.0' of https://git.codelinaro.org/clo/la/platform/vendor/qcom-opensource/wlan/qcacld-3.0 into HEAD  [Bruno Martins]
* 400d29e  Merge tag 'LA.VENDOR.13.2.0.r1-24300-KAILUA.QSSI15.0' of https://git.codelinaro.org/clo/la/platform/vendor/qcom-opensource/wlan/platform into HEAD  [Bruno Martins]
* de5084c  Merge tag 'LA.VENDOR.13.2.0.r1-24300-KAILUA.QSSI15.0' of https://git.codelinaro.org/clo/la/platform/vendor/qcom-opensource/wlan/fw-api into HEAD  [Bruno Martins]
* 1c8ac4a  Merge tag 'GRAPHICS.LA.1.0.r1-08500-KAILUA.0' of https://git.codelinaro.org/clo/la/platform/vendor/qcom/opensource/graphics-kernel into HEAD  [Bruno Martins]
* 0212c29  Merge tag 'LA.VENDOR.13.2.0.r1-24300-KAILUA.QSSI15.0' of https://git.codelinaro.org/clo/la/platform/vendor/qcom/opensource/datarmnet into HEAD  [Bruno Martins]
* fc95562  Merge tag 'LA.VENDOR.13.2.0.r1-24300-KAILUA.QSSI15.0' of https://git.codelinaro.org/clo/la/platform/vendor/opensource/dataipa into HEAD  [Bruno Martins]
* d7fdb1b  Merge tag 'CAMERA.LA.3.0.r1-09600-KAILUA.0' of https://git.codelinaro.org/clo/la/platform/vendor/opensource/camera-kernel into HEAD  [Bruno Martins]

### 09-01-2024

#### bionic

* 26fdf5f  bionic: Optimize libc for performance  [Vaisakh Murali]

#### hardware/xiaomi

* 1eff3da  ir: Stop setting duty cycle  [Sebastiano Barezzi]
* af6a4d1  Drop HIDL IR HAL  [Sebastiano Barezzi]
* 01f73b1  Rewrite IR HAL in AIDL  [Sebastiano Barezzi]
* c978c4d  sensors: Create v{1,2} subdirectories for respective subhals  [Arian]
* 6c4ce8b  hidl: sensors: 2.1: HalProxy: Forward 'lshal debug' options.  [Chris Kuiper]
* ecae650  hidl: sensors: 2.1: Adding suport for multiple multihal config files  [Aditya Chitnis]

#### packages/resources/devicesettings

* d973342  devicesettings: Import popupcamera strings  [Arian]

#### vendor/parasite/common

* 87eba3a  Utils: Run google-java-format  [someone5678]

#### vendor/parasite/prebuilts

* 8da425c  prebuilts: Update Gramophone to 1.0.9  [someone5678]

### 08-31-2024

#### art

* b084098  art: Disable debug tracing on production builds  [Danny Lin]
* 57c0bec  art: Optimize the entirity of ART for performance  [Vaisakh Murali]

#### external/skia

* 7327a0a  skia: Optimize for performance  [ralph950412]

#### frameworks/base

* 5339bbe  SurfaceControl: add more window types to consider NoVote  [Omkar Chandorkar]

#### frameworks/native

* e0f2434  getFps() -> getVsyncRate()  [Hridaya Prajapati]
* 980716f  SF: Scheduler: vote max for NOTIFICATION_SHADE  [Juhyung Park]
* eaf61e8  SF: Scheduler: set an expiration for heuristic layer's high refresh rate usages  [Adithya R]
* a5e4b17  SF: Scheduler: touch boost whenever possible  [Juhyung Park]
* 4f06e53  SF: Scheduler: opportunistically enter idle after touch  [Juhyung Park]
* 0cef3a6  SF: Scheduler: relax measurements for heuristic mode  [Juhyung Park]
* e38353f  SF: Scheduler: remove presentTime check in calculateAverageFrameTime()  [Juhyung Park]
* a7ba87c  SF: Scheduler: maintain current refresh rate if no layers are detected  [Juhyung Park]

#### manifest

* 327a3ea  manifest: Sort entries  [someone5678]
* 7a62809  manifest: parasite: Track external/skia  [someone5678]

#### tools/extract-utils

* ffc1ea0  extract-utils: use git apply instead of patch in apktool_patch  [Arian]
* 64d350b  fixup! extract-utils: make image extraction follow symlinks as well  [nift4]

#### vendor/aosp

* ccf2962  aconfig: Enable qs_new_pipeline  [someone5678]

