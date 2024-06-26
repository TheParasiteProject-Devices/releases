# pdx234

### 06-26-2024

#### device/sony/pdx234

* 421fd84  pdx234: overlay: parasite: Setup X-Reality mode preset for this device  [someone5678]

#### device/sony/sm8550-common

* eace897  sm8550-common: overlay: Remove "Saturated" from supported profile  [someone5678]
* c204e00  sm8550-common: Setup DeviceAsWebcam  [Yumi Yukimura]
* 8097b5b  sm8550-common: init: Give proper permissions for /dev/diag  [Yohan Black]
* 93fd129  sm8550-common: Enable Smart Pixels support  [someone5678]
* db8b750  sm8550-common: Build libidd dummy  [someone5678]
* 0bbc3d6  sm8550-common: Kill useless in device diagnostics  [someone5678]
* a8afd57  sm8550-common: Mark CNE symlink target as required package  [Bruno Martins]
* 9fc88fd  sm8550-common: Declare EGL libs as symlinks during extraction  [Bruno Martins]
* d1dc2f9  sm8550-common: Declare IMS libs as symlinks during extraction  [Bruno Martins]
* 15a115c  sm8550-common: Move all symlinks to install_symlink targets  [someone5678]
* 6f61f0d  sm8550-common: Move to new RFS install_symlink targets  [Bruno Martins]
* 6a48c72  sm8550-common: Unset BUILD_BROKEN_INCORRECT_PARTITION_IMAGES  [Bruno Martins]
* 4f078a8  sm8550-common: Allow pipe2 to qwesd  [someone5678]
* 71d8af7  sm8550-common: Build some VNDK libraries  [micky387]
* 93ba104  sm8550-common: props: Move props to avoid sepolicy denials  [someone5678]
* dd53ba7  sm8550-common: Build missing libraries for 14 QPR3  [Michael Bestas]
* 47a79c7  sm8550-common: vendorsetup.sh: Correct var name  [someone5678]
* 765392f  sm8550-common: Enable blur  [someone5678]
* 6ae8f59  sm8550-common: vendorsetup.sh: Guard it  [someone5678]
* 810c099  sm8550-common: Do not set BOARD_API_LEVEL manually  [someone5678]
* 705f626  sm8550-common: Update parasite signature dir  [someone5678]
* aa25ac4  sm8550-common: Run reorder-libs.py  [someone5678]
* 4ef5052  [TMP] Automatically patch Sony changes to qti usb  [someone5678]
* 2e49f41  sm8550-common: Include Qcom usb configs  [someone5678]
* 6861d3d  sm8550-common: Build and import more display components  [someone5678]
* 81db5e3  sm8550-common: configs: wifi: Import configs from wifi-bonding  [someone5678]
* 3287e99  sm8550-common: props: odm: Enable SDR dimming for HWC  [someone5678]
* 572403e  sm8550-common: props: odm: Clean-ups  [someone5678]
* 281fbe1  sm8550-common: props: Set default Wi-Fi country code  [someone5678]
* c85c84a  sm8550-common: vibrator: Rename to avoid conflicts  [someone5678]
* 37d5a43  sm8550-common: Update powerhint.json nodes to kalama  [someone5678]
* 7b8e511  sm8550-common: Use HintManager for HWUI  [Vaisakh Murali]
* 04aa05a  sm8550-common: rootdir: Kill WALT CPU boosting  [Sugakesshaa]
* 7150279  sm8550-common: powerhint: Drop CPU freqs boosting on INTERACTION  [bheatleyyy]
* 70d6267  sm8550-common: powerhint: Follow taro's CPU freqs for little cluster  [bheatleyyy]
* c02d2a7  sm8550-common: rootdir: Do not allow foreground tasks to run on CPU7  [Jake Weinstein]
* da040bc  sm8550-common: rootdir: Move background cpuset to CPU0-1  [Jake Weinstein]
* c082cca  sm8550-common: rootdir: Set restricted cpuset to the same CPUs as system-background  [Jake Weinstein]
* 7989254  sm8550-common: sepolicy: Allow powerhal write to /proc  [Sugakesshaa]
* 4d2e4c9  sm8550-common: rootdir: Enable powerhint parsing after boot completion  [Bruno Martins]
* 28211bb  sm8550-common: powerhint: Adapt and tune for SM8475 (cape)  [bheatleyyy]
* b3f520d  sm8550-common: Import powerhint.json from lahaina  [bheatleyyy]
* c3aa93d  sm8550-common: Provide a static lib for power mode extension  [Arian]
* dbac21b  sm8550-common: Migrate to common libqti-perfd-client and power-libperfmgr  [Bruno Martins]
* f6c7001  sm8550-common: Remove QTI perfd  [Wei Wang]
* 423c9d1  sm8550-common: Move init.qcom.post_boot.sh here  [someone5678]
* 486287b  sm8550: Signing build with custom key  [someone5678]
* 77d548e  sm8550-common: Import Google changes on DEC7 Volume on all mic paths  [Arseniy Graur]
* 74b3c52  sm8550-common: rottdir: Remove duplicated TA patition permission setup  [someone5678]
* f70d045  sm8550-common: rootdir: Move powershare permission setup to ueventd.sony.rc  [someone5678]
* eac1b90  sm8550-common: configs: audio: Sync hotword input to primary input  [someone5678]
* 413fbad  sm8550-common: Build Kprofiles as LKM  [someone5678]
* 00232de  sm8550-common: overlay: Add Sony's public vendor platform signature  [someone5678]
* 75ff722  sm8550-common: Enable puffdiff for ota compression  [someone5678]
* 1643af5  sm8550-common: Enable zucchini for ota compression  [someone5678]

#### device/xiaomi/sweet

* eee4cd5  [TESTING] Enable microG integration  [someone5678]

#### external/bouncycastle

* d420665  Add more files to bouncycastle-repackaged-unbundled  [someone5678]

#### frameworks/base

* fd7c018  Import certification changes  [someone5678]
* d8ca92c  Revert "Keystore: Spoof locked bootloader on local attestations"  [someone5678]

#### hardware/sony

* da6ae01  XperiaParts: Notify user of the behavior of the creator mode  [Luofan Chen]
* 6e84037  XperiaParts: Don't setup display HAL on boot if setting is disabled  [Luofan Chen]
* 05f2972  sony: Add libidd dummy  [someone5678]
* 61991b2  XperiaDisplay: Introduce X-Reality Engine  [saku-bruh]
* dfddb4c  XperiaSettings: Set profile to be primary profile only  [someone5678]
* 430dc35  XperiaDisplay: Make sure it's not enable by default on first boot  [lolipuru]

#### hardware/xiaomi

* 7f9dcf1  hidl: biometrics: fingerprint: Set thread to high CFS priority  [Nauval Rizky]
* 4fdb6f3  interfaces: fxtunnel: Add fxtunnel 1.0 interface  [bengris32]
* 8448f1f  XiaomiEuicc: Remove references to EuiccPixel  [Bruno Martins]
* 1c6e5a2  XiaomiEuicc: Move to priv-app and grant required permissions  [someone5678]
* 332b87f  XiaomiEuicc: Disable EuiccGoogle when GMS and GSF are not installed  [Peter Cai]
* c796111  Introduce XiaomiEuicc  [Bruno Martins]
* 54ffb9d  dolby: Convert to SwitchPreferenceCompat  [Michael Bestas]
* 0e2aa22  DolbyManager: Migrate to CompoundButton.OnCheckedChangeListener  [Chaohui Wang]
* fe95159  dolby: Enable use_resource_processor for all sysui deps  [Peter Kalauskas]
* b003cd0  vintf: Add more hals to fcm  [Adithya R]
* fd02f28  xiaomi: Introduce Dolby Atmos  [Adithya R]
* 7aea56c  vibrator: effect: Fallback to click if an effect is missing  [Adithya R]
* ccb8279  vibrator: effect: Create double click effect from click if necessary  [Arian]
* 470a6b4  vibrator: effect: Read vibration fifo data from vendor  [Arian]
* 61ec891  vintf: Remove transports from FCM  [Bruno Martins]
* 7ba79ec  vintf: Add synaptic interfaces to FCM  [Andrey Sprynga]
* 3dd9b99  aidl: light: Add RGB sync support  [LuK1337]
* 7da3f21  aidl: light: Lower battery light priority  [LuK1337]
* cab0f67  aidl: light: Support the `left` LED  [danielml]
* bba3857  aidl: light: Add support for button-backlight2 device  [LuK1337]
* 8ced65e  aidl: light: Add support for timed mode  [Bruno Martins]
* ec5b9a4  aidl: light: Refactor  [Sebastiano Barezzi]
* 3f9bef8  vintf: Add extra GoodixFingerprint interfaces  [Bruno Martins]
* 31f5d42  vintf: Add {goodix 2.1, fingerprintextension, motor} to fcm  [Arian]
* 9892a7a  aidl: Remove useless makefile  [Bruno Martins]

#### manifest

* 4b9502b  manifest: parasite: Track external/bouncycastle  [someone5678]

#### vendor/aosp

* 50838d8  [TMP] Revert "kernel: Update default clang version to r510928"  [someone5678]
* 7411a00  kernel: Update default clang version to r510928  [Aaron Kling]
* 5a433e3  kernel: Add rust prebuilts to path  [Aaron Kling]
* e94eb1c  vendor: AOSPASettingsOverlay: Clean-ups  [someone5678]
* 513f05b  vendor: aconfig: Remove use_media_router2_for_info_media_manager  [someone5678]
* 221152b  vendor: aconfig: Enable volume panel related configs  [someone5678]
* 36d9a8d  kernel: Add support to append DTBs to kernel image  [Yumi Yukimura]
* fe022e5  vendor: optimisation: Move shutdown prop to system_ext  [someone5678]
* 60e83be  vendor: Move out aconfig to top of repo  [someone5678]
* 8b9a169  fixup! Hookup GRALLOC_HANDLE_HAS_UBWCP_FORMAT  [AdarshGrewal]

#### vendor/certification

* dafd9c1  libs: Adapt to current project  [someone5678]
* 05ca98e  libs: Adapt import to current project  [someone5678]
* 13530c8  libs: Import FrameworkPatch sources  [chiteroman]
* d83f82d  certification: Add com.android.internal.util.custom.certification  [someone5678]

#### vendor/parasite/common

* c6239ad  PixelPropsUtils: Move out certfication stuffs  [someone5678]

### 06-25-2024

#### frameworks/base

* 65e7ea9  fixup! SystemUI: Add API for runtime taskbar config  [Oliver Scott]
* eaaaf62  fixup! SystemUI: Restore 14 QPR1 FingerprintInteractiveToAuth handling  [Oliver Scott]
* 909b221  services: Make X-reality display engine mode preset configurable  [someone5678]

#### vendor/qcom/opensource/usb

* 10c592d  USBGadgetHAL: Add support for UVC function  [Yumi Yukimura]

### 06-24-2024

#### frameworks/base

* a69c47e  Camera: Clearing exception for Extended Face  [Sauhard Pande]
* 6610222  camera: Allow selected camera apps to skip unconfigure  [LuK1337]
* ea7f550  Guard in short-circuit evaluations for stringSplit methods.  [Mohammed Irfan]
* 919577f  Camera: Don't crash when trying to disable shutter sound  [jhenrique09]
* 0d6c143  Camera: Add feature extensions  [Sauhard Pande]
* 330082d  Fix Photosphere/Camera FCs  [Jostein Kjønigsen]
* 36b195b  Allow sending vendor- or device-specific commands to the camera HAL.  [Danny Baumann]
* 28b21d5  Camera: Expose aux camera if packagename is null  [wbs306]
* d9e99a7  CameraDeviceImpl: Don't crash when checking input configuration failed  [Xayah]
* 0a53768  CameraManager: Prevent out of bounds when extracting camera IDs  [minaripenguin]
* a0cc86e  Camera: Extend face detection  [Shuzhen Wang]
* 14faa5c  SystemUI: Properly set margins for QQS Brightness slider  [Pranav Vashi]
* 04c684e  [TMP] SystemUI: Use performHapticFeedback for volume slider haptic  [someone5678]

#### hardware/qcom-caf/common

* 9078867  fwd-detect: Create symlink target for CneApp  [Bruno Martins]
* 6dd8d87  Introduce RFS install_symlink targets  [Bruno Martins]

#### packages/apps/Settings

* a3a0c6c  Settings: Disable Smart Pixels if not supported  [someone5678]
* 6123f9f  fixup! Settings: Add optional haptic feedback on scrolling with fling gesture [2/2]  [someone5678]
* f3da88a  fixup! Settings: Allow to hide screen capture status from apps [2/2]  [someone5678]
* ae4365a  Settings: Allow toggling privacy indicators  [Ido Ben-Hur]
* 36f63aa  Revert "Settings: Add location indicators toggle to privacy control settings"  [someone5678]
* ebfe5d6  Revert "Link location indicators toggle in privacy settings"  [someone5678]
* a38b074  Settings: display: Sync X-Reality Engine summary to hardware/sony  [someone5678]
* 15cb4a8  display: Introduce X-Reality Engine display mode [2/2]  [minaripenguin]
* 5bfd2af  Settings: Add color mode category  [someone5678]
* cddc6be  Settings: Forcefully enable Hotspot Speed setting  [someone5678]
* 24c5169  WiFi: Remove country code checking.  [xyyx]
* befd3e1  Settings: Move all custom security options to misc security settings  [someone5678]
* 77d6ea8  Settings: Add additional security settings preference  [someone5678]
* 1890433  ExternalStorageProvider: Conditionally remove SAF restrictions [2/2]  [someone5678]
* a1f257d  DataProcessor: Do not skip and replace screen on component with screen on time  [minaripenguin]
* 7384fd3  NightDisplay Settings: Use List Preference for NightLight settings  [Akash]
* 97515d8  DarkMode Settings: Use List Preference rather ugly Drop Down  [Pranav Vashi]
* 14957d6  Settings: Allow to hide screen capture status from apps [2/2]  [someone5678]
* 53af1ad  Settings: Update Annoying Notifications title  [someone5678]
* c61c249  Settings: Update Misc Haptics title  [someone5678]
* 7496919  CustomSettings: Remove un-implemented features  [someone5678]
* 64fe33c  Settings: Generify custom project info props  [someone5678]
* ab85255  Settings: Fix regulatory info availability check  [Ido Ben-Hur]
* 542cf86  Settings: Add a dev option to unlimit screenrecord filesize [2/2]  [Ido Ben-Hur]
* 479cace  Settings: Update hide developer status strings  [someone5678]
* 1cd80cb  Settings: Update storage encryption status spoofing strings  [someone5678]
* 0da450d  Settings: Fix setting device name based on market name  [John Vincent]
* 05f4232  Settings: Set device name from marketname if available  [Pranav Vashi]
* 41fc18d  Settings: deviceinfo: Move Battery info preference back to device info page  [someone5678]
* c4216b2  Settings: Add icon for emergency broadcasts  [Pranav Vashi]
* a9fecad  Settings: Add Market Name to device info  [someone5678]
* fed6636  Make battery cycle count configurable and disable it by default  [Michael Bestas]
* 5c8a465  Hide unavailable battery info  [Michael Bestas]
* a9452cd  Settings: deviceinfo: Extend Battery info page  [Jyotiraditya Panda]
* 2deb8ba  Make battery info configurable and enable it by default  [Michael Bestas]
* 295b763  Settings: Use marketname for App Aspect Ratio summary  [someone5678]
* bee221b  fixup! Add option to reset network settings to factory  [someone5678]
* 5ff91fa  Update PhoneLink 14-3 Settings change  [chawan]
* 5a173f9  Island: Add Now playing settings  [minaripenguin]
* 31b78d2  Settings: Add fragment for Island Feature  [minaripenguin]
* 3be0a2a  Settings: support per-app volume [3/3]  [cjybyjk]
* 05b39a1  Settings: Add haptics to brightness slider [2/2]  [someone5678]
* f43605d  Settings: Move three-fingers-swipe to screenshot to SwitchPreferenceCompat  [someone5678]
* 3344a4a  Settings: ButtonSettings: Move to SwitchPreferenceCompat  [someone5678]
* 96a3bc0  BatteryStateDatabase: Set exportSchema to false  [someone5678]
* 035cef9  Settings: Make all user apps cloneable [2/2]  [Jyotiraditya Panda]
* fb91c2c  SoundSettings: Add charging vibration settings  [xyyx]
* ffd9230  Settings: Add support for disabling fingerprint lockout [2/2]  [SamarV-121]
* f0639d0  fixup! Settings: Allow extended/"L" back swipe to trigger actions/app/activities [2/2]  [someone5678]
* ff1c9bd  Settings: Always restore keyChordPowerVolumeUp to mute...  [Adithya R]
* 4f7dc53  Settings: Add userRestriction for auto brightness  [Erfan Abdi]
* 10b0647  Settings: Introduce new refresh rate selector page  [Adithya R]
* 73cf005  Settings: Gesture nav: Add back launch menu action  [someone5678]
* 21fad5f  Settings: Gesture nav: Add go forward action  [someone5678]
* 4bb3690  Settings: Gesture nav: Correctly disable left/right option when long swipe setting is disabled  [someone5678]
* 7244ef0  Settings: Gestures nav: Add back show recents action  [someone5678]
* 81cb0ca  Settings: Gesture nav: Remove timeout setting  [someone5678]
* 8d38fbf  Allow extended/"L" back swipe to trigger actions/app/activities [2/2]  [ezio84]
* 340595e  Settings: Spoof current storage encryption status [2/2]  [someone5678]
* f7b5315  ChargingControl: Don't index settings if it is not supported  [Luofan Chen]
* 44dd5cb  Settings: Add charging control preferences  [Danny Trunk]
* 0f711c9  Settings: Reset props for status bar lyric [2/2]  [cjybyjk]
* 8296d34  Settings: Add status bar lyric [2/2]  [Kujou Yuko]
* 676319d  Settings: Add optional haptic feedback on scrolling with fling gesture [2/2]  [Blaster4385]
* 62386b0  QuickSettings: Add Haptic Feedback to tiles [2/2]  [amartinz]
* 19a1b6f  Settings: Add optional haptic feedback to volume panel [2/2]  [Blaster4385]
* 72873e8  Settings: Align user avatar with homepage title  [jhonboy121]
* 7ead105  Status bar: Wifi Standard Icon [2/2]  [minaripenguin]
* 6c1db1a  Settings: Allow to quickly open Running Services from meminfo view  [ezio84]
* 4041e83  Settings: Declare an activity for WirelessDebuggingFragment  [Ido Ben-Hur]
* 7fd492f  Settings: Extend protect sensitive info to MAC [2/2]  [Ido Ben-Hur]
* aeb8b91  Settings: Allow toggling floating rotation button [2/2]  [Ido Ben-Hur]
* 4fa0a87  Settings: Allow disabling color inversion support [2/2]  [Ido Ben-Hur]
* 1f3aec5  Settings: disable all bugreport settings  [maxwen]
* 5674c16  Settings: Fix potential NPE in WifiTetherSecurityPreferenceController  [Fabian Leutenegger]
* ecd74ae  Settings: buttons text should no longer be allCaps  [maxwen]
* 8a3ab88  Fix long click intent for Smart Pixels tile [2/2]  [Pranav Vashi]
* 6d762a4  Settings: Smart Pixels [2/2]  [Adin Kwok]
* 86a5d16  Settings: Add developer setting to set the default GPU renderer.  [Joe Maples]
* 3d7b147  Settings: Update Application downgrade and Ignore window secure strings  [someone5678]
* 5ccb9d1  Settings: Bluetooth: Don't check persistable uri permission for BtHelper  [someone5678]
* 137d203  Settings: allow disable of screenshot shutter sound [2/2]  [someone5678]
* f502c2a  Settings: fix typo in settings namespace for qr scanner on ls  [maxwen]
* 09ea5c8  Settings: Fix tint on newly added private VPN and mobile plan icons  [Bruno Martins]
* 01dd818  Settings: Update private dns icons  [penglezos]
* 3759b17  Settings: Make roaming indicator optional [2/2]  [Pranav Vashi]
* ccdc62b  Settings: Option to Display Data Disabled Indicator Icon [2/2]  [varund7726]
* 7a8fe9f  Settings: User toggle for unlimited photos storage [2/2]  [spezi77]
* 44dfcbe  Settings: Add advanced settings preference  [someone5678]
* 91390db  Fix LTE Only mode on World Mode  [flawedworld]
* 66cd7ea  LTE Only Mode  [Pratyush]
* a2940ea  Settings: Add location indicators toggle to privacy control settings  [someone5678]
* 41ed330  Settings: Don't check ro.build.selinux  [someone5678]
* 52050f0  Settings: Add proximity check on wake preference  [Bruno Martins]
* 1e2285f  crdroid: Transparent QS customization  [ShevT]
* d976bcc  Settings: Add Device codename to Firmware version window  [ganeshi4u]
* c93c35e  Settings: Move Vo5G toggle right below VoLTE  [Adithya R]
* dad09f1  Settings: StatusBarSettings: Restore Network Traffic Settings  [someone5678]
* bc51262  Settings: Add default value for Navigation Bar IME Space  [someone5678]
* 9ea11ab  Settings: Allow to skip confirmation in biometric auth dialog [3/2]  [someone5678]
* 215b08a  Settings: Re-order SELinux status on About Phone  [someone5678]
* 3e6f35e  Settings: Allow to skip confirmation in biometric auth dialog [2/2]  [cjh1249131356]
* efe91b7  Settings: Export FaceEnrollFinish activity to Sense  [Chris Crump]
* dda4436  Settings: Partial import DotOS A11 About Phone design  [IacobIonut01]
* 792f8ae  Port "Battery Usage Alerts" feature from factory images  [ezio84]
* 57444ef  Settings: Implement cutout force full screen [2/2]  [jhenrique09]
* c9220fb  Settings: Add empty TheParasiteProject config overlay  [someone5678]
* 39a3d7a  Settings: Hide ADB and developer setting enable status [2/2]  [someone5678]
* 30e9bb6  Properly set Wi-Fi Privacy spinner initial state  [Tommy Webb]
* 39d3fa8  Settings: Do not skip fp authentication for udfps  [Adithya R]
* 45d09e7  Settings: Add a preference to battery optimization page  [jhonboy121]
* ad580cc  Settings: Black theme [2/3]  [SagarMakhar]
* 186bd5f  Settings: Hide radio info if device don't support voice  [LynnrinChan]
* 3d0251b  Settings: Expose radio info (*#*#4636#*#*)  [xyyx]
* 9fb972f  Link location indicators toggle in privacy settings  [Danny Lin]
* 97040af  Settings: Improve code for time spent in app  [Jyotiraditya Panda]
* 3503e0f  AppInfo: Add time spent in app from Wellbeing  [Jason Edson]
* a6e75e0  Settings: use Glif themed button bar  [Timi Rautamäki]
* 9a868a9  Add toggle for connectivity check  [Aayush Gupta]
* 82009b4  AGPS: Mention that it's ignored during user-initiated emergency calls  [Chirayu Desai]
* d88a344  Settings: StatusBarSettings: Restore Network Traffic Settings  [someone5678]
* 7de526c  Settings: Add switch preference for AGPS  [juwei]
* 2adfa33  NetworkProviderSettings: Fixup uninitialized mWifiManager  [Jacob McSwain]
* e0a2f72  Settings: Add more required libraries  [Joey Huab]
* f24dabe  Settings: Add Glide library  [SagarMakhar]
* 67f3488  Settings: Regulatory: Fullscreen instead of AlertDialog  [ReallySnow]
* 10b060d  Settings: Remove IME space under keyboard feature [2/2]  [timjosten]
* 516bfd1  Settings: Allow using 4G icon instead LTE [2/2]  [neobuddy89]
* f2b7656  Settings: Remove DSU Loader if unsupported  [Joey Huab]
* fbd0b31  Settings: Remove A/B preference if unsupported  [Luca Stefani]
* 0266aea  Settings: Add Default USB Configuration  [ZeNiXxX]
* cf7188e  Settings: Show SoC Model rather than value of ro.board.platform if available  [Tim Zimmermann]
* fb09d2b  Settings: Align TotalRAMPreferenceController with MemoryUsagePreferenceController from dev settings  [Tim Zimmermann]
* eb30cfc  DeviceInfo: Add back SELinux status to About Phone  [mydongistiny]
* e870032  Settings: Add platform and RAM to Model & Hardware  [Rashed Abdel-Tawab]
* 86b5c4b  Settings: Reset battery stats [2/2]  [Jorge Ruesga]
* 53c7ab2  InstalledApp: Hide GooglePlay icon for webapps  [DarkJoker360]
* fdb2ded  Settings: Link smallest width options in display settings  [Subhajeet Muhuri]
* 8d280f7  Settings: Expose saved devices fragment via intent  [Adithya R]
* 6e95b26  Settings: default to GlifV3Theme  [Timi Rautamäki]
* e6de585  Port brightness slider changes [2/2]  [Pranav Vashi]
* ed03c64  Settings: DevicePicker: Adapt to S style  [ReallySnow]
* 6bf6098  development: Enable force resizable activities by default  [minaripenguin]
* b915657  development: Enable freeform windows by default  [minaripenguin]
* 6715a18  Settings: Long press to copy wifi password  [Ido Ben-Hur]
* bc4dffa  Settings: Remove divider from Battery Manager  [Akash Srivastava]
* 8aa2180  Settings: Observe auto brightness mode changes  [Ido Ben-Hur]
* e8577d2  Open app when clicking on icon in App Info  [deadman96385]
* a607bbb  InstalledApp: show link to Google Play  [George G]
* 84bc949  InstalledAppDetails: fix refreshing storage summary after force stop  [Altaf-Mahdi]
* 7100fd3  Expand abbreviation in average memory usage string  [Danny Lin]
* 139c701  Enable FeatureFlags on "user" builds too  [ezio84]
* a3d827f  Battery: Implement background process killer [2/2]  [Dil3mm4]
* f85287f  Allow to suppress notifications sound/vibration if screen is ON [2/2]  [ezio84]
* 27b4e5f  Settings: Add window ignore secure feature [2/2]  [LibXZR]
* 8ad912c  Settings: Add application downgrade feature [2/2]  [LibXZR]
* 01ac45a  Ignore custom app space management activities  [Danny Lin]
* c3899bf  FingerprintEnroll: Add config for dedicated side mounted fps  [Bruno Martins]
* 0e632e8  Settings: Introduce Smart Pause [2/2]  [Chris Crump]
* 7dea341  ButtonSettings: Remove split screen action  [jhenrique09]
* f1547b9  Settings: Long press power button to toggle flashlight [2/2]  [Chris Crump]
* 5dd5995  Settings: add TextView for summary into SeekBarDialogPreference  [cjybyjk]
* c3b9042  SoftAp: add Hidden SSID preference  [cjybyjk]
* df087e2  Settings: navigation mode settings [2/2]  [maxwen]
* e62e4d6  Settings: Add hide notch support [3/3]  [Henrique Silva]
* dbeff3a  Settings: Add three-fingers-swipe to screenshot [2/2]  [ghbhaha]
* cdd58ee  Settings: Implement hide gestural navigation hint bar [2/3]  [Jesse Chan]
* fda77a0  Settings: Changes for LiveDisplay  [Henrique Silva]
* 3aac0e3  Revert "Settings: Restore statusbar brightness preferences"  [someone5678]
* 6cfcbf9  Settings: StatusBarSettings: Drop all un-implemented features  [someone5678]
* e42e3b7  Settings: Import statusbar and others customizations  [Steve Kondik]
* a983664  Settings: Always show button settings  [Henrique Silva]
* 0660398  Settings: Incall vibration option [3/3]  [beanstown106]
* 833ea9c  Settings: Add misc haptics category  [someone5678]
* a02d6d5  Settings: Add toggle for heads up notifications  [Michael Bestas]
* 3a2b9c0  Settings: Add option to scramble pin layout when unlocking (1/2).  [Adnan]
* 9d6c8d3  Settings: Add setup UI for minimum delay between an app's notification sounds  [Danny Baumann]
* 24eee4f  Settings: display: Add wake on plug switch  [Jon Evans]
* 7b8af88  Settings: Add double tap to sleep preference  [Rashed Abdel-Tawab]
* 5e61fe6  Hide the "Show the vibrate icon in the Status Bar" setting  [Chirayu Desai]
* b36adc7  Settings: Add back increasing ring feature (2/2).  [Danny Baumann]
* 0bf274f  Settings: Configurable 0, 90, 180 and 270 degree rotation [2/2]  [kufikugel]
* f6077fa  Settings: Protect sensitive data on the about phone  [althafvly]
* dc84210  Settings: Add missing icons network and internet menu  [kleidione Freitas]
* ea19442  ButtonSettings: Add preferences for back key long press customization  [LuK1337]
* 51fe331  Settings: Add FastCharge preference into Battery settings  [Bruno Martins]
* 4fc11a7  ButtonSettings: Remove diff actions for go devices  [jhenrique09]
* b0af87b  SystemNavigationPreferenceController: Only show gestures if navbar visible  [jhenrique09]
* 6aff5ee  Settings: Fix ButtonBacklightBrightness dialog  [Andy CrossGate Yan]
* ffcf39f  KeyboardSettings: Add a RemotePreference for device-specific panel  [Bruno Martins]
* 47b83aa  Settings: Display: Add High Touch Polling Rate Support  [Ramii Ahmed]
* 19ba6ad  Settings: Improve touch gestures preferences  [jhenrique09]
* ece7b4d  Settings: Allow devices to provide remote gesture preferences  [Bruno Martins]
* 33d004c  Settings: Add high touch sensitivity and touchscreen hovering toggles  [LuK1337]
* e354ff7  Settings: Add preference for TouchGestures  [Anushek Prasal]
* ac4922e  ButtonSettings: Add a RemotePreference for device-specific panel  [Bruno Martins]
* 896a8a6  ButtonSettings: Add a setting to swap capacitive keys  [Arian]
* 014056d  Implement button settings  [jhenrique09]
* 702626c  Settings: add sim status listener in about phone  [hoffc]
* 2ac5923  SlicesDatabaseHelper: Use Build.VERSION.INCREMENTAL  [jhenrique09]
* ab593b6  Settings: Good news, `encryptable=footer` is broken  [Michael W]
* 6bfe8ba  Settings: Add switch for battery led  [jhenrique09]
* 0b65e12  Settings: Make NetworkScanHelper max search time customizable  [LuK1337]
* db3c0d8  Settings: Hide AOD pref is device provides Doze settings  [Bruno Martins]
* 50eaea2  Settings: Add a RemotePreference for device-specific doze settings  [Steve Kondik]
* b2a8649  Settings: Build custom-preference library  [jhenrique09]
* 0dd888f  fingerprint: Rework enrollment screen  [Bruno Martins]

#### tools/extract-utils

* 79a2a0f  extract-utils: Set install_symlink PREFIX based on installed_location  [Mashopy]

#### vendor/google/gms

* cd6771a  gms: Import SfpsOverlay for missing strings  [someone5678]
* 66020b7  gms: Import TrafficLightFaceOverlay  [someone5678]
* 3267038  gms: Use install_symlink for symlinks  [someone5678]

#### vendor/google/pixel-additional

* 7fc61dd  TurboAdapter_NoBatt: Use install_symlink for lib  [someone5678]

#### vendor/google/pixel-framework

* aa54b65  SystemUIGoogle: Update  [someone5678]
* 20547ec  SettingsGoogle: Add modification  [someone5678]
* a4d457b  SettingsGoogle: Import customisations  [someone5678]
* 9359f6a  Reapply "SettingsGoogle: Disable columbus sensitivity if using ap sensor"  [jhenrique09]
* f7e1844  SettingsGoogle: Update  [someone5678]

#### vendor/parasite/signatures

* 3057461  keys: Allow updating existing dir  [AnierinB]

#### vendor/qcom/opensource/usb

* 3c47c8c  init.qcom.usb.rc: Add support for DeviceAsWebcam feature  [Yumi Yukimura]

#### vendor/sony/sm8550-common

* 30f1b56  sm8550-common: Run setup-makefiles.sh  [someone5678]
* eee2c58  sm8550-common: Kill useless in device diagnostics  [someone5678]

### 06-23-2024

#### art

* 0f8e066  BACKPORT: Update product treble check for VNDK deprecation  [Tim Zimmermann]

#### frameworks/base

* c046d4a  base: Allow disabling slider haptic feedbacks [1/2]  [Ido Ben-Hur]
* 5e87687  Revert "VolumeDialogImpl: Handle cases where media controller is not available"  [someone5678]
* 3dd53b1  SystemUI: Correctly monet theme the new volume panel  [Ido Ben-Hur]
* 1433e65  DeviceConfigUtils: Add support for keep property's values  [someone5678]

#### hardware/qcom-caf/common

* b3f28a2  Introduce legacy FCM  [Michael Bestas]

#### packages/apps/Updater

* 3e5a79e  Catch exceptions when enabling performance mode  [Eamon Powell]

#### system/sepolicy

* 1a0d8d0  Resolve neverallow in retrofit devices  [Michael Bestas]

#### vendor/parasite/common

* 33bb0fe  PixelPropsUtils: Don't spood gms ui process  [someone5678]

#### vendor/parasite/signatures

* 5dd8c39  generate.sh: Use python script instead of prebuilt  [someone5678]
* c0c8f90  signatures: Add nfc key symlinks  [someone5678]
* deeb473  generate.sh: Correct output dir  [someone5678]
* bdd57e9  generate.sh: Don't generate avb_pkmd if already exists  [someone5678]
* aba2393  keys: Add nfc  [AnierinB]

### 06-22-2024

#### bootable/recovery

* df2fee8  recovery: allow formatting & mounting system on user builds  [Joker-V2]

#### build/make

* 6ff20c5  releasetools: Pass non-sparse super_empty.img to update_dynamic_partitions()  [Yumi Yukimura]
* 9eb16b3  Revert "releasetools: Support generating non-A/B RDAP Full OTA Package"  [someone5678]

#### system/sepolicy

* 547730d  Allow ignore neverallows in user builds  [Zhenxiang]
* af61944  sepolicy: allow fastbootd to operate devpts  [Randall Huang]
* 32deca7  sepolicy: allow system app to access sysfs_leds  [Marko Man]

#### vendor/certification

* 2c4c331  certification: Update  [someone5678]

#### vendor/google/dexopt_profiles

* a40d7d6  update-profiles.sh -> update-files.sh  [someone5678]

#### vendor/google/gms

* 5487298  gms: overlay: Move indicator configs to device_configs_propertyToKeep  [someone5678]

#### vendor/parasite/common

* 00ae528  PixelPropsUtils: Small update to isCallerSafetyNet  [someone5678]
* afa38c4  PixelPropsUtils: Allow disabling `onEngineGetCertificateChain` via prop  [Joey]
* 63dc681  PixelPropsUtils: Do not spoof gms to Pixel  [someone5678]

