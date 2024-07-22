# pdx234

### 07-22-2024

#### frameworks/base

* 86b5bc1  base: Fix gamespace on secondary users  [Dhina17]
* 1f108ea  base: Fix NPE in GameManagerService  [Dhina17]
* 2ecc9b4  GameManagerService: Prevent multiple threads from accessing settings observer onChange  [minaripenguin]
* bfa3e28  GameManagerService: Set device_config property on behalf of GameSpace  [Dhina17]
* f8b9a57  SystemUI: Add support for GameSpace  [Nauval Rizky]
* e0e5011  base: add API for disabling gestural navigation  [ezio84]
* 0ed6c0b  Fix UDFPS icon and progress while enrolling  [Tobias Merkel]
* 7110c53  Fix pipe fds leak in copyInternalSpliceSocket  [hangl]
* 933ed60  base: PhoneLink: Catch DeadObjectException  [someone5678]
* 13c4b79  [SQUASH] services: Boost gesture flings  [minaripenguin37]
* 173bb49  display: Don't reset brightness adjustment on clearUserDataPoints()  [LibXZR]
* 82f0854  PointerIcon: Add leniency to hotspot validation for scaled icons  [Prabir Pradhan]
* ecf60e3  CameraManager: Fix NPE in getting cameraIds  [afterallafk]
* 5bf4616  SystemUI: IslandView: Use status bar height as top margin  [minaripenguin]
* 7690a65  fixup! SystemUI: Integrate Google Lens into Screenshot UI  [someone5678]
* ad8a79c  fixup! SystemUI: Allow using 4G icon instead of LTE [1/2]  [someone5678]
* d7b5473  BluetoothDialog: Fix theme context  [Pranav Vashi]
* d911384  SystemUI: Allow skipping mirroring confirmation dialog [1/2]  [Sebastiano Barezzi]
* 7691415  SystemUI: Disable FaceUnlock Lockouts [1/2]  [minaripenguin]
* cfc2c47  fwb: Add missing android.permission.REGISTER_STATS_PULL_ATOM launcher3 permission  [karthik1896]
* ffc96bf  Camera: Prevent crash with prebuilt camera metadata  [Pranav Vashi]
* ac4cddf  keylayouts: Nintendo ProCon: Map it like stock does  [Nolen Johnson]
* e6eeda3  LensScreenshotReceiver: Return when failed to start activity  [someone5678]
* 55247bf  Import certification changes  [someone5678]
* c102365  Camera: Clearing exception for Extended Face  [Sauhard Pande]
* 20be412  camera: Allow selected camera apps to skip unconfigure  [LuK1337]
* e65b9a3  Guard in short-circuit evaluations for stringSplit methods.  [Mohammed Irfan]
* 5d93ac3  Camera: Don't crash when trying to disable shutter sound  [jhenrique09]
* 306e2e7  Camera: Add feature extensions  [Sauhard Pande]
* 3819c72  Fix Photosphere/Camera FCs  [Jostein Kjønigsen]
* 486ea70  Allow sending vendor- or device-specific commands to the camera HAL.  [Danny Baumann]
* e3cd7b2  Camera: Expose aux camera if packagename is null  [wbs306]
* 4ee1d417  CameraDeviceImpl: Don't crash when checking input configuration failed  [Xayah]
* a172a11  CameraManager: Prevent out of bounds when extracting camera IDs  [minaripenguin]
* 6844a82  Camera: Extend face detection  [Shuzhen Wang]
* 1928b9a  base: Allow disabling slider haptic feedbacks [1/2]  [Ido Ben-Hur]
* fac051c  SystemUI: Correctly monet theme the new volume panel  [Ido Ben-Hur]
* 857e434  SystemUI: KeyguardUnlockAnimationController: Catch all exception  [someone5678]
* 7059d25  Squash of SystemUI: Show bluetooth battery level  [LuK1337]
* 1b7d297  core: jni: Add backwards compat methods for QCOM WFD  [LuK1337]
* 81d6e0b  WiredAccessoryManager: replace every non digit character  [Francesco "Dil3mm4" Manzo]
* 8cd7270  SystemUI: Fix build after recording changes  [someone5678]
* 8907f32  code: ConfigurationController: Prevent an NPE  [minaripenguin]
* 81214fd  [TMP] base: Don't ignore PhoneLink's call on calledWithValidTokenLocked  [someone5678]
* 6b6ab08  base: Add hide annotation to all Device Integration components  [someone5678]
* 52aaf2f  PackageManager: Add platform sig arr for MS system apps  [someone5678]
* 212b56a  services: Introduce X-reality display engine mode [1/2]  [minaripenguin]
* 5c7eda5  Add keylayout for Xbox Wireless Controller  [Akshay Tigga]
* 7bfe6eb  SystemUI: screenshot: Catch RejectedExecutionException  [someone5678]
* db5aae7  base: Make device integration disable/enable through props  [someone5678]
* b0a8114  base: Enable device integration  [Omkar Chandorkar]
* aafda41  base: add support of the Phone Link  [Arthur Shuai]
* 3ef1ea2a  SystemUI: Add null check for wakelock in KeyguardViewMediator  [Pranav Vashi]
* 1eeb929  SystemUI: Prevent OOB when reinflating QS panel with notifications  [minaripenguin]
* 8a1344f  SystemUI: Prevent systemui crash when reinflating QS  [minaripenguin]
* 9c4e0c8  SystemUI: customization: Avoid NPE in ClockRegistry  [someone5678]
* 4ffd431  SystemUI: tuner: Set profile to be primary profile only  [someone5678]
* d6738ca  WindowDecor: Pass correct displayId for back key event  [Dhina17]
* d024860  SystemUI: Ignore R8 optimizations warnings  [minaripenguin]
* f7b9aa6  SystemUI: Do not shrink resources  [minaripenguin]
* 579a0b52  ExternalStorageProvider: Conditionally remove SAF restrictions [1/2]  [Richard Raya]
* 0b620d6  JobSchedulerService:fix arrayIndexOutOfBoundsException to aviod systemServer crash.  [lijilou]
* 8144072  Vibrator: Force to return a non-zero duration  [flakeforever]
* 4839c1af  Fix NPE when traversing viewgroup display list  [minaripenguin]
* 4a4b62e  BatteryStatsImpl: Guard against OOB  [Ido Ben-Hur]
* a03cd59  core: Broadcast intent when display power state changes  [Adithya R]
* 05a7ab6  Allow signature spoofing for microG Companion/Services  [LuK1337]
* 44d510d  SystemUI: Add FingerprintInteractiveToAuthProvider implementation  [Adithya R]
* 6ad74fc  SettingsLib: Use framework resource for headline font  [Adithya R]
* 38517bf  SystemUI: Fix lottie malformed json crashes  [minaripenguin]
* 582d6b5  EdgeBackGestureHandler: Change back gesture height intervals  [Anushek Prasal]
* bd40133  base: Allow to hide screen capture status from apps [1/2]  [someone5678]
* a39212a  BrightnessController: Update icon state for auto bg icon  [yukiscape]
* 1fd8945  ActivityManagerNative: Prevent possible soft-reboot  [fusionjack]
* cb83511  SystemUI: IslandView: Update color implementation  [Pranav Vashi]
* 237391d  SystemUI: IslandView: Auto remove now playing notification  [Pranav Vashi]
* 92c502a  SystemUI: IslandView: Properly handle island notification on track change  [Pranav Vashi]
* df75ecb  Revert "Remove dependency on IME subtype from TSMS"  [Michael Bestas]
* ca5130d  Allow lid to send a generic COVER_CHANGED broadcast  [jrior001]
* 7592735  SystemUI: add FloatingRotationButton for hw-key devices  [Michal Pražák]
* 1eb87d4  BatteryMeterView: Hide icon on battery-less devices  [Bruno Martins]
* d71df0d  Don't skip theme application if it's already current  [Michael Bestas]
* e50c505  SystemUI: Clean-up IME space feature  [someone5678]
* c61b670  KeyStore: Add getApplicationContext method required for Asus Devices  [Jackeagle]
* f82d3f8  SystemUI: PowerShareTile: Clean-ups  [someone5678]
* 9746ff2  SystemUI: screenshot: add delay for long-press partial screenshot  [Pranav Vashi]
* becb098  Forward port 'Swap volume buttons' (1/3)  [nadlabak]
* 3cce6c64  SystemUI: screenshot: close QS after launching long screenshot activity  [LuK1337]
* 368916d  SystemUI: screenshot: disable magnification for partial screenshots  [Cosmin Tanislav]
* 04abf0e  SystemUI: screenshot: open long screenshot activity for partial screenshots  [Cosmin Tanislav]
* fe24f22  Implement click to take partial screenshot [1/3]  [Jesse Chan]
* 9dfe585  CameraServiceProxy: fix exception  [Dmitrii]
* 6c69a50  Fix "Manage App & Content access" for profiles  [Tommy Webb]
* 1b6d2ae  Keyguard: Hide battery indication on battery-less devices  [Bruno Martins]
* 23ccd31  SettingsLib: Update 5G+ icon to Silk design  [Adithya R]
* 3d4844b  SettingsLib: Update 4G+ icon to Silk design as well  [TH779]
* 9b821c0  SettingsLib: Update LTE+ icon as per new Silk design  [Adithya]
* 79b34fe  PackageManager: Add separated vendor platform signatures for GMS  [someone5678]
* 08e519c  PackageManager: Allow device to specify vendor platform signatures  [Ethan Chen]
* 621a700  Island: Fix some album-art not showing  [Subratam6296]
* 38642f2  base: SystemUI: Add Black theme [1/3]  [SagarMakhar]
* 142e30e  Fix NPE in SystemUI  [first last]
* 15138b7  Textutils: Optimize writeToParcel performance  [minaripenguin]
* 0dfce98  SettingsLib: Fix crash when checking emergency gesture state  [minaripenguin]
* e25fb1a  Island: Resolve notification contents  [minaripenguin]
* 02b9f18  UpdateEngine: Add perf mode binder interface  [Luca Stefani]
* 39ba7c5  SystemUI: Disable dagger.fastInit option  [someone5678]
* fc6f554  Integrate Pixel framework hooks and wrappers  [minaripenguin]
* 09b1b8d  SystemUI: Introduce wifi standard icon feature [1/2]  [minaripenguin]
* 1a81917  CarrierConfig: allow toggling VoWiFi while roaming by default  [r3g_5z]
* 29d6f4a  SystemUI: biometrics: Follow user setting to confirm face unlock  [Pranav Vashi]
* 8396f6b  base: make per-app work with multi audio focus  [El Dainosor]
* 2458658  SystemUI: Use proper tint for face unlock icon  [Pranav Vashi]
* 4a28206  SystemUI: FaceUnlock: Add margin based on lock icon  [someone5678]
* 447c191  SystemUI: Implement face unlock recognition animation and text  [minaripenguin]
* d1f1d0c  SystemUI: Follow monet theme on privacy indicators  [minaripenguin]
* 949b642  base: PhantomProcessList: Correctly handle orphan procs  [Ido Ben-Hur]
* 4b91e24  base: Disable haptic feedback on scrolling correctly  [someone5678]
* d2b80563  BootAnimation: Check persist.sys.boot.theme instead  [someone5678]
* f652d2b  SystemUI: Correctly disable double tap to sleep gesture by default  [someone5678]
* 74141d1  core: BatteryManager: Add few more Battery broadcast intents  [Jyotiraditya Panda]
* d382919  SystemUI: Launch hotspot settings on long click instead of click  [someone5678]
* aaddf88  SystemUI: Adapt "Extend kill button to notification conversation guts" to A14 QPR2  [someone5678]
* fb4f4e6  Settings: Always show package name in installed app details  [Michael Bestas]
* b30de89  [TMP] base: Don't append app name to App Clips screenshot for now  [someone5678]
* 8c99013  SystemUI: tuner: Migrate MainSwitchBar and Switch to Material3  [Bruno Martins]
* 803f752  SystemuUI: tuner: migrate to SwitchPreferenceCompat  [aswin7469]
* b0899dd3  SystemUI: Tuner: Move to SwitchPreferenceCompat  [someone5678]
* a238907  SystemUI: New per-app volume icon  [ReallySnow]
* 5153000  Island: Improve text filtering to support symbols  [minaripenguin]
* 160a922  Island: Do not show now playing on keyguard and dozing state  [minaripenguin]
* 22fbb13  IslandView: Fix and improve notification regex filtering  [minaripenguin]
* 2ba6d18  IslandView: Ensure global headsup is enabled  [Pranav Vashi]
* 8c57cfc  Island: Return if sbn.notification.contentIntent is NULL  [someone5678]
* 43ae676  Island: Get application info from all user  [someone5678]
* ab82839  Island: Import SystemUIToast icon retrieving logic  [someone5678]
* 12b3567  Island: Squeeze it  [someone5678]
* b9bc363  SystemUI: Implement Island notification feature [1/2]  [minaripenguin]
* fd2134a  base: support per-app volume [2/3]  [cjybyjk]
* d11e05e  SystemUI: Add haptics to brightness slider [1/2]  [Vaisakh Murali]
* 5cc54da  base: Allow toggling floating rotation button [1/2]  [Ido Ben-Hur]
* 2a46ce7  SystemUI: Cleanup screenshot sound/vibration logic  [Adithya R]
* 00bcded  SystemUI: Adapt screenshot sound to ringer modes  [Ashwin R C]
* 4c83e8e  base: core: Unregister broadcast receiver only when registered  [Soo-Hwan Na]
* 13ee718  core: Gracefully handle unregistering of unregistered receivers/services  [minaripenguin]
* 4a2f929  Fix uninstall for all users  [Tommy Webb]
* 77ebab0  SettingsLib: Make all user apps cloneable [1/2]  [Jyotiraditya Panda]
* 55e79d5  charging: Allow using vibration without sounds  [xyyx]
* bd3de46  base: Add support for disabling fingerprint lockout [1/2]  [SamarV-121]
* 5b0fdc2  CustomUtils: Refactor isPackageInstalled method  [Pranav Vashi]
* 4ef02c14  services: Disable automatic system server heap dumps by default  [minaripenguin]
* 3be4b71  CEC: correct frameworks physicalAddress parsing  [Thomas Makin]
* cd09fe8  base: Add support for strict standby policy [SQUASH]  [LibXZR]
* dbac016  SystemUI: Allow ignoring IWlan status in the mobile icon pipeline  [Tommaso Fonda]
* 4589471  Gesture nav: Add back menu action  [someone5678]
* 7df8f11  Gesture nav: Add go forward action  [someone5678]
* fb94c4e  Gestures nav: Make it cancelable  [someone5678]
* 70e4cc4  Gestures nav: Add back show recents action  [someone5678]
* fee521a  SystemUI: BackPanel: Always add second arrow in front on long swipe  [someone5678]
* 4a642a9  SystemUI: navigationbar: Flip canvas if gesture started from left  [someone5678]
* 3adfe16  Gestures nav: Add Partial Screenshot action  [spezi77]
* e164078  Gestures nav: Add Power menu action  [kdrag0n]
* 9438bcf  Show a double arrow when almost triggered in new back affordance as well  [DennySPb]
* c11c92a  [SQUASH] Advanced navigation "extended/L" gestures  [ezio84]
* cb623d4  [SQUASH] Utils: Actions for advanced navigation gestures  [ezio84]
* 0982d36  base: Add api to take screenshots  [bigrushdog]
* d15987a  Utils: Add method to turn off the screen  [ezio84]
* fa02572  Utils: Reverse actions for QS and notification panel  [ezio84]
* db5de9b  Add api to get or kill foreground app  [ezio84]
* 008f138  Add a sendKeycode api to Utils  [ezio84]
* af0b9ff  Add api to toggle flashlight and check if device has flashlight  [ezio84]
* dac30e1  Utils: Add isAvailableApp method  [maxwen]
* b6851020  UI: Follow Monet and light/dark theme in user 1 icon  [Andy CrossGate Yan]
* e190450  Fix screen flickering when using one handed mode  [timjosten]
* 74e2396  SystemUI: Fix double unlock sound issue  [timjosten]
* 96823e6  base: Use Context instead of Application for *PropsUtils [2/2]  [someone5678]
* e8198e9  Add 5G Ultra Wideband icon carrier config keys  [Vala Zadeh]
* 8e08b71  TelephonyManager: Add getLteOnCdmaMode() function for default subId  [Ido Ben-Hur]
* 59a44dc  telephony: Add ICCID into CarrierIdentifier  [Mengjun Leng]
* cf18fab  base: Spoof current storage encryption status [1/2]  [someone5678]
* 6d088bd  core: Allow telephony stack and its components to receive un-sanitized ServiceState entries  [minaripenguin]
* 3665fa7  Skip checking SystemUI's permission for observing sensor privacy  [Han Wang]

#### hardware/sony

* 7e712f9  fixup! XperiaParts: Don't setup display HAL on boot if setting is disabled  [someone5678]

#### manifest

* 7402e41  manifest: parasite: Track GameSpace  [someone5678]

#### packages/apps/GameSpace

* 5a1842d  GameSpace: Import qs_tile_background ripple resource for tile  [someone5678]
* c896758  GameSpace: Split app name and settings title  [someone5678]
* dfccd9b  GameSpace: Add Google Game Dashboard shortcut  [someone5678]
* 69d71cc  GameSpace: Move game library to its own preference  [someone5678]
* 29d6845  GameSpace: Migrate MainSwitchBar and Switch to Material3  [Bruno Martins]
* 9924548  GameSpace: Rename title to Game Mode  [someone5678]
* e53d73c  GameSpace: Add meta-data for Settings entry  [someone5678]
* 76f2af3  GameSpace: Enable enableOnBackInvokedCallback  [someone5678]
* d656b9c  GameSpace: Hide from launcher  [someone5678]
* 4e9fb68  GameSpace: Fix stopping session service in secondary users  [Dhina17]
* d926563  GameSpace: Update fps once menu switcher attached to window  [Dhina17]
* db0d027  GameSpace: Skip starting game bar if already connected  [Pranav Vashi]
* 8343387  GameSpace: Update gson prebuilt namespace to gson-prebuilt-jar-2.9.1  [minaripenguin]
* 931a0c8  GameSpace: Fix up cast error for list preference  [Pranav Vashi]
* 2000558  GameSpace: Update preferences to meet latest spec  [Pranav Vashi]
* 16dafd6  GameSpace: Fix A14 QPR2 compile issues  [Pranav Vashi]
* a5a8895  GameSpace: Update icon - Change background color - Add monochrome icon support - Remove unused background drawable  [mukesh22584]
* 37e4d14  GameSpace: Expose icon in launcher  [cjh1249131356]

#### packages/apps/ParanoidSense

* 3f08d0e  ParanoidSense: Update app name to "Face Unlock Service"  [someone5678]

#### packages/apps/Settings

* f54004f  Settings: Move to lowercase of "Apps" in Cloned Apps title  [someone5678]
* 96e7b72  Revert "Settings: Add Game Settings page"  [someone5678]
* 8b5d1b2  fixup! Settings: Add status bar lyric [2/2]  [someone5678]

#### packages/providers/TelephonyProvider

* fa2b57f  TelephonyProvider: Fix exception regarding SIM info tables  [flakeforever]

#### vendor/aosp

* fd54f67  apns: Fix broken entries  [Sebastiano Barezzi]
* d8f59b1  vendor: apps: Build Game Space  [someone5678]
* a05ad9d  overlay: wifionly: Mark as WiFi-only  [Tim Zimmermann]
* 61e6c78  overlay: wifionly: Set network and radio attributes  [Bruno Martins]

#### vendor/google/gms

* 86f4a4c  gms: Import PixelUdfpsOverlay  [someone5678]
* 1814347  gms: Import UdfpsOverlay  [someone5678]

#### vendor/google/pixel-additional

* dcbe05f  TurboAdapter_NoBatt: Add logging  [someone5678]
* 0965c19  TurboAdapter_NoBatt: Return dummy bundle  [someone5678]

#### vendor/google/pixel-framework

* 6a2557a  base: add API for disabling gestural navigation [2/1]  [someone5678]

#### vendor/sony/extra

* 66507ec  GamingAccessorySettingsCustom: Redirect to Game Space  [someone5678]

### 07-21-2024

#### device/sony/sm8550-common

* 45d1cef  sm8550-common: Use QTI usb_compositions.conf  [someone5678]

#### hardware/sony

* 7354cf4  sepolicy: Remove duplicated wakeup nodes  [kyasu]
* 9468922  XperiaModules: Enable enableOnBackInvokedCallback  [someone5678]

#### packages/apps/Settings

* 8a6c390  Setting: batteryinfo: Add config_show_battery_design_capacity & show_battery_maximum_capacity  [Asriadi Rahim]

#### vendor/google/pixel-additional

* dc76906  pixel-additional: TurboAdapter_NoBatt: Update  [someone5678]
* 2dd2103  pixel-additional: Add CleanSpec for TurboAdapter_NoBatt  [someone5678]

#### vendor/microsoft/mms

* afa9913  mms: Allow PhoneLink to access hidden api  [someone5678]

#### vendor/sony/extra

* cc65989  extra: Enable enableOnBackInvokedCallback  [someone5678]

### 07-20-2024

#### bootable/recovery

* 3620807  minui: Support secondary framebuffers  [Aaron Kling]
* 322e90c  recovery_ui: Retry for getting battery info  [Luofan Chen]
* 34f1b6c  recovery: allow formatting & mounting system on user builds  [Joker-V2]
* 3a7ef89  fixup! recovery: add the option to choose the filesystem for /data  [someone5678]
* 9e6af8a  fixup! recovery: touch UI  [someone5678]
* bdf1e6f  Add e2fsck/resize2fs/tune2fs to recovery  [Michael Bestas]
* 5ccf44e  recovery: rewrite slot switch logic using bootcontrol APIs  [Anay Wadhera]
* 9638cc4  recovery: add support for changing slots  [Ethan Yonker]
* c20d621  recovery: display current filesystem when going to format  [Anay Wadhera]
* 6f9501b  recovery: add the option to choose the filesystem for /data  [Anay Wadhera]
* 5b8765a  recovery: Skip verifying packages altogether  [Pranav Vashi]
* e633695  recovery: Make recovery usable on user builds  [Christian Oder]
* ed7f8e9  recovery: allow A/B updater to downgrade  [Alessandro Astone]
* e00d612  recovery: Allow bypassing signature verification on non-release builds  [Tom Marshall]
* b60fe00  updater: Support loading dynamic partition metadata from OTA  [Yumi Yukimura]
* 5f19517  recovery_ui: Respect margin_height while drawing battery capacity status  [Chippa-a]

#### device/sony/pdx234

* 4f61ec4  pdx234: Update  [someone5678]

#### hardware/interfaces

* c6aaaaf  Partial revert "Remove mapper from composer2.1 VTS"  [Aaron Kling]

#### kernel/sony/sm8550

* 0e07723  configs: sony: Enable Kallsyms  [someone5678]
* 21f7378  drivers: qcom: Make CONFIG_QCOM_SOC_SLEEP_STATS_ON_SYSFS depend on DEBUGFS  [Luofan Chen]
* 6b88ceb  Makefile.lib: Lower kernel gzip compression to fastest  [Angelo G. Del Regno]
* 138ddac  configs: sony: Enable ZRAM writeback  [Luofan Chen]
* f6cf23c  arch: configs: sony: Disable CONFIG_QCOM_SOC_SLEEP_STATS_ON_SYSFS  [Luofan Chen]
* ebff62a  configs: Move sony specific config to its fragment  [Luofan Chen]
* fb0572c  sony: config: Use 1M for kernel log  [Juhyung Park]
* d0a8ad2  sony: config: Disable most of the debugging configs  [Pranav Vashi]
* 9ac81a5  sony: config: Disable wcd-usbss  [Bruno Martins]
* e511633  sony: config: Unset all configs related with crow chipset  [Bruno Martins]
* ee0f264  power: Import wakeup_irq_debug driver  [Luofan Chen]
* bdfab60  ARM64: dts: vendor: Add symlink to sm8550-devicetrees  [Bruno Martins]
* 229e00b  et6xx: Align implementation in sm8550  [Luofan Chen]
* cf6623c  et6xx: Remove reference to hardware_info  [Luofan Chen]
* 7f421d5  drivers: sony: Import et6xx driver from 68.0.A.0.768  [Luofan Chen]
* 061e33e  drivers: Import sony drivers to build inline  [Luofan Chen]
* d0df062  tools/resolve_btfids: Skip unresolved symbol warning for empty BTF sets  [Kumar Kartikeya Dwivedi]
* 463fefd  minimal sony changes  [Luofan Chen]
* f10b0ab  fixup! Merge tag 'KERNEL.PLATFORM.2.0.r1-17900-kernel.0' of https://git.codelinaro.org/clo/la/kernel/msm-5.15 into HEAD  [chaptsand]

#### packages/apps/Updater

* a005d09  Updater: Append trailing slash to upgrade url  [Michael W]

#### vendor/aosp

* bf4c3f7  vendor: Move ro.storage_manager.enabled to gms  [someone5678]
* a9a7a99  vendor: Adapt foldable book config to this project  [someone5678]
* 77ee3a5  config: Add common config for book-style foldables  [Jens Reidel]
* c9af309  apns: Order properly  [Michael W]
* 2a0017a  apns: Fix invalid entries for WOM (chile)  [Michael W]
* ec378f0  ADD APN for DIGI Spain IMS and DIGI Italy IMS  [armando.maya]
* bb6ccec  apns: Move Hits  [Michael W]
* 7cb9077  apns: Add 4ka SK  [Michael W]
* 23f8fe4  apn: Add VTB Mobile  [Andrey Sprynga]
* ff3e916  apn: Add Tinkoff Mobile  [Andrey Sprynga]
* b0efec6  apn: Add SberMobile  [Andrey Sprynga]
* 5aac9d3  apn: Add GPB Mobile  [Andrey Sprynga]
* face4b8  aconfig: DeviceAsWebcam: Enable high quality toggle  [someone5678]
* 1e8aa95  aconfig: SystemUI: Disable Faster wallpaper unlock transition  [someone5678]
* afd0e1f  apns: Update Claro Ecuador APN  [0xSoul]
* 185a0e8  vendor: prebuilt: Add cache cleaner script [1/2]  [someone5678]
* b0d7cf6  vendor: art: Conditionally enable 64Bit dex2oat  [someone5678]
* b5c239f  aospa: Optimize dex2oat for cortex-a76 on cortex-a510  [Jake Weinstein]
* 0ae6404  aconfig: Enable volume slider haptic feedbacks  [someone5678]
* 2b2b84a  Revert "vendor: Move out aconfig to top of repo"  [someone5678]
* 888280a  vendor: aconfig: Enable Notification Cooldown  [someone5678]
* 5f997d1  vendor: props: Disable SystemUIDialog volume panel  [someone5678]
* 79c50a2  vendor: overlay: Move back res to non-RRO which uses Resources.getSystem()  [someone5678]
* e0f0f4e  vendor: art: Unset FULL_SYSTEM_OPTIMIZE_JAVA  [someone5678]
* 1ef4605  kernel: use systemimage_intermediates on devices with no vendor  [Han Sol Jin]
* 0b59ffb  kernel: Better x86 support  [Sebastiano Barezzi]
* f331a7a  kernel: Add kernel modules to partition file list  [Aaron Kling]
* 6b3540a  apns: Update Telia Finland APNs  [JH]
* 04d3376  factory: zygote and rescue party properties  [Ryan Chu]
* 45a4f6c  vendor: Move art related configs  [someone5678]
* f7e1099  extra: configs: Do not include other java mini debug info  [Yurical]
* 95bd315  vendor: Move persist.vendor.recovery_update to ADDITIONAL_SYSTEM_PROPERTIES  [someone5678]
* 8307d2a  overlay: Enable the app battery usage list page feature  [LuK1337]

#### vendor/google/gms

* efefee3  gms: Disable ro.storage_manager.enabled  [someone5678]
* e7fc1bc  gms: Add support for DSE search engine choice screen and EEA device features  [someone5678]

#### vendor/parasite/common

* 1138109  fixup! sensitive_pn: Update RUS numbers  [someone5678]
* 0e606e2  PixelPropsUtils: Add back HARDWARE spoofing  [someone5678]
* 9d970c2  fixup! sensitive_pn: Update RUS numbers  [LuK1337]
* 4cdb3b3  sensitive_pn: Update RUS numbers  [Andrey Sprynga]

#### vendor/parasite/signatures

* 7f9baaf  signatures: Generate NFC apex keys  [someone5678]
* 8a1c28d  keys: Include custom releasekey in recovery  [Tom Powell]

#### vendor/sony/pdx234

* 395c177  pdx234: Update  [someone5678]

#### vendor/sony/sm8550-common

* ed57b5d  sm8550-common: Update  [someone5678]

### 07-19-2024

#### device/parasite/sepolicy

* d0f8d1f  parasite: sepolicy: Add cache cleaner script [2/2]  [someone5678]

#### device/sony/sm8550-common

* 32c9dd3  sm8550-common: Use soong_config_set to set sony powershare variable  [Arian]

#### manifest

* 0ba7576  Revert "manifest: Track DeviceAsWebcam"  [someone5678]

### 07-18-2024

#### build/make

* f16ce9a  config: Allow overriding dex2oat CPU variant  [Adithya R]
* 6187bc3  core: set pkg target files deflate level to 1  [Simão Gomes Viana]
* 96ba22c  releasetools: Pass non-sparse super_empty.img to update_dynamic_partitions()  [Yumi Yukimura]
* 6e2367a  make: sysprop.mk: Treat dev-keys as release-keys  [Ido Ben-Hur]
* 46db7e6  build: Use custom brand prop when add project banner  [someone5678]
* f9dc8bf  build: Generify custom project info props  [someone5678]
* d2d85b1  make: envsetup: Always use latest release for lunch  [Ido Ben-Hur]
* 93f6388  Remove non existent snapuserd.recovery package  [Michael Bestas]
* 07c2e1d  build: core: Add support for setting additional options when building ota  [someone5678]
* d6b1021  fixup! Correct logic for obtaining the path to full recovery image  [Luca Stefani]
* f97d8f4  releasetools: Make recovery patch use bsdiff exclusively  [Gérard Parat]
* d5b8cb1  Allow installing fake [odm|product|system_ext] packages  [Alexander Koskovich]
* 4122347  fixup! Support generating partial OTAs from extracted target_files  [Chirayu Desai]
* 40db567  Correct logic for obtaining the path to full recovery image  [Ricky Cheung]
* 29684a6  releasetools: Fix building new recovery patch on vendor  [Gérard Parat]
* 3dc9ff2  No more lies  [Chirayu Desai]
* 0ec5b1a  releasetools: Resolve symlinks in IsEntryOtaPackage()  [LuK1337]
* d3d7b2b  releasetools: check_partition_sizes: Allow non-A/B RDAP  [Yumi Yukimura]
* 715ac58  build: Enable super image build rules depending on single super block device  [Yumi Yukimura]
* 002fe41  releasetools: build_super_image: Do not set readonly attr  [Yumi Yukimura]
* a94531e  envsetup: Source vendorsetups after running roomservice in lunch  [Beru Hinode]
* b00876f  build: envsetup.sh: Always get CUSTOM_BUILD  [someone5678]
* 9111160  Remove WallpaperPicker from aosp_product.mk  [Michael Bestas]
* 18599fd  Remove android.hardware.wifi from generic_system.mk  [Michael Bestas]
* ed528e2  fixup! build: Add phony package to build enforce RRO packages  [Yumi Yukimura]
* 2bd0fb8  fixup! build: Add support for device tree in boot.img  [LuK1337]
* 992eef7  fixup! core: Allow overriding device/model/name properties  [Michael Bestas]
* 0fcb812  build: Adapt backuptool support commit to this project  [someone5678]
* f23a7a0  build: Fix LEX mismatch on Gentoo Linux  [HyperN00B]
* a0d97cd  envsetup.sh: cleanup ccache echo  [Lup Gabriel]
* 34f2b20  envsetup: Fix indentation in ccache code snippet  [Pranav Vashi]
* 6072f48  envsetup: export the CCACHE_DIR if its not set  [Daniel Moral]
* 8e1de11  envsetup: Prefer setting ccache compress as command line parameter  [ganeshi4u]
* 58f35ee  Automatically set CCACHE_EXEC to the system's ccache  [ganeshi4u]
* 79a2480  combo: Add kryo585|785 architectures to known v8-2a cores  [minarypenguin]
* 5a630af  combo: Add kryo585 architecture to known v8 cores  [johnmart19]
* 71d161c  build: copy files to zip from $OUT/install as well  [Chenyang Zhong]
* 2569148c  copy files to zip from system  [TheScarastic]
* fd8f60e  releasetools: Don't compress with brotli  [Alexander Winkowski]
* 1dcc4af  Revert "Remove unused $MD5SUM."  [kubersharma001]
* 011ed4c  envsetup: Fixup mka for R  [ganeshi4u]
* adf305b  Add mka alias  [xplodwild]
* 774b241  build: target: Move TeleService to telephony_system.mk  [roynatech2544]
* 0c7c31a  Remove ro.kernel.android.checkjni  [Chet Kener]
* d1214c3  Makefile: Dont include tasks from testing repos  [maxwen]
* 74e1440  All operating systems are beautiful  [Christopher N. Hesse]
* f2d3972  Use SOONG_ZIP for all zip usages  [Simao Gomes Viana]

#### device/sony/extra

* 846e1e9  extra: extract-files.sh: Do not run xmlstarlet background  [someone5678]
* aaa0328  extra: Set execution perm to update-sha1sums.py  [someone5678]

#### manifest

* a57f699  manifest: parasite: Move ThemeIcons under vendor/google  [someone5678]

#### vendor/certification

* f77f00b  certification: Disable keybox support by default  [someone5678]

#### vendor/google/gms

* d35e23a  gms: Move ThemeIcons under vendor/google  [someone5678]

#### vendor/google/overlays/ThemeIcons

* 533ca78  ThemeIcons: Move under vendor/google  [someone5678]

#### vendor/parasite/common

* d839bf5  sensitive_pn: Add and modify netherland numbers  [Japie3krekel]
* 9afffd7  Helplines: Update and simplify helplines for multiple countries.  [Alexander K]

