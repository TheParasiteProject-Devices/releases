# pdx234

### 06-11-2024

#### device/sony/sm8550-common

* 5438487  sm8550-common: Update parasite signature dir  [someone5678]
* d4a2683  sm8550-common: Run reorder-libs.py  [someone5678]
* a63e086  [TMP] Automatically patch Sony changes to qti usb  [someone5678]
* 33b13c0  sm8550-common: Include Qcom usb configs  [someone5678]
* 9fe9179  sm8550-common: Build and import more display components  [someone5678]
* 30e5cfb  sm8550-common: configs: wifi: Import configs from wifi-bonding  [someone5678]
* 55d67b5  sm8550-common: props: odm: Enable SDR dimming for HWC  [someone5678]
* 0da3e60  sm8550-common: props: odm: Clean-ups  [someone5678]
* 426ed1b  sm8550-common: props: Set default Wi-Fi country code  [someone5678]
* deb01c0  sm8550-common: vibrator: Rename to avoid conflicts  [someone5678]
* 2e7d691  sm8550-common: Update powerhint.json nodes to kalama  [someone5678]
* d448065  sm8550-common: Use HintManager for HWUI  [Vaisakh Murali]
* 48733cb  sm8550-common: rootdir: Kill WALT CPU boosting  [Sugakesshaa]
* d4ad0aa  sm8550-common: powerhint: Drop CPU freqs boosting on INTERACTION  [bheatleyyy]
* 176268b  sm8550-common: powerhint: Follow taro's CPU freqs for little cluster  [bheatleyyy]
* 92709ce  sm8550-common: rootdir: Do not allow foreground tasks to run on CPU7  [Jake Weinstein]
* 4b6c366  sm8550-common: rootdir: Move background cpuset to CPU0-1  [Jake Weinstein]
* 88a884b  sm8550-common: rootdir: Set restricted cpuset to the same CPUs as system-background  [Jake Weinstein]
* 950d822  sm8550-common: sepolicy: Allow powerhal write to /proc  [Sugakesshaa]
* c8aec3f  sm8550-common: rootdir: Enable powerhint parsing after boot completion  [Bruno Martins]
* d00bac6  sm8550-common: powerhint: Adapt and tune for SM8475 (cape)  [bheatleyyy]
* 7c4b3cd  sm8550-common: Import powerhint.json from lahaina  [bheatleyyy]
* d3579a2  sm8550-common: Provide a static lib for power mode extension  [Arian]
* abd1a77  sm8550-common: Migrate to common libqti-perfd-client and power-libperfmgr  [Bruno Martins]
* 1b56a36  sm8550-common: Remove QTI perfd  [Wei Wang]
* 7009aa8  sm8550-common: Move init.qcom.post_boot.sh here  [someone5678]
* c4df641  sm8550: Signing build with custom key  [someone5678]

#### frameworks/base

* bd8c417  base: Do not reset keyguard going away state  [minaripenguin]
* 6baacdd  WallpaperManagerService: Get rid of removed UIDs that have set dim  [Ido Ben-Hur]
* 2644130  code: ConfigurationController: Prevent an NPE  [minaripenguin]

#### hardware/qcom-caf/common

* 1c67438  common: Add support for pineapple boards  [Venkat Yadlapati]

#### vendor/aosp

* e3c86fc  vendor: Update parasite repo to vendor/parasite/common  [someone5678]

#### vendor/certification

* 0ecf3ed  certification: Fix scripts  [someone5678]
* fcd65ef  setup-buildprops: Clean-ups  [someone5678]
* 4ce609f  Update README.md  [someone5678]
* 01cef2c  certification: Small tidy up  [someone5678]
* d8ca278  Automatically setup system.prop at build time  [someone5678]
* 6099941  certification: Add public pif  [someone5678]
* 22784c8  setup-buildprops.sh: Add public pif.json for placeholder  [someone5678]
* dea805b  setup-buildprops: Exit when no pif.json exists  [someone5678]
* 0278611  Update README.md  [someone5678]
* 09ac8b5  certification: Add setup-buildprops script  [someone5678]
* e15f5c8  certification: Don't public properties  [someone5678]
* e9fa8ee  certification: Spoof more props  [someone5678]

#### vendor/parasite/prebuilts

* 619a411  Update README.md  [someone5678]
* a9f9b8d  prebuilts: update-files: Comment out Accord fetching  [someone5678]
* e60146b  prebuilts: update-files: Add Accord  [someone5678]
* 07c0a2a  prebuilts: Import Accord  [someone5678]
* a8fc345  prebuilts: Add support for Accord  [someone5678]

### 06-10-2024

#### build/soong

* e558713  allowlists: support inline signing for U [1/2]  [John Galt]

#### device/sony/pdx234

* aa2a6b3  pdx234: Run reorder-libs.py  [someone5678]

#### frameworks/base

* 7f6e4f5  [TMP] base: Don't ignore PhoneLink's call on calledWithValidTokenLocked  [someone5678]
* 3777181  base: Add hide annotation to all Device Integration components  [someone5678]
* 11d4f47  PackageManager: Add platform sig arr for MS system apps  [someone5678]
* 4e1cf10  services: Introduce X-reality display engine mode [1/2]  [minaripenguin]
* a4cb3d99  Add Gravis GamePad Pro USB key layout  [Nathaniel Manista]
* 5f4f44c  Add keylayout for Xbox Wireless Controller  [Akshay Tigga]
* 12bc04f  SystemUI: screenshot: Catch RejectedExecutionException  [someone5678]
* 279e4bc  base: Make device integration disable/enable through props  [someone5678]
* 16397a6  base: Enable device integration  [Omkar Chandorkar]
* 5e3cf23  base: add support of the Phone Link  [Arthur Shuai]
* 06b59a3  HideDeveloperStatusUtils: Avoid NPE with mApps  [Joey]
* eaca6d2b3  SystemUI: Fix the bluetooth icon cannot be toggled by status tuner  [lgjint]
* d10afa0  SystemUI: Add null check for wakelock in KeyguardViewMediator  [Pranav Vashi]
* 86b13a0  SystemUI: Prevent OOB when reinflating QS panel with notifications  [minaripenguin]
* 329ec39  SystemUI: Prevent systemui crash when reinflating QS  [minaripenguin]
* 81a63ae  SystemUI: customization: Avoid NPE in ClockRegistry  [someone5678]
* b76544c  SystemUI: tuner: Set profile to be primary profile only  [someone5678]
* e133c4e  WindowDecor: Pass correct displayId for back key event  [Dhina17]
* b593364  TelephonyManager: Gracefully handle null telephony service [2]  [minaripenguin]
* f74c7a9  SystemUI: Ignore R8 optimizations warnings  [minaripenguin]
* 240f979  SystemUI: Do not shrink resources  [minaripenguin]
* 74cdcfd  ExternalStorageProvider: Conditionally remove SAF restrictions [1/2]  [Richard Raya]
* 74ce248  Wifi Standard: Optimize handling for flooding network requests  [minaripenguin]
* de25a7b  JobSchedulerService:fix arrayIndexOutOfBoundsException to aviod systemServer crash.  [lijilou]
* 11a6183  Vibrator: Force to return a non-zero duration  [flakeforever]
* ca6dc14  Reapply "Make dun APNs as read-only by default."  [ShevT]
* c176c24  Fix NPE when traversing viewgroup display list  [minaripenguin]
* dc4ff56  BatteryStatsImpl: Guard against OOB  [Ido Ben-Hur]
* 8d79a46  core: Broadcast intent when display power state changes  [Adithya R]
* 6285af5  Allow signature spoofing for microG Companion/Services  [LuK1337]
* 56ca218  SystemUI: Add FingerprintInteractiveToAuthProvider implementation  [Adithya R]
* 83be715  SettingsLib: Use framework resource for headline font  [Adithya R]
* ff388d2  SystemUI: Fix lottie malformed json crashes  [minaripenguin]
* 94286f2  EdgeBackGestureHandler: Change back gesture height intervals  [Anushek Prasal]
* ec1395a  base: Allow to hide screen capture status from apps [1/2]  [someone5678]
* 0170443  BrightnessController: Update icon state for auto bg icon  [yukiscape]
* 3190f23  ActivityManagerNative: Prevent possible soft-reboot  [fusionjack]
* 7ed301d  SystemUI: IslandView: Update color implementation  [Pranav Vashi]
* c471e26  SystemUI: IslandView: Auto remove now playing notification  [Pranav Vashi]
* beff01a  SystemUI: IslandView: Properly handle island notification on track change  [Pranav Vashi]
* 3d7238a  Revert "Remove dependency on IME subtype from TSMS"  [Michael Bestas]
* a947848  Allow lid to send a generic COVER_CHANGED broadcast  [jrior001]
* c1f9607  SystemUI: add FloatingRotationButton for hw-key devices  [Michal Pražák]
* 5984f91  BatteryMeterView: Hide icon on battery-less devices  [Bruno Martins]
* e045f73  fixup! SystemUI: Make Navbar Secondary Handle Appear Correctly.  [OnlyTomInSecond]
* a81791f  Don't skip theme application if it's already current  [Michael Bestas]
* c24314d  SystemUI: theme: Clean-up and fix black theme enable  [someone5678]
* 2981e78  SystemUI: Clean-up IME space feature  [someone5678]
* 4066e5e  KeyStore: Add getApplicationContext method required for Asus Devices  [Jackeagle]
* 73f9760  SystemUI: PowerShareTile: Clean-ups  [someone5678]
* d214024  SystemUI: screenshot: add delay for long-press partial screenshot  [Pranav Vashi]
* 4be56b05  Forward port 'Swap volume buttons' (1/3)  [nadlabak]
* 5d95d8c  SystemUI: screenshot: close QS after launching long screenshot activity  [LuK1337]
* 8be7d87  SystemUI: screenshot: disable magnification for partial screenshots  [Cosmin Tanislav]
* ab0db39  SystemUI: screenshot: open long screenshot activity for partial screenshots  [Cosmin Tanislav]
* fb05dd4  Implement click to take partial screenshot [1/3]  [Jesse Chan]
* 1345f62  CameraServiceProxy: fix exception  [Dmitrii]
* 2509647  fwb: silence more spam  [Dmitrii]
* 872e2fe  Fix "Manage App & Content access" for profiles  [Tommy Webb]
* 742f2e2  Keyguard: Hide battery indication on battery-less devices  [Bruno Martins]
* de17412  SettingsLib: Update 5G+ icon to Silk design  [Adithya R]
* 247aff7  SettingsLib: Update 4G+ icon to Silk design as well  [TH779]
* 848b0a5  SettingsLib: Update LTE+ icon as per new Silk design  [Adithya]
* bac4825  PackageManager: Add separated vendor platform signatures for GMS  [someone5678]
* af05dab  PackageManager: Allow device to specify vendor platform signatures  [Ethan Chen]
* dbadc28  Island: Fix some album-art not showing  [Subratam6296]
* 44430c7  Island: Use status bar height as top margin  [minaripenguin]
* 4e28459  base: Fix Black theme not applied immediately  [someone5678]
* 2478f2c  base: SystemUI: Add Black theme [1/3]  [SagarMakhar]
* 372c16b  Fix NPE in SystemUI  [first last]
* cd98784  SystemUI: screenrecord: Also remember share mode selection  [Ido Ben-Hur]
* a4c31a4  Textutils: Optimize writeToParcel performance  [minaripenguin]
* a17c767  SettingsLib: Fix crash when checking emergency gesture state  [minaripenguin]
* 35b65bc  Island: Resolve notification contents  [minaripenguin]
* 33e8d6c  UpdateEngine: Add perf mode binder interface  [Luca Stefani]
* bb6e2b9  SystemUI: Disable dagger.fastInit option  [someone5678]
* a5a9d99  Integrate Pixel framework hooks and wrappers  [minaripenguin]
* 45f1712  SystemUI: Introduce wifi standard icon feature [1/2]  [minaripenguin]
* ef7be6a  CarrierConfig: allow toggling VoWiFi while roaming by default  [r3g_5z]
* dc455ec  SystemUI: biometrics: Follow user setting to confirm face unlock  [Pranav Vashi]
* 4ca3c3f  base: make per-app work with multi audio focus  [El Dainosor]
* 109ef85  SystemUI: Use proper tint for face unlock icon  [Pranav Vashi]
* d444cd2  SystemUI: FaceUnlock: Add margin based on lock icon  [someone5678]
* 137b698  SystemUI: Implement face unlock recognition animation and text  [minaripenguin]
* 85150d1  SystemUI: Follow monet theme on privacy indicators  [minaripenguin]
* fb1825f  base: PhantomProcessList: Correctly handle orphan procs  [Ido Ben-Hur]
* 419ec5a  VolumeDialogImpl: Handle cases where media controller is not available  [danielml]
* c7e2c47  base: Disable haptic feedback on scrolling correctly  [someone5678]
* 366eb24  BootAnimation: Check persist.sys.boot.theme instead  [someone5678]
* c35ac90  SystemUI: Correctly disable double tap to sleep gesture by default  [someone5678]
* ac9c5c2  core: BatteryManager: Add few more Battery broadcast intents  [Jyotiraditya Panda]
* 6052866  Screenrecord: Fix notifications not being dismissed  [Ido Ben-Hur]
* ed1f4804  SystemUI: Launch hotspot settings on long click instead of click  [someone5678]
* 34a39d2  Revert "Use HwLight.type as the key of mLightsByType"  [Joker-V2]
* 77d447fa  SystemUI: Adapt "Extend kill button to notification conversation guts" to A14 QPR2  [someone5678]
* f78c6ff  Settings: Always show package name in installed app details  [Michael Bestas]
* f50fd82  [TMP] base: Don't append app name to App Clips screenshot for now  [someone5678]
* b238116  SystemUI: tuner: Migrate MainSwitchBar and Switch to Material3  [Bruno Martins]
* 69c28ba  FaceSense: Adapt for 14 QPR2  [aswin7469]
* 7074fed  SystemuUI: tuner: migrate to SwitchPreferenceCompat  [aswin7469]
* aa95a1f  SystemUI: Tuner: Move to SwitchPreferenceCompat  [someone5678]
* 3f290c7  SystemUI: New per-app volume icon  [ReallySnow]
* 5323973  Island: Improve text filtering to support symbols  [minaripenguin]
* c38c319  Island: Do not show now playing on keyguard and dozing state  [minaripenguin]
* cdb423f  IslandView: Fix and improve notification regex filtering  [minaripenguin]
* a7dbf9e  IslandView: Ensure global headsup is enabled  [Pranav Vashi]
* 6306093  Island: Return if sbn.notification.contentIntent is NULL  [someone5678]
* 66c8b6f  Island: Get application info from all user  [someone5678]
* 7f4ee24  Island: Import SystemUIToast icon retrieving logic  [someone5678]
* 811b095  Island: Squeeze it  [someone5678]
* ad0456d  SystemUI: Implement Island notification feature [1/2]  [minaripenguin]
* c46a511  base: support per-app volume [2/3]  [cjybyjk]
* db031d1  SystemUI: Add haptics to brightness slider [1/2]  [Vaisakh Murali]
* 870c2ea7  base: Allow toggling floating rotation button [1/2]  [Ido Ben-Hur]
* 0b22843  SystemUI: Cleanup screenshot sound/vibration logic  [Adithya R]
* 329e4a1  SystemUI: Adapt screenshot sound to ringer modes  [Ashwin R C]
* ebc0221  base: core: Unregister broadcast receiver only when registered  [Soo-Hwan Na]
* a371692  core: Gracefully handle unregistering of unregistered receivers/services  [minaripenguin]
* dd245ff  Fix unknown sources app install confirmation  [Tommy Webb]
* c704be8  Fix uninstall for all users  [Tommy Webb]
* 7786de0  SettingsLib: Make all user apps cloneable [1/2]  [Jyotiraditya Panda]
* 5aba594  charging: Allow using vibration without sounds  [xyyx]
* eae5432  base: Add support for disabling fingerprint lockout [1/2]  [SamarV-121]
* 10563e1  CustomUtils: Refactor isPackageInstalled method  [Pranav Vashi]
* 6d0262e  services: Disable automatic system server heap dumps by default  [minaripenguin]

#### manifest

* 51f359f  manifest: parasite: Reconstructure parasite repos  [someone5678]
* 4c01d0f  manifest: parasite: Move microsoft repo under vendor/microsoft/mms  [someone5678]

#### vendor/aosp

* ff16bc6  vendor: Move parasite specific stuffs to parasite repo  [someone5678]

#### vendor/microsoft/mms

* 9e05095  mms: Enable dex-preopt  [someone5678]
* e7c8add  mms: Update structure  [someone5678]
* e993c51  microsoft: Move repo unser vendor/microsoft/mms  [someone5678]

#### vendor/parasite/common

* 2742a96  Revert "PropImitationHooks: Fix bootloader spoofing [1/2]"  [someone5678]
* 1ffe403  parasite: Move under vendor/parasite/common  [someone5678]
* 7a3b589  parasite: Move in parasite specific stuffs here  [someone5678]

#### vendor/parasite/prebuilts

* 9aa781a  Update README.md  [someone5678]
* 1bcf269  prebuilts: Add app file to remove / output file as arg  [someone5678]
* 5b94ed3  prebuilts: update-files: Add microG  [someone5678]
* ace628c  parasite-prebuilts: Import microG components  [someone5678]
* b4c593d  prebuilts: Prepare for import microG  [someone5678]
* e0e6f72  prebuilts: Update inclusion  [someone5678]
* ea0b817  prebuilts: Move under vendor/parasite/prebuilts  [someone5678]

#### vendor/parasite/signatures

* 4ebad1f  signatures: Move under vendor/parsite/signatures  [someone5678]

### 06-09-2024

#### vendor/aosp

* 4ca7223  config: device_framework_matrix: Add lineage.hardware.radio  [Sebastiano Barezzi]

#### vendor/google/gms

* bf39f8a  halcyonUI: overlay: Disable Google Dialer Call recording TTS  [HeroBuxx]

#### vendor/google/pixel-additional

* f3c34da  pixel-additional: gms: Enable dex-preopt  [someone5678]
* 3b57827  Update README.md  [someone5678]

#### vendor/parasite/prebuilts

* 3894fbe  parasite-prebuilts: Import Omni  [someone5678]
* 4110c5a  parasite-prebuilts: Ship Omni by default  [someone5678]

### 06-08-2024

#### build/make

* 4ce50c8  build: Add support to attach bootconfig to ramdisk  [Yumi Yukimura]
* 573c66b  build: Add support to combine ramdisk images  [Yumi Yukimura]
* d0c0ecc  build: Allow to build vendor ramdisk image independent of vendor boot image  [Yumi Yukimura]
* adee185  build: Move vendor ramdisk related build rules to top  [Yumi Yukimura]

#### device/sony/sm8550-common

* 7f87d3a  sm8550-common: Import Google changes on DEC7 Volume on all mic paths  [Arseniy Graur]
* ad1c33c  sm8550-common: rottdir: Remove duplicated TA patition permission setup  [someone5678]
* 61059a8  sm8550-common: rootdir: Move powershare permission setup to ueventd.sony.rc  [someone5678]
* 4547a9b  sm8550-common: configs: audio: Sync hotword input to primary input  [someone5678]
* b1e36e2  sm8550-common: Build Kprofiles as LKM  [someone5678]
* 052137e  sm8550-common: overlay: Add Sony's public vendor platform signature  [someone5678]
* 8237a52  sm8550-common: Enable puffdiff for ota compression  [someone5678]
* 0c6cf02  sm8550-common: Enable zucchini for ota compression  [someone5678]
* 2702df5  sm8550-common: update sf related props  [SGCMarkus]
* de25ae5  sm8550-common: Setup additional options for ota  [someone5678]
* 3b40def  sm8550-common: BOARD_CHARGER_ENABLE_SUSPEND becomes ro.charger.enable_suspend  [Redick Lin]
* 45c8f41  sm8550-common: Include mainline common board config  [someone5678]
* 5dd5821  sm8550-common: Enable watchdog timeout loop breaker  [someone5678]
* 6761113  sm8550-common: props: Sync suspend properties to gs201  [someone5678]
* c57b7c4  sm8550-common: Reduce shutdown wait time to 0 sec  [someone5678]
* ff0b2d4  sm8550-common: properties: Disable continuous transaction tracing on all build types  [SamarV-121]
* 614ebac  sm8550-common: Force device to treat 170M as sRGB in SF  [Alec Mouri]
* 7b75cd5  sm8550-common: props: Switch to AutoSingleLayer Android 13 Setting  [johnmart19]
* f828668  sm8550-common: props: Enable incremental FS feature.  [P.Adarsh Reddy]
* ad1d53e  sm8550-common: properties: Disable Async MTE on System Server  [Vinay Verma]
* 90235bd  sm8550-common: properties: Kill off IMS logspam with fire  [Adithya R]
* 6d3cf36  sm8550-common: Remove FM Tuner from audio input devices  [iovxw]
* 198085f  fixup! sm8550-common: configs: audio: Add hotword input for hotword mic concurrency  [someone5678]
* 58fce52  sm8550-common: configs: audio: Add hotword input for hotword mic concurrency  [Jasmine Cha]
* 82be244  sm8550-common: Don't set ro.com.android.dataroaming  [someone5678]
* c28aee5  update-sha1sums: Also recognize '- From' as needSHA1  [someone5678]
* 40eb1bb  sm8550-common: Update ERoFS LZ4HC compression rate to 12  [someone5678]
* 3beeec6  sm8550-common: Add 34 to PRODUCT_EXTRA_VNDK_VERSIONS  [someone5678]
* a34d7a1  sm8550-common: Set VNDK versions  [someone5678]
* 1bf9933  sm8550-common: Patch configs to drop NFC logging levels  [LuK1337]
* bd24191  sm8550-common: Allow extracting only firmware images  [Bruno Martins]
* bc5c08f  sm8550-common: Add firmware extraction support  [Michael Bestas]
* f7dfeb6  sm8550-common: Drop EuiccGoogle  [someone5678]
* 3a77eb8  sm8550-common: Build vendor variant of android.hardware.wifi.hostapd-V1-ndk  [someone5678]
* 57d5e5c  sm8550-common: Commonize hash algorithm  [someone5678]
* 53e6887  sm8550-common: overlay: Remove some useless doze overlays  [Tim Zimmermann]
* 057a146  sm8550-common: props: Drop sys.vendor.shutdown.waittime  [someone5678]
* d3582ed  sm8550-common: disable FW TWT  [Juhyung Park]
* ccf1d61  sm8550-common: configs: Move wifi config to device tree  [someone5678]
* 34ec4ab  sm8550-common: sepolicy: Add device specific policies  [someone5678]
* 5b35a5f  sm8550-common: sepolicy: Allow PowerOffAlarm app to find alarm service  [someone5678]
* 85bfa7e  sm8550-common: sepolicy: Allow vendor init to get powerctl_prop  [someone5678]
* 4cf242f  sm8550-common: props: Move props to other partition to avoid avc denial  [someone5678]
* e395851  sm8550-common: overlay: Decommonize wifi_tether_configure_ssid_default  [someone5678]
* 6a8affb  sm8550-common: overlay: Drop MMS user agent overlays  [Sebastiano Barezzi]
* ad654e2  sm8550-common: sepolicy: Allow hal_nfc_default to search oem partition  [someone5678]
* f4161fe  sm8550-common: sepolicy: Allow vendor_init to set audio_prop  [someone5678]
* a041b18  sm8550-common: rootdir: Don't enable adb on boot  [Luofan Chen]
* 7b794d3  sm8550-common: sepolicy: avoid hal_fingerprint_default denials  [someone5678]
* 1268898  avoid qseecomd denials  [David]
* 8679a1d  sm8550-common: overlay: Move Lineage-SDK resources  [someone5678]
* 70d1b53  sm8550-common: sepolicy: Allow vendor_hal_usb_qti to access/modify sysfs_battchg_ext  [someone5678]
* 4db061f  sm8550-common: Target BoardConfigReservedSize makefile to this project  [someone5678]
* 28df922  sm8550-common: Inherit XperiaModules  [someone5678]
* 7c627a3  sm8550-common: Import QCOM audio effects from OnePlus 9R  [someone5678]
* 77838e3  sm8550-common: audio: use QCOM Implementation for Audio Effects  [ANUSH MADATHUMKARA]
* 2c20014  sm8550-common: Reduce shutdown wait time to 0 sec  [someone5678]
* ca4787b  sm8550-common: BoardConfig: Set loop.max_part to 8  [someone5678]
* 1f070d2  sm8550-common: blobs: Add from statement  [someone5678]
* b0260cd  sm8550-common: blobs: Import PowerOffAlarm  [someone5678]
* 128cf54  sm8550-common: overlay: telephony: Drop redundant platform_number_verification_package  [someone5678]
* df79254  sm8550-common: Enable fastbootd support  [someone5678]
* d0bcad9  sm8550-common: rootdir: Boost performance during bootup  [ghostrider-reborn]
* 860d162  sm8550-common: Panic to recovery, not bootloader  [Peter Cai]
* 252004c  sm8550-common: configs: audio: Fix mic issues in apps like WhatsApp  [markakash]
* c7fe41f  universal7885: configs: audio: Disable DRC  [roynatech2544]
* 74f3727  sm8550-common: Import missing strings/mode for display mode  [someone5678]
* e231106  sm8550-common: Move SOMC related props to pdx234  [someone5678]
* 81ac477  sm8550-common: Organize configs  [someone5678]
* cbe5b28  sm8550-common: props: Drop Dolby props  [someone5678]
* 942a01c  sm8550-common: Include dtbo in recovery image  [LuK1337]
* 2c47377  sm8550-common: blobs: Move pinned blobs to below  [someone5678]
* 7568f76  sm8550-common: BoardConfig: vintf: Use += instead of := for inclusion  [someone5678]
* f32fe25  sm8550-common: overlay: Update from XperiaLabs pdx234 tree  [someone5678]
* 83aba64  sm8550-common: props: Remove debug.sf.enable_hwc_vds from vendor  [someone5678]

#### hardware/sony

* dfcfc12  XperiaDisplay: Introduce X-Reality Engine  [saku-bruh]

#### packages/apps/Settings

* 9754818  Settings: display: Sync X-Reality Engine summary to hardware/sony  [someone5678]

#### vendor/aosp

* b630487  config: Indent BoardConfig makefiles  [Bruno Martins]
* 6335a43f  vendor: optimisation: Move to system_ext for EGL Blobcache configuration  [someone5678]
* 2788c85  vendor: props: Sync suspend properties to gs201  [someone5678]
* b83bb3f  vendor: Enable watchdog timeout loop breaker  [someone5678]
* 368feb0  vendor: Use HintManager for HWUI  [Vaisakh Murali]
* 4e0e254  vendor: optimisation: Diasble shutdown timeout by default  [someone5678]
* 07c0f58  vendor: Enable zygote critical window  [Woody Lin]
* 3d9abd83  vendor: properties: Disable Async MTE on System Server  [Vinay Verma]
* a1e26b6  vendor: props: disable phantom process monitoring  [Lucchetto]
* 93e3ee7  vendor: optimisation: Disable Scudo to save ram  [someone5678]
* d3229c1  config: Reduce /product minimal reserved size  [razorloves]

#### vendor/google/gms

* 3e7dd34  gms: device_config: Remove duplicated config  [someone5678]

#### vendor/microsoft/mms

* b9b8dc7  microsoft: Add Microsoft's public RSA APK signature  [someone5678]

#### vendor/sony/sm8550-common

* 64df55a  sm8550-common: Build and import more display components  [someone5678]

### 06-07-2024

#### bootable/recovery

* 707e761  fixup! recovery_utils: add support for unmounting entire volumes  [LuK1337]
* 3c88d80  updater: Support loading dynamic partition metadata from OTA  [Yumi Yukimura]
* d874cca  recovery_ui: Respect margin_height while drawing battery capacity status  [Chippa-a]
* d14d147  minui: Import graphics_drm fix from QSSI 13  [Yuan Si]
* e975d2c  volume_manager: Remove libdiskconfig dependency  [Michael Bestas]
* a424576  recovery_ui: Bump to android.hardware.health-V3-ndk  [Michael Bestas]
* 0a1556f  recovery_ui: Retry for getting battery info  [Luofan Chen]
* 9f09a24  fixup! recovery_ui: Add support for battery capacity status  [Aaron Kling]
* 920841a  recovery_ui: Add support for battery capacity status  [Chippa-a]
* ada67e7  fixup! recovery: add the option to choose the filesystem for /data  [someone5678]
* fd8169f  recovery: Update logo after going back to recovery  [LuK1337]
* e5290a1  install: Keep all spaces in "ui_print"  [TH779]
* 7bbdd2c  recovery: rewrite slot switch logic using bootcontrol APIs  [Anay Wadhera]
* ddde7bf  recovery: add support for changing slots  [Ethan Yonker]

#### device/parasite/sepolicy

* bc8678e  parasite: sepolicy: Conditionally add PhoneLink policies  [someone5678]
* 25c89dd  The sepolicy update for phone link  [Arthur Shuai]

#### lineage/scripts

* 622b06d  build-webview: Update default webview to 125.0.6422.165  [Kevin F. Haggerty]

#### packages/apps/BtHelper

* f16f4ca  BtHelper: Fix chevron icon color in light theme  [someone5678]
* f14961a  BtHelper: Match settings_title and more_settings_title  [someone5678]

#### packages/apps/Settings

* 1c6bbf0  display: Introduce X-Reality Engine display mode [2/2]  [minaripenguin]
* f091866  Settings: Add color mode category  [someone5678]

#### vendor/aosp

* f92a28e  vendor: Sync apns-conf to LineageOS  [someone5678]
* 629a8ea  vendor: Correctly add project specific sepolicy rules  [someone5678]

#### vendor/microsoft/mms

* eee2db1  microsoft: Intial platform signature setup  [someone5678]

