# pdx234

### 08-09-2024

#### build/make

* d0b5e18  Revert "Remove non existent snapuserd.recovery package"  [David Anderson]

#### device/sony/sm8550-common

* 6f58ebb  sm8550-common: usb_compositions: Change vid and pid to sony  [Luofan Chen]
* 6d82978  sm8550-common: wfd: Sync vendor.sys.media.target_variant to vendor.media.target_variant  [someone5678]
* 3e644c5  sm8550-common: wfd: enable mouse input for qcom wfd  [Chenyang Zhong]
* 63117e5  sm8550-common: wfd: Enable UIBC (User Input Back Channel) support by default  [someone5678]
* 787e417  sm8550-common: Move in wfd config  [someone5678]
* 46c6462  Revert "sm8550-common: Add BUILD_BROKEN_INCORRECT_PARTITION_IMAGES"  [someone5678]
* 85c2ab3  sm8550-common: Move DeviceAsWebcam resource to non-RRO  [someone5678]
* 46d25a3  sm8550-common: Sync euicc setting to stock  [someone5678]
* 10cfc1f  sm8550-common: Use soong_config_set to set sony powershare variable  [Arian]
* cdb75da  sm8550-common: unset BOARD_USERDATAIMAGE_PARTITION_SIZE  [SGCMarkus]
* 2ce8234  sm8550-common: Remove media_codecs_google_c2*  [Michael Bestas]
* cd055fb  sm8550-common: Convert WiFi firmware symlinks to install_symlink targets  [Bruno Martins]
* 7c15a20  sm8550-common: Declare wlan firmware files as symlinks during extraction  [Luofan Chen]
* b8544ec  sm8550-common: rootdir: Don't check build type for creating wfd dir  [someone5678]
* a2b2e0a  sm8550-common: Build vendor.qti.hardware.capabilityconfigstore@1.0  [someone5678]
* 1cf5452  sm8550-common: Use AOSP default Codec2/OMX ranks  [Michael Bestas]
* 4fb04df  sm8550-common: Remove software omx codec references  [Aaron Kling]
* 75bf421  sm8550-common: media: use AOSP FLAC decoder.  [Anver sadhique]
* def87de  sm8550-common: Fix battery and USB OTG detection  [ghostrider-reborn]

#### frameworks/base

* 9411d85  SystemUI: Also enable IME space overlay to managed profiles if possible  [someone5678]

#### kernel/sony/sm8550

* f319ba0  configs: sony: Enable Kallsyms  [someone5678]
* bf197d4  drivers: qcom: Make CONFIG_QCOM_SOC_SLEEP_STATS_ON_SYSFS depend on DEBUGFS  [Luofan Chen]
* 1ea5b07  Makefile.lib: Lower kernel gzip compression to fastest  [Angelo G. Del Regno]
* fdd1ba7  configs: sony: Enable ZRAM writeback  [Luofan Chen]
* e3842ac  arch: configs: sony: Disable CONFIG_QCOM_SOC_SLEEP_STATS_ON_SYSFS  [Luofan Chen]
* e2fc67e  configs: Move sony specific config to its fragment  [Luofan Chen]
* c3cd540  sony: config: Use 1M for kernel log  [Juhyung Park]
* f3110a0  sony: config: Disable most of the debugging configs  [Pranav Vashi]
* 8276f82  sony: config: Disable wcd-usbss  [Bruno Martins]
* 303907b  sony: config: Unset all configs related with crow chipset  [Bruno Martins]
* 0e38117  power: Import wakeup_irq_debug driver  [Luofan Chen]
* e940904  ARM64: dts: vendor: Add symlink to sm8550-devicetrees  [Bruno Martins]
* ebb520c  et6xx: Align implementation in sm8550  [Luofan Chen]
* ff6e98a  et6xx: Remove reference to hardware_info  [Luofan Chen]
* 7ee0e35  drivers: sony: Import et6xx driver from 68.0.A.0.768  [Luofan Chen]
* 4f1e93c  drivers: Import sony drivers to build inline  [Luofan Chen]
* 5e156f4  tools/resolve_btfids: Skip unresolved symbol warning for empty BTF sets  [Kumar Kartikeya Dwivedi]
* 0ed88d4  minimal sony changes  [Luofan Chen]
* 9f19bed  Merge tag 'ASB-2024-08-05_13-5.15' of https://android.googlesource.com/kernel/common into HEAD  [Bruno Martins]
* 783cf06  Merge branch 'android13-5.15-lts' of https://android.googlesource.com/kernel/common into HEAD  [Bruno Martins]
* 7326483  Merge tag 'KERNEL.PLATFORM.2.0.r1-18200-kernel.0' of https://git.codelinaro.org/clo/la/kernel/msm-5.15 into HEAD  [Bruno Martins]

#### vendor/google/dexopt_profiles

* a16f2cf  dexopt_profiles: Update  [someone5678]

#### vendor/google/gms

* 1b2b019  gms: Update  [someone5678]
* 3696adb  gms: Matching AccessibilityMenum overlay name to other overlays  [someone5678]
* a583126  gms: Add DreamlinerOverlay  [someone5678]
* a7f7318  pixel-style: Add rro to enable clear calling on supported devices  [AnierinB]
* f8c7f45  gms: Remove now-auto extracted PixelSfpsOverlay  [someone5678]
* d7596be  gms: Import PixelSfpsOverlay  [someone5678]

#### vendor/google/mainline_modules

* a9e4d22  mainline_modules: Disable enforce-product-packages-exist  [someone5678]
* 8d7cc5a  mainline_modules: Update  [someone5678]

### 08-08-2024

#### build/make

* 1e00ab6  Merge tag 'android-14.0.0_r61'  [someone5678]

#### external/cronet

* 5810fd3  cronet: Fix build with custom out directory  [M. Masters]

#### external/exfatprogs

* 15782e7  exfatprogs: Add .gitupstream  [someone5678]
* c95c0d6  Remove github workflow  [someone5678]
* f7beabe  Fixing issues in METADATA file external_updater expects string in METADATA file but it couldn't find any to update the project.  [Sadaf Ebrahimi]
* 6b720f3  [LSC] Add LOCAL_LICENSE_KINDS to external/exfatprogs  [Bob Badour]
* d34f749  ANDROID: Add metadata files  [Daniel Rosenberg]

#### frameworks/av

* e2ea585  Merge tag 'android-14.0.0_r61'  [someone5678]

#### frameworks/base

* e92e33d  Merge tag 'android-14.0.0_r61'  [someone5678]

#### frameworks/native

* 746f510  Merge tag 'android-14.0.0_r61'  [someone5678]

#### hardware/interfaces

* ac18fa3  Merge tag 'android-14.0.0_r61'  [someone5678]

#### hardware/xiaomi

* 6c242be  Provide a Java library with required Xiaomi telephony methods  [danielml]

#### manifest

* 5715eba  manifest: parasite: Update kernel-build-tools  [someone5678]
* 39dff28  Merge tag 'android-14.0.0_r61'  [someone5678]

#### system/core

* c94f3de  Merge tag 'android-14.0.0_r61'  [someone5678]

#### vendor/google/overlays/ThemeIcons

* ce36465  pixel-style: overlay: Update anxcamera icon  [Karan Parashar]

#### vendor/google/pixel-additional

* a2e83a3  pixel-additional: Update  [someone5678]

#### vendor/parasite/common

* 449bf3c  PixelPropsUtils: Update  [someone5678]

### 08-07-2024

#### external/exfatprogs

* 7262607  exfatprogs: release 1.2.5 version  [Hyunchul Lee]

#### manifest

* c0031cd  Manifest for Android 14.0.0 Release 61 (AP2A.240805.005.F1)  [The Android Open Source Project]

### 08-06-2024

#### external/exfatprogs

* d5ace3a  Merge pull request #271 from exfatprogs/exfat-next  [Namjae Jeon]
* 13d7fc8  exfat: change to use bswap macros  [Yuezhang Mo]
* 4f8f750  ci: support testing for big-endian system  [Yuezhang Mo]
* 3c2a632  exfatprogs: fix endianness issues  [Yuezhang Mo]
* aa447cf  fsck: fix decompress upcase table for big-endian systems  [Yuezhang Mo]

#### hardware/xiaomi

* 21b5ec5  fixup! dolby: Restore all settings upon bootup  [Adithya R]
* 9f45ed6  dolby: Remove deprecated PlainTooltipBox  [Pranav Vashi]
* cdfe11b  dolby: Introduce graphic equalizer  [Adithya R]
* 7ea80d4  dolby: Add launcher icon  [Pranav Vashi]
* 705bba8  dolby: Override AudioFx  [Pranav Vashi]
* 102a5f5  dolby: Use all shared resources from devicesettings  [Bruno Martins]
* 351cda0  dolby: Fix build with kotlinc 1.9.0  [basamaryan]
* 3f67403  dolby: Restore current profile _after_ resetting profiles  [Adithya R]
* 8307ce5  dolby: Do not set volume leveler amount  [Adithya R]
* f18ca2d  dolby: Restore all settings upon bootup  [Adithya R]
* 76b5ba0  dolby: Rewrite in Kotlin  [Adithya R]
* 5bb474f  dolby: Revert "Re-enable speaker virtualization after bootup"  [Adithya R]
* 7f93614  dolby: Convert to SwitchPreferenceCompat  [Michael Bestas]
* 69c43c9  DolbyManager: Migrate to CompoundButton.OnCheckedChangeListener  [Chaohui Wang]
* 0097e83  dolby: Enable use_resource_processor for all sysui deps  [Peter Kalauskas]
* 34c2ef9  xiaomi: Introduce Dolby Atmos  [Adithya R]
* d72402a  vintf: Add more hals to fcm  [Adithya R]
* 2227a4c  vibrator: Add support for TEXTURE_TICK effect  [someone5678]
* 7b83aaa  vibrator: effect: libqtivibratoreffect: Add libc++fs to static libs  [someone5678]
* 2372940  hidl: biometrics: fingerprint: Set thread to high CFS priority  [Nauval Rizky]
* bd479bf  interfaces: fxtunnel: Add fxtunnel 1.0 interface  [bengris32]
* 21d70b5  XiaomiEuicc: Remove references to EuiccPixel  [Bruno Martins]
* 9503a61  XiaomiEuicc: Move to priv-app and grant required permissions  [someone5678]
* 73a8c25  XiaomiEuicc: Disable EuiccGoogle when GMS and GSF are not installed  [Peter Cai]
* e57edfc  Introduce XiaomiEuicc  [Bruno Martins]
* 29cc87d  vintf: Add more hals to fcm  [Adithya R]

#### packages/apps/GameSpace

* 4873897  GameSpace: Add GamePropsUtils toggle  [someone5678]
* 48b2ab1  GameSpace: Use accent_device_default_light for icon bg color  [someone5678]

#### vendor/parasite/common

* a7559c3  GamesPropsUtils: Allow enable/disable at runtime  [someone5678]
* a26a878  PixelPropsUtils: Allow enable/disable at runtime  [someone5678]
* 22b8669  libs: Add hide annotation to *Utils  [someone5678]
* 95c0c8d  CustomFeaturesUtils: Report tensor features for Pixel Launcher  [someone5678]

### 08-05-2024

#### device/sony/sm8550-common

* ff675d5  sm8550-common: Load adsp_loader_dlkm for battery status in recovery  [pjgowtham]
* f4505cf  sm8550-common: Build sounddose interfaces  [someone5678]
* 002c9f8  sm8550-common: overlay: Add saturation mode to color modes  [someone5678]
* 5050d13  sm8550-common: props: Remove ro.build.shutdown_timeout  [someone5678]
* c60d30c  sm8550-common: Move all sepolicy to hardware/sony  [someone5678]
* 0bfe85f  sm8550-common: Build more libraries  [someone5678]
* f4fbc81  sm8550-common: Build vendor variant of libstagefright_omx  [someone5678]
* e392b59  sm8550-common: Setup DeviceAsWebcam  [Yumi Yukimura]
* b7110b2  sm8550-common: init: Give proper permissions for /dev/diag  [Yohan Black]
* 4e476c3  sm8550-common: Build libidd dummy  [someone5678]
* eaaa310  sm8550-common: Kill useless in device diagnostics  [someone5678]
* 40a93d0  sm8550-common: Build some VNDK libraries  [micky387]
* a33c58e  sm8550-common: props: Move props to avoid sepolicy denials  [someone5678]
* 3bbf5eb  sm8550-common: Enable blur  [someone5678]
* ecca481  sm8550-common: Update parasite signature dir  [someone5678]

#### frameworks/base

* be18a42  CameraManager: Prevent array index out of bound exception  [Pranav Vashi]
* eb71a47  CameraManager: Prevent out of bounds when extracting camera IDs  [minaripenguin]
* ad832b3  [TMP] base: Hack for PhoneLink  [someone5678]
* 936b708  base: Add hide annotation to all Device Integration components  [someone5678]
* 7e83010  PackageManager: Add platform sig arr for MS system apps  [someone5678]
* 3c01bc3  base: Make device integration disable/enable through props  [someone5678]
* f3fd9e5  base: Enable device integration  [Omkar Chandorkar]
* d01b643  base: add support of the Phone Link  [Arthur Shuai]
* 3cb8fe3  SystemUI: Use groove for brightness slider  [minaripenguin]
* 6b45c0e  ImageReader: Allow skipping of nativeDetachImage  [minaripenguin]
* 0a504da  fixup! base: Hide ADB and developer setting enable status [1/2]  [someone5678]
* 25fdaa4  camera2: allow access to CaptureRequest.mLogicalCameraSettings  [Cosmin Tanislav]
* d4a598e  SystemUI: Hide face unlock recognition animation on UDFPS devices  [someone5678]
* e0b4c86  data: Include NotoColorEmojiAddon font  [Radosław Błędowski]
* af232a7  data: Add missing Noto fonts  [Jyotiraditya Panda]
* 31289b6  Extends "base: Implement cutout force full screen [1/2]"  [someone5678]
* 0205cab  fixup! Allow to suppress notifications sound/vibration if screen is ON [1/2]  [Pranav Vashi]
* df4df22  base: Fix gamespace on secondary users  [Dhina17]
* 9ee2a0f  base: Fix NPE in GameManagerService  [Dhina17]
* 646ae59  GameManagerService: Prevent multiple threads from accessing settings observer onChange  [minaripenguin]
* a71733a  GameManagerService: Set device_config property on behalf of GameSpace  [Dhina17]
* 414ca72  SystemUI: Add support for GameSpace  [Nauval Rizky]
* bdf6126  base: add API for disabling gestural navigation  [ezio84]
* 63d58f2  Fix UDFPS icon and progress while enrolling  [Tobias Merkel]
* 21462a2  Fix pipe fds leak in copyInternalSpliceSocket  [hangl]
* f6668cd  [SQUASH] services: Boost gesture flings  [minaripenguin37]
* 040e575  display: Don't reset brightness adjustment on clearUserDataPoints()  [LibXZR]
* 9ca2dba  PointerIcon: Add leniency to hotspot validation for scaled icons  [Prabir Pradhan]
* 173eac1  CameraManager: Fix NPE in getting cameraIds  [afterallafk]
* a2b5a69  SystemUI: IslandView: Use status bar height as top margin  [minaripenguin]
* d094b15  fixup! SystemUI: Integrate Google Lens into Screenshot UI  [someone5678]
* 86d8ac6  fixup! SystemUI: Allow using 4G icon instead of LTE [1/2]  [someone5678]
* ccf2f49  BluetoothDialog: Fix theme context  [Pranav Vashi]
* d9c0b5c  SystemUI: Allow skipping mirroring confirmation dialog [1/2]  [Sebastiano Barezzi]
* 24dca73  SystemUI: Disable FaceUnlock Lockouts [1/2]  [minaripenguin]
* f67d09c  fwb: Add missing android.permission.REGISTER_STATS_PULL_ATOM launcher3 permission  [karthik1896]
* 7449a37  Camera: Prevent crash with prebuilt camera metadata  [Pranav Vashi]
* 884ec1e  keylayouts: Nintendo ProCon: Map it like stock does  [Nolen Johnson]
* e1ab3a3  LensScreenshotReceiver: Return when failed to start activity  [someone5678]
* 481b5b3  Import certification changes  [someone5678]
* 02b61e7  Camera: Clearing exception for Extended Face  [Sauhard Pande]
* d993278  camera: Allow selected camera apps to skip unconfigure  [LuK1337]
* 1de6c7e  Guard in short-circuit evaluations for stringSplit methods.  [Mohammed Irfan]
* 07c3e5b  Camera: Don't crash when trying to disable shutter sound  [jhenrique09]
* 32fb07d  Camera: Add feature extensions  [Sauhard Pande]
* 1ce0ec5  Fix Photosphere/Camera FCs  [Jostein Kjønigsen]
* fdee162  Allow sending vendor- or device-specific commands to the camera HAL.  [Danny Baumann]
* af2f9cb  Camera: Expose aux camera if packagename is null  [wbs306]
* 933a659  CameraDeviceImpl: Don't crash when checking input configuration failed  [Xayah]

#### vendor/google/gms

* b178432  gms: Import missing preinstalled packages config  [someone5678]

#### vendor/google/overlays/ThemeIcons

* 44e2abd  ThemeIcons: Clean-up and update official gms icons  [someone5678]
* bf4f99e  ThemeIcons: Move under vendor/google  [someone5678]

