# pdx234

### 06-03-2024

#### frameworks/base

* c6268dc  TelephonyManager: Gracefully handle null telephony service [2]  [minaripenguin]

#### kernel/sony/sm8550

* 46dc001  configs: pdx234: Build KProfiles as LKM  [someone5678]
* 69b0816  drivers: misc: Import KernelSU  [someone5678]
* be7286e  configs: pdx234: Configure KProfiles  [Mohammad Sayful Islam]
* 1d269da  configs: pdx234: Enable Kprofiles  [someone5678]
* 1308a2e  drivers: misc: Import Kprofiles  [someone5678]
* 6b867ef  drivers: qcom: Make CONFIG_QCOM_SOC_SLEEP_STATS_ON_SYSFS depend on DEBUGFS  [Luofan Chen]
* 7becf70  Makefile.lib: Lower kernel gzip compression to fastest  [Angelo G. Del Regno]
* ac145dc  configs: sony: Enable ZRAM writeback  [Luofan Chen]
* b4c706f  arch: configs: sony: Disable CONFIG_QCOM_SOC_SLEEP_STATS_ON_SYSFS  [Luofan Chen]
* a1d1741  configs: Move sony specific config to its fragment  [Luofan Chen]
* 0039d51  sony: config: Use 1M for kernel log  [Juhyung Park]
* 679b994  sony: config: Disable most of the debugging configs  [Pranav Vashi]
* 99eb6ca  sony: config: Disable wcd-usbss  [Bruno Martins]
* a5d3aa6  sony: config: Unset all configs related with crow chipset  [Bruno Martins]
* b3ee9cb  power: Import wakeup_irq_debug driver  [Luofan Chen]
* d3ccf87  ARM64: dts: vendor: Add symlink to sm8550-devicetrees  [Bruno Martins]
* e751f54  et6xx: Align implementation in sm8550  [Luofan Chen]
* 93fc73f  et6xx: Remove reference to hardware_info  [Luofan Chen]
* 98aa2b6  drivers: sony: Import et6xx driver from 68.0.A.0.768  [Luofan Chen]
* 469702a  drivers: Import sony drivers to build inline  [Luofan Chen]
* 30b40dd  tools/resolve_btfids: Skip unresolved symbol warning for empty BTF sets  [Kumar Kartikeya Dwivedi]
* f8ca1fe  minimal sony changes  [Luofan Chen]

#### packages/apps/Aperture

* aac5e1c  Automatic translation import  [LineageOS Infra]

#### packages/apps/Updater

* d614744  Automatic translation import  [LineageOS Infra]
* 38cc977  Updater: Handle ErrorCode::kUpdateAlreadyInstalled more gracefully  [LuK1337]

#### vendor/parasite

* 6c987cc  PixelPropsUtils: Spoof Photos even if util is disabled  [someone5678]

#### vendor/parasite-prebuilts

* cb83454  Gramophone: Import 1.0.8  [someone5678]

#### vendor/sony/extra

* fb8fde9  GamingAccessorySettingsCustom: Redirect to Pixel Launcher  [someone5678]
* a89149f  extra: custom: Inital decomp for GamingAccessorySettings  [someone5678]
* 734d3d0  extra: Inital custom GamingAccessorySettings  [someone5678]

### 06-02-2024

#### frameworks/base

* aae1572  SystemUI: Ignore R8 optimizations warnings  [minaripenguin]
* cfd8337  SystemUI: Do not shrink resources  [minaripenguin]
* 558805d  ExternalStorageProvider: Conditionally remove SAF restrictions [1/2]  [Richard Raya]
* 27b4dd664  Wifi Standard: Optimize handling for flooding network requests  [minaripenguin]
* 7972a3f  Add Gravis GamePad Pro USB key layout  [Nathaniel Manista]
* de9d7fa  JobSchedulerService:fix arrayIndexOutOfBoundsException to aviod systemServer crash.  [lijilou]
* 7dd3341  Vibrator: Force to return a non-zero duration  [flakeforever]
* bdb1434  Reapply "Make dun APNs as read-only by default."  [ShevT]
* 9ec78b1  Fix NPE when traversing viewgroup display list  [minaripenguin]
* 454415f  BatteryStatsImpl: Guard against OOB  [Ido Ben-Hur]
* 5a77278  core: Broadcast intent when display power state changes  [Adithya R]
* 507ff5f  Allow signature spoofing for microG Companion/Services  [LuK1337]
* 6b98692  SystemUI: Add FingerprintInteractiveToAuthProvider implementation  [Adithya R]
* a04ae13  SettingsLib: Use framework resource for headline font  [Adithya R]
* e61dbd9  SystemUI: Fix lottie malformed json crashes  [minaripenguin]
* be89161  EdgeBackGestureHandler: Change back gesture height intervals  [Anushek Prasal]
* 0f98408  base: Allow to hide screen capture status from apps [1/2]  [someone5678]
* 6d7b75d  BrightnessController: Update icon state for auto bg icon  [yukiscape]
* c377f0d  ActivityManagerNative: Prevent possible soft-reboot  [fusionjack]
* 063aed6  SystemUI: IslandView: Update color implementation  [Pranav Vashi]
* a0850de  SystemUI: IslandView: Auto remove now playing notification  [Pranav Vashi]
* 5a67083  SystemUI: IslandView: Properly handle island notification on track change  [Pranav Vashi]
* d3bba17  Revert "Remove dependency on IME subtype from TSMS"  [Michael Bestas]
* 67b060c  Allow lid to send a generic COVER_CHANGED broadcast  [jrior001]
* 26dd54e  SystemUI: add FloatingRotationButton for hw-key devices  [Michal Pražák]
* 8e8d557  BatteryMeterView: Hide icon on battery-less devices  [Bruno Martins]
* 28db275  fixup! SystemUI: Make Navbar Secondary Handle Appear Correctly.  [OnlyTomInSecond]
* 3a01188  Don't skip theme application if it's already current  [Michael Bestas]
* c4bdbc0  SystemUI: theme: Clean-up and fix black theme enable  [someone5678]
* cf3b887  SystemUI: Clean-up IME space feature  [someone5678]
* 5566b27  KeyStore: Add getApplicationContext method required for Asus Devices  [Jackeagle]
* 84940a6  SystemUI: PowerShareTile: Clean-ups  [someone5678]
* 99cd47a  SystemUI: screenshot: add delay for long-press partial screenshot  [Pranav Vashi]
* bd37ea7  Forward port 'Swap volume buttons' (1/3)  [nadlabak]
* e010e1f  SystemUI: screenshot: close QS after launching long screenshot activity  [LuK1337]
* a80dbc4  SystemUI: screenshot: disable magnification for partial screenshots  [Cosmin Tanislav]
* ef0a6f0  SystemUI: screenshot: open long screenshot activity for partial screenshots  [Cosmin Tanislav]
* 435b011  Implement click to take partial screenshot [1/3]  [Jesse Chan]
* 6ebdb5b  CameraServiceProxy: fix exception  [Dmitrii]
* b1d0408  fwb: silence more spam  [Dmitrii]
* 1ae989e  Fix "Manage App & Content access" for profiles  [Tommy Webb]
* 5c85323  Keyguard: Hide battery indication on battery-less devices  [Bruno Martins]
* f8c693c  SettingsLib: Update 5G+ icon to Silk design  [Adithya R]
* b47f6d2  SettingsLib: Update 4G+ icon to Silk design as well  [TH779]
* 5d8d338  SettingsLib: Update LTE+ icon as per new Silk design  [Adithya]
* 36765f0  PackageManager: Add separated vendor platform signatures for GMS  [someone5678]
* 8ce5586  PackageManager: Allow device to specify vendor platform signatures  [Ethan Chen]
* 5037dc0  Island: Fix some album-art not showing  [Subratam6296]
* 49fd54b  Island: Use status bar height as top margin  [minaripenguin]
* d002b87  base: Fix Black theme not applied immediately  [someone5678]
* 8a9912c  base: SystemUI: Add Black theme [1/3]  [SagarMakhar]
* a10b315  Fix NPE in SystemUI  [first last]
* e4faacf  SystemUI: screenrecord: Also remember share mode selection  [Ido Ben-Hur]
* 71c1374  Textutils: Optimize writeToParcel performance  [minaripenguin]
* 2a77bea  SettingsLib: Fix crash when checking emergency gesture state  [minaripenguin]
* 75e5a42  Island: Resolve notification contents  [minaripenguin]
* de2a056  UpdateEngine: Add perf mode binder interface  [Luca Stefani]
* f2ab4c9  SystemUI: Disable dagger.fastInit option  [someone5678]
* b457056  Integrate Pixel framework hooks and wrappers  [minaripenguin]
* 7f11a52  SystemUI: Introduce wifi standard icon feature [1/2]  [minaripenguin]
* b87d973  CarrierConfig: allow toggling VoWiFi while roaming by default  [r3g_5z]
* eef76b1  SystemUI: biometrics: Follow user setting to confirm face unlock  [Pranav Vashi]
* 6ac80e8  base: make per-app work with multi audio focus  [El Dainosor]
* a4b64feb  SystemUI: Use proper tint for face unlock icon  [Pranav Vashi]
* ab63c1d  SystemUI: FaceUnlock: Add margin based on lock icon  [someone5678]
* c0e2c84  SystemUI: Implement face unlock recognition animation and text  [minaripenguin]
* 7d67169  SystemUI: Follow monet theme on privacy indicators  [minaripenguin]
* 1e7440c  base: PhantomProcessList: Correctly handle orphan procs  [Ido Ben-Hur]
* 0cbd2a3  VolumeDialogImpl: Handle cases where media controller is not available  [danielml]
* 8a6c378  base: Disable haptic feedback on scrolling correctly  [someone5678]
* 710d210  BootAnimation: Check persist.sys.boot.theme instead  [someone5678]
* 1642abe  SystemUI: Correctly disable double tap to sleep gesture by default  [someone5678]
* e9abe3c  core: BatteryManager: Add few more Battery broadcast intents  [Jyotiraditya Panda]
* ab101e2  Screenrecord: Fix notifications not being dismissed  [Ido Ben-Hur]
* d9bb4db  SystemUI: Launch hotspot settings on long click instead of click  [someone5678]
* fe772c1  Revert "Use HwLight.type as the key of mLightsByType"  [Joker-V2]
* d689a16  SystemUI: Adapt "Extend kill button to notification conversation guts" to A14 QPR2  [someone5678]
* 8f3bc29  Settings: Always show package name in installed app details  [Michael Bestas]
* 4b28318  [TMP] base: Don't append app name to App Clips screenshot for now  [someone5678]
* e65fb76  SystemUI: tuner: Migrate MainSwitchBar and Switch to Material3  [Bruno Martins]
* 4694138  FaceSense: Adapt for 14 QPR2  [aswin7469]
* 2635a39  SystemuUI: tuner: migrate to SwitchPreferenceCompat  [aswin7469]
* 84b12a2  base: Add hide annotation to all Device Integration components  [someone5678]
* 51f7373  base: Make device integration disable/enable through props  [someone5678]
* 08c32f7  SystemUI: Tuner: Move to SwitchPreferenceCompat  [someone5678]
* ec32fe2  base: Enable device integration  [Omkar Chandorkar]
* a58b0a2  base: add support of the Phone Link  [Arthur Shuai]
* 7f6780c  SystemUI: New per-app volume icon  [ReallySnow]
* cec2419  Island: Improve text filtering to support symbols  [minaripenguin]
* 3875998  Island: Do not show now playing on keyguard and dozing state  [minaripenguin]
* 33b5e5c  IslandView: Fix and improve notification regex filtering  [minaripenguin]
* 27fd1be  IslandView: Ensure global headsup is enabled  [Pranav Vashi]
* 09082b5  Island: Return if sbn.notification.contentIntent is NULL  [someone5678]
* 54204f1  Island: Get application info from all user  [someone5678]
* 6977e2c  Island: Import SystemUIToast icon retrieving logic  [someone5678]
* 49f28e3  Island: Squeeze it  [someone5678]
* 5dfc2c8  SystemUI: Implement Island notification feature [1/2]  [minaripenguin]
* 3ab8867  base: support per-app volume [2/3]  [cjybyjk]
* e5ee067  SystemUI: Add haptics to brightness slider [1/2]  [Vaisakh Murali]
* 91e440c  base: Allow toggling floating rotation button [1/2]  [Ido Ben-Hur]
* 48d11dd  SystemUI: Cleanup screenshot sound/vibration logic  [Adithya R]
* 8db4113  SystemUI: Adapt screenshot sound to ringer modes  [Ashwin R C]
* c64b65c  base: core: Unregister broadcast receiver only when registered  [Soo-Hwan Na]
* 45f01c4  core: Gracefully handle unregistering of unregistered receivers/services  [minaripenguin]
* 2e2e4ae  Fix unknown sources app install confirmation  [Tommy Webb]
* deb3800  Fix uninstall for all users  [Tommy Webb]
* f52ab52  SettingsLib: Make all user apps cloneable [1/2]  [Jyotiraditya Panda]
* 2dd8881  charging: Allow using vibration without sounds  [xyyx]
* a281ffb  base: Add support for disabling fingerprint lockout [1/2]  [SamarV-121]
* f6852df  CustomUtils: Refactor isPackageInstalled method  [Pranav Vashi]
* 705c9a7  PropImitationHooks: Fix bootloader spoofing [2/2]  [minaripenguin]
* 2c1ddda  services: Disable automatic system server heap dumps by default  [minaripenguin]
* 7ed11cf  KeyStore: Update local attestation spoofing  [minaripenguin]
* 2d9c16c  CEC: correct frameworks physicalAddress parsing  [Thomas Makin]
* f8528fd  LocalImageResolver: Stop the spam  [penglezos]
* 2f202a8  base: Add support for strict standby policy [SQUASH]  [LibXZR]
* 3e470fd  SystemUI: Allow ignoring IWlan status in the mobile icon pipeline  [Tommaso Fonda]
* b7c8df4  Gesture nav: Add back menu action  [someone5678]
* 8212ab9  Gesture nav: Add go forward action  [someone5678]
* 278d266  Gestures nav: Make it cancelable  [someone5678]
* 8f0ff90  Gestures nav: Add back show recents action  [someone5678]
* 7928fb3  SystemUI: BackPanel: Always add second arrow in front on long swipe  [someone5678]
* 0f41f79  SystemUI: navigationbar: Flip canvas if gesture started from left  [someone5678]
* 9970342  Gestures nav: Add Partial Screenshot action  [spezi77]
* b73a075  Gestures nav: Add Power menu action  [kdrag0n]
* 545c368  Show a double arrow when almost triggered in new back affordance as well  [DennySPb]
* 980a4c9  [SQUASH] Advanced navigation "extended/L" gestures  [ezio84]
* 7003387  [SQUASH] Utils: Actions for advanced navigation gestures  [ezio84]
* 67a3d68  base: Add api to take screenshots  [bigrushdog]
* 695a214  Utils: Add method to turn off the screen  [ezio84]
* ace8b46  Utils: Reverse actions for QS and notification panel  [ezio84]
* 4b65700  Add api to get or kill foreground app  [ezio84]
* 5017d70  Add a sendKeycode api to Utils  [ezio84]
* 7eec7e4  Add api to toggle flashlight and check if device has flashlight  [ezio84]
* 52f068a  Utils: Add isAvailableApp method  [maxwen]
* a28c0e0  UI: Follow Monet and light/dark theme in user 1 icon  [Andy CrossGate Yan]
* 7054843  Fix screen flickering when using one handed mode  [timjosten]
* 0c897f0  SystemUI: Fix double unlock sound issue  [timjosten]
* 90ed111  base: Use Context instead of Application for *PropsUtils [2/2]  [someone5678]
* 045aad4  Add 5G Ultra Wideband icon carrier config keys  [Vala Zadeh]
* ae51c3f  TelephonyManager: Add getLteOnCdmaMode() function for default subId  [Ido Ben-Hur]
* 4d4031d  telephony: Add ICCID into CarrierIdentifier  [Mengjun Leng]
* 63a533f  Remove unnecessary HashMap instantiation  [Josep del Rio]
* f3885b6  Fix NPE in AnomalyReporter.initialize  [yangjing24]
* 0c95dc0  base: Spoof current storage encryption status [1/2]  [someone5678]
* e60d7a5  add workaround for dynamic code logging system_server crash  [Dmitry Muhomor]
* 9664198  core: Allow telephony stack and its components to receive un-sanitized ServiceState entries  [minaripenguin]
* 97e587d  Skip checking SystemUI's permission for observing sensor privacy  [Han Wang]
* 30631673  SystemUI: enable fading squiggle animation of qs media player  [nift4]
* b2834db  BatteryStatsViewer: Move it to Battery Section  [Subratam6296]
* b48dbcd  BatteryStatsViewer: Fix theme  [Michael Bestas]
* 3d9ba68  BatteryStatsViewer: Fix initial activity after launch  [Michael Bestas]
* d74aa10  BatteryStatsViewer: Add summary for IA preference  [Michael Bestas]
* d5e86e6  Create IA entry for BatteryStatsViewer  [Oliver Scott]
* 77283a6  BatteryStatsViewer: Remove some hardcoded strings  [Michael Bestas]
* ba7c2d9  Fix odm privapp permissions  [Jurijs Oniscuks]
* 762d829  wm: Fix menu in legacy apps with multiple activities  [nift4]
* c833b39  display: Consider peak refresh rate in BrightnessObserver  [Adithya R]
* 089d97d  SystemUI: Make popup menus more rounded  [Lucchetto]
* 58644dc  ActivityManagerService: Exclude more packages for receiver check  [Pranav Vashi]
* da323344  SystemUI: Do not duplicate SPN and PLMN in network name  [Adithya R]
* c074e9f  Prevent crashing with several child profiles  [Tommy Webb]
* 034d9d9  Show hidden apps on secondary users' app lists  [Oliver Scott]
* 72319e2  services: fix weird launcher3 crash  [nift4]
* a863d38  ChargingControl: Additional log lines for deadline  [Tommy Webb]
* 60c9fd7  ChargingControl: Retry setting deadline if it fails  [Tommy Webb]
* 53bebf7  ChargingControl: Drop default values for initially zero variables  [Luofan Chen]
* 88798e5  ChargingControl: Return early if lineage health HAL is not found  [Luofan Chen]
* b9c67fb  ChargingControl: Don't set deadline if charging control is not enabled  [Luofan Chen]
* 20351f0  ChargingControl: Use ServiceManager.waitForDeclaredService()  [LuK1337]
* 8bfacfb  ChargingControl: No need to log a crash when not supported  [Michael W]
* 6bc1588  ChargingControl: Handle cancel toggle correctly if bypass is not supported  [Luofan Chen]
* f04e187  ChargingControl: Add cancel toggle for limit done notification  [Luofan Chen]
* 46db34a  ChargingControl: Reset internal states on settings change  [Luofan Chen]
* b3c1393  ChargingControl: Set a small margin for devices with bypass support  [Luofan Chen]
* e7d615c  base: Add static isChargingControlSupported(ctx) method  [LuK1337]
* a5071b1  base: Implement Lineage health service  [Luofan Chen]
* a1d5e54  base: Extract base class for lineage base feature  [Luofan Chen]
* fa1c8f2  base: Settings: Add settings for charging control  [Danny Trunk]
* b04bc3a  BluetoothControllerImpl: Optimize connected battery level scanning  [minaripenguin]
* 5949e8f  [SQUASH] SystemUI: Show bluetooth battery level on statusbar  [LuK1337]
* eebacec  idmap2: Cache Lineage resources  [Luca Stefani]
* 9ecd867  androidfw: Add Lineage res to default assets  [Luca Stefani]
* 7d7de55  Allow lineage resources package to be overlayed by RRO packages  [LuK1337]
* 402587b  services: Keep vendor.lineage.* classes  [Michael Bestas]
* c62db56  services: Keep sdk classes  [Michael Bestas]
* a2c5e01  SystemUI: update powershare QS tile icon  [aswin7469]
* 4aee336  services: Fix strict mode violation when decompressing files  [minaripenguin]
* 99953e9  Revert "Deprecate TunerService"  [Pranav Vashi]
* 32860d7  core: res: Add ParanoidSense into privacy indicator exemption list  [someone5678]
* 00d8913  usb: Show charging notification only if power brick is disconnected  [Adithya R]
* 070e73f  Do not ignore background vibrations from shell  [Tommy Webb]
* b14c009  services: Fix exception when retrieving target SDK version  [minaripenguin]
* fdcd260  display: Allow HBM in manual brightness if no time limitation  [Adithya R]
* 7e2e447  FaceService: Conditionally add ParanoidSense  [someone5678]
* 7dd8805  BootReceiver: Return early if trace_pipe doesn't exists  [minaripenguin]
* 1d5062a  FaceSense: Vibrate on successful authentication  [Adithya R]
* 9bfb956  SettingsLib: Handle WifiService being null  [Sebastiano Barezzi]
* daab8c8  base: Reset props for status bar lyric [2/3]  [cjybyjk]
* 9298eb5  [SQUASHED] base: Add status bar lyric for Android 14  [cjybyjk]
* ad501a4  base: Incall vibration options [1/3]  [beanstown106]
* 6b79ef3  base: Add util function to restart any app  [Blaster4385]
* 55439bc  base: Add optional haptic feedback on scrolling with fling gesture [1/2]  [Blaster4385]
* 1577192  SystemUI: Use click effect instead of duration for haptic feedback for QSTile  [Krishnakant Shedge]
* f590bf4  QuickSettings: Add Haptic Feedback to tiles [1/2]  [Evisceration]
* cafc978  base: Add optional haptic feedback to volume panel [1/2]  [Blaster4385]
* 3b52c14  Keyguard: Add option to scramble pin layout when unlocking (2/2)  [Adnan]
* 369cbce  SystemUI: Animate StatusBarState doze transition using DarkAnimator  [someone5678]
* 369f92c  SystemUI: RecordingService: Fix non dismissing notifications  [Ido Ben-Hur]
* c4876a0  SystemUI: Add double tap to sleep gesture  [Rashed Abdel-Tawab]
* 28f1ff2  base: Make Gesture navbar IME space settings key readable  [minaripenguin]
* 267430f  CarrierConfig: Always show APN settings on CDMA carriers  [flawedworld]
* 2ad4fe9  SystemUI: AODTile: Use MD2 Icon  [Anushek Prasal]
* 870ed52  SystemUI: screenshot: add extra crop boundaries  [Cosmin Tanislav]
* 68c1603  SystemUI: screenshot: remove duplicate clamping on move action  [Cosmin Tanislav]
* de2a1fe  power: Explicitly check for silent ringtone  [Sam Mortimer]
* f8113c1  power: Respect global vibration setting for charging sounds  [Michael Bestas]
* f6bdfd4  SystemUI: Hide notifications when quickly expanding QS  [Adithya R]
* 8ca395d  Keystore: Spoof locked bootloader on local attestations  [minaripenguin]
* 5bd361f  base: fix wake on unplug also for wireless charging  [maxwen]
* e858057  SystemUI: Update NFC tile drawable  [mydongistiny]
* bfd2e2f  Fix action bar font family on material themes  [Henrique Silva]
* 1900bcd  services: Fix google apps permission denials [2/2]  [minaripenguin]
* 690cd4d3  service: Do not ensure system package for required services extension  [minaripenguin]
* 12157b8  services: Bypass shorcut permission enforcement to default launchers  [minaripenguin]
* f2fbc6a  SystemUI: Update NFC icon  [Adithya R]
* a9f1ab2  SystemUI: Add statusbar NFC icon  [xyyx]
* 23f026f  SystemUI: Add click actions to combined QS header  [Ido Ben-Hur]
* 3f7ed28  Add Face Unlock with ParanoidSense  [Chris Crump]
* eb2a5c1  base: Allow disabling color inversion support [1/2]  [Ido Ben-Hur]
* 1f59831  Increase Zenmode max hour limit from 12 to 24  [Alex Cruz]
* f6b1929  base: Add a notification for percentage based battery saver  [Ido Ben-Hur]
* 9771f1a  SettingsLib: Extend protect sensitive info to MAC [1/2]  [Ido Ben-Hur]
* 558f465  development: Address NPE when removing preferences out of developer options  [Alex Cruz]
* e32669d  base: Update some icons to MD2  [Anushek Prasal]
* 53ec31b  Crash occured due to null pointer exception.  [Niraj kumar Mishra]
* 9283c0e  Restore getSimStateForSlotIndex in SubscriptionManager  [Andy CrossGate Yan]
* 65f568d  TtsEngines: avoid crashes caused by null engine name  [Oliver Scott]
* a276e43  SystemUI: AntiFlickerTile: Catch NullPointerException  [someone5678]
* 97ddddb  ServiceRegistry: Don't throw an exception if OEM_LOCK is missing  [Scott Warner]
* ddc76b9  services: Fix NPE caused by null connectionToken  [minaripenguin]
* b7b5ac54  services: Fix ArrayIndexOutOfBoundsException in TextServicesManagerService  [minaripenguin]
* fd73046  services/PPU: Simplify and improve bypassing for PPU `onTaskStackChanged` listening [2/2]  [minaripenguin]
* 3cdc11c  AudioService: focus listener: enable it when using external AudioFocus  [Francois Gaffie]
* 231c0f04  KernelCpuUidActiveTimeReader: Do not spam log with negative active time  [cjh1249131356]
* f37935a  SystemProperties: Override vendor values with product key values  [minaripenguin]

#### packages/apps/BtHelper

* 7a6f09f  PodsService: Correctly broadcast ACTION_BATTERY_LEVEL_CHANGED  [someone5678]
* e8e0376  Revert "BtHelper: Check whether bond state changes to none"  [someone5678]
* 954db4f  PodsService: Set METADATA_MAIN_BATTERY  [someone5678]

#### packages/apps/Settings

* 8e1fb1e  Settings: Move all custom security options to misc security settings  [someone5678]
* da2744a  Settings: Add additional security settings preference  [someone5678]
* de65f87  ExternalStorageProvider: Conditionally remove SAF restrictions [2/2]  [someone5678]

#### vendor/parasite

* b65dcec  PixelPropsUtils: Sort packagesToChangeRecentPixel entries  [someone5678]
* d583c71  GamesPropsUtils: Move PUBG Mobile spoof to ROG Phone 8 as well  [Joey]
* 2b3cc64  PixelPropsUtils: Stop spoofing Gboard and Play store  [Joey]

### 06-01-2024

#### packages/apps/Settings

* 454c0a8  DataProcessor: Do not skip and replace screen on component with screen on time  [minaripenguin]

#### vendor/google/pixel-additional

* d884e0e  pixel-additional: Drop TurboAdapter_NoBatt  [someone5678]
* 4fed5af  TurboAdapter_NoBatt: Return null for get* methods  [someone5678]

#### vendor/parasite

* fa8f79d  PixelPropsUtils: Move all apps out of Pixel 5a list  [someone5678]

### 05-31-2024

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

#### hardware/qcom-caf/common

* 29e63ca  libqti-perfd-client: Add more dummy methods  [someone5678]
* 40a7e32  qcom: Allow a device to manually override which HALs it wants to use  [Akhil Narang]

#### manifest

* afb908d  [TMP] manifest: parasite: Track hardware/qcom-caf/common diff --git a/snippets/lineage-caf.xml b/snippets/lineage-caf.xml index 378758192..56136b36c 100644  [someone5678]

#### packages/apps/Aperture

* 8d4db99  Aperture: Switch to ZXing-C++  [LuK1337]
* 3a903a6  Aperture: Update kotlin to 1.9.0  [LuK1337]
* 10b101e  Aperture: Update ZXing to 3.5.3  [LuK1337]

#### packages/apps/Settings

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

### 05-30-2024

#### vendor/aosp

* 8f6ab31  soong: Add power libperfmgr extension config  [Arian]

#### vendor/google/pixel-additional

* a2371ee  TurboAdapter_NoBatt: Throws remote exception  [someone5678]

#### vendor/sony/extra

* 9fce5c0  extra: custom: daxService: Update tile name  [someone5678]

#### vendor/sony/sm8550-common

* 43e5b7b  sm8550-common: Remove QTI perfd  [someone5678]
* 4b4030b  sm8550-common: Move init.qcom.post_boot.sh to device tree  [someone5678]

