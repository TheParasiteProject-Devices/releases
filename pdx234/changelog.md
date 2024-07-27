# pdx234

### 07-27-2024

#### device/parasite/sepolicy

* d969184  parasite: sepolicy: Add cache cleaner script [2/2]  [someone5678]

#### device/sony/extra

* d131a5e  extra: sepolicy: Allow threesixtyra_app to create anon_inode  [someone5678]

#### device/sony/sm8550-common

* 26e499f  sm8550-common: wfd: Sync vendor.sys.media.target_variant to vendor.media.target_variant  [someone5678]
* 1a737e2  sm8550-common: wfd: enable mouse input for qcom wfd  [Chenyang Zhong]
* bb7105f  sm8550-common: wfd: Enable UIBC (User Input Back Channel) support by default  [someone5678]

#### device/xiaomi/sweet

* b823d00  [TEST] sweet: Build oss soundtrigger hal  [someone5678]
* 186cf38  sweet: Enable common xiaomi vibrator effect stream configs  [someone5678]

#### external/noto-fonts

* 93365b0  noto-fonts: Add Noto Emoji Addons  [Radosław Błędowski]
* 45a611e  noto-fonts: Add missing noto fonts  [Jyotiraditya Panda]

#### frameworks/base

* 593f7f7  SystemUI: Hide face unlock recognition animation on UDFPS devices  [someone5678]
* dae9371  data: Include NotoColorEmojiAddon font  [Radosław Błędowski]
* a920084  data: Add missing Noto fonts  [Jyotiraditya Panda]
* 6883766  Extends "base: Implement cutout force full screen [1/2]"  [someone5678]
* 181ffa9  fixup! Allow to suppress notifications sound/vibration if screen is ON [1/2]  [Pranav Vashi]
* c0ec9d5  base: Fix gamespace on secondary users  [Dhina17]
* 4a49fad  base: Fix NPE in GameManagerService  [Dhina17]
* 6813ade  GameManagerService: Prevent multiple threads from accessing settings observer onChange  [minaripenguin]
* 23daa2f  GameManagerService: Set device_config property on behalf of GameSpace  [Dhina17]
* cfecd99  SystemUI: Add support for GameSpace  [Nauval Rizky]
* f50b3fe  base: add API for disabling gestural navigation  [ezio84]
* 95c3ebd  Fix UDFPS icon and progress while enrolling  [Tobias Merkel]
* 31a3c6c  Fix pipe fds leak in copyInternalSpliceSocket  [hangl]
* 28792eb  [SQUASH] services: Boost gesture flings  [minaripenguin37]
* ca44a42  display: Don't reset brightness adjustment on clearUserDataPoints()  [LibXZR]
* 3eea6e4  PointerIcon: Add leniency to hotspot validation for scaled icons  [Prabir Pradhan]
* e159d40  CameraManager: Fix NPE in getting cameraIds  [afterallafk]
* f6c0860  SystemUI: IslandView: Use status bar height as top margin  [minaripenguin]
* c23ca89  fixup! SystemUI: Integrate Google Lens into Screenshot UI  [someone5678]
* 53d6e28  fixup! SystemUI: Allow using 4G icon instead of LTE [1/2]  [someone5678]
* 4616d3c  BluetoothDialog: Fix theme context  [Pranav Vashi]
* affb4e70  SystemUI: Allow skipping mirroring confirmation dialog [1/2]  [Sebastiano Barezzi]
* da9c60a  SystemUI: Disable FaceUnlock Lockouts [1/2]  [minaripenguin]
* c4e9e6d  fwb: Add missing android.permission.REGISTER_STATS_PULL_ATOM launcher3 permission  [karthik1896]
* cb2b4c2  Camera: Prevent crash with prebuilt camera metadata  [Pranav Vashi]
* 90ff20c  keylayouts: Nintendo ProCon: Map it like stock does  [Nolen Johnson]
* b72019f  LensScreenshotReceiver: Return when failed to start activity  [someone5678]
* 0009c7e  Import certification changes  [someone5678]
* f6f900c  Camera: Clearing exception for Extended Face  [Sauhard Pande]
* 5ed41cf  camera: Allow selected camera apps to skip unconfigure  [LuK1337]
* ff57ccf  Guard in short-circuit evaluations for stringSplit methods.  [Mohammed Irfan]
* b518b2c  Camera: Don't crash when trying to disable shutter sound  [jhenrique09]
* b5fcaed  Camera: Add feature extensions  [Sauhard Pande]
* 5d6ef33  Fix Photosphere/Camera FCs  [Jostein Kjønigsen]
* cb8c463  Allow sending vendor- or device-specific commands to the camera HAL.  [Danny Baumann]
* 3ddaa4e  Camera: Expose aux camera if packagename is null  [wbs306]
* 326b647  CameraDeviceImpl: Don't crash when checking input configuration failed  [Xayah]
* 84acb69  CameraManager: Prevent out of bounds when extracting camera IDs  [minaripenguin]
* 6f7db15  Camera: Extend face detection  [Shuzhen Wang]
* 3c0d5f8  base: Allow disabling slider haptic feedbacks [1/2]  [Ido Ben-Hur]
* 211e1e1  SystemUI: Correctly monet theme the new volume panel  [Ido Ben-Hur]
* 6a8b110  SystemUI: KeyguardUnlockAnimationController: Catch all exception  [someone5678]
* d10ce65  Squash of SystemUI: Show bluetooth battery level  [LuK1337]
* dff5205  core: jni: Add backwards compat methods for QCOM WFD  [LuK1337]
* a0f99d0  WiredAccessoryManager: replace every non digit character  [Francesco "Dil3mm4" Manzo]
* 7c5f68a  SystemUI: Fix build after recording changes  [someone5678]
* 54c45aa  code: ConfigurationController: Prevent an NPE  [minaripenguin]
* dcfbd9e  services: Introduce X-reality display engine mode [1/2]  [minaripenguin]
* 9da836c  Add keylayout for Xbox Wireless Controller  [Akshay Tigga]
* 5a05482  SystemUI: screenshot: Catch RejectedExecutionException  [someone5678]

#### frameworks/native

* 52d555f  [PATCH] Add simple FEAS support  [YuKongA]
* a7119c7  Differentiate between empty and unrecognizable display identification data  [Brian Lindahl]
* 4d701c2  Exit the loop after confirming the id  [Linnan Li]
* c63d38e  gpuservice: prevent hang in destruction  [Steven Moreland]
* 6db4405  SF: Don't enable expensive rendering for unknown dataspace  [Adithya R]
* 6e00898  IPCThreadState: Workaround to improve robustness  [johnmart19]
* 624e323  Native: Camera: Import Release Slot Xiaomi Changes  [johnmart19]
* 67d6b81  Native: ProducerListener: Import ON_BUFFER_DETACHED Changes  [johnmart19]
* d302642  SF: Defer setDesiredActiveMode when display is off  [Adithya R]
* be98cc9  Forward port 'Swap volume buttons' (2/3)  [nadlabak]
* e17772d  input: Bring back PointerProperties::copyFrom()  [Edwin Moquete]

#### hardware/sony

* c52359f  XperiaSwitcher: Redirect qs tile long click to RefreshRateSettingsActivity  [someone5678]
* 51ddae5  XperiaSwitcher: Add activity for handling QS tile long click action  [Nauval Rizky]
* ad526b7  sepolicy: Address wfd denials  [someone5678]

#### manifest

* c78deb4  manifest: parasite: Remove PhoneLink support  [someone5678]
* 501cce6  manifest: parasite: Track external/noto-fonts  [someone5678]

#### packages/apps/Settings

* 605c746  Extends "Settings: Implement cutout force full screen [2/2]"  [someone5678]
* e4a1103  fixup! Settings: Add support for disabling fingerprint lockout [2/2]  [someone5678]
* 69ac64f  Settings: Move to lowercase of "Apps" in Cloned Apps title  [someone5678]
* 4644239  Revert "Settings: Add Game Settings page"  [someone5678]
* fdfc141  fixup! Settings: Add status bar lyric [2/2]  [someone5678]
* 438587f  Setting: batteryinfo: Add config_show_battery_design_capacity & show_battery_maximum_capacity  [Asriadi Rahim]
* d504deb  Settings: Add Game Settings page  [someone5678]
* 733c2e7  Settings: Add a DEVICE field to the getSummary() function  [Quince]
* d6dee4f  fixup! Settings: Implement hide gestural navigation hint bar [2/3]  [someone5678]
* 164da51  fixup! Settings: Black theme [2/3]  [someone5678]
* a22fba8  fixup! Settings: Black theme [2/3]  [someone5678]
* 7ebbdf7  Settings: Remove qqs brightness slider tuning  [someone5678]
* 524a29f  Settings: Allow skipping mirroring confirmation dialog [2/2]  [someone5678]
* 19f5bfa  SystemUI: Disable FaceUnlock Lockouts [2/2]  [someone5678]
* 4162205  Revert "[Sim UI enhancement] remove the "Tap to show info""  [althafvly]
* 67c01a3  Settings: Move spoof storage encryption status to global settings  [someone5678]
* 7dac88c  Settings: Move window ignore secure to global settings  [someone5678]
* a2fde0c  Settings: display: Sync X-Reality Engine summary to hardware/sony  [someone5678]
* 4580b26  display: Introduce X-Reality Engine display mode [2/2]  [minaripenguin]
* fe9ee0f  Settings: Add color mode category  [someone5678]
* 1a4edb6  Settings: Forcefully enable Hotspot Speed setting  [someone5678]
* 5018e7d  WiFi: Remove country code checking.  [xyyx]
* 347a930  Settings: Move all custom security options to misc security settings  [someone5678]
* 691db31  Settings: Add additional security settings preference  [someone5678]
* 37421cb  ExternalStorageProvider: Conditionally remove SAF restrictions [2/2]  [someone5678]
* c47a637  DataProcessor: Do not skip and replace screen on component with screen on time  [minaripenguin]
* 255cbd4  NightDisplay Settings: Use List Preference for NightLight settings  [Akash]
* 940a579  DarkMode Settings: Use List Preference rather ugly Drop Down  [Pranav Vashi]
* d54bd8a  Settings: Allow to hide screen capture status from apps [2/2]  [someone5678]
* a393d99  Settings: Update Annoying Notifications title  [someone5678]
* b12cb48  Settings: Update Misc Haptics title  [someone5678]
* e232c49  CustomSettings: Remove un-implemented features  [someone5678]
* e4562f8  Settings: Generify custom project info props  [someone5678]
* 1828e62  Settings: Fix regulatory info availability check  [Ido Ben-Hur]
* 6e584d3  Settings: Add a dev option to unlimit screenrecord filesize [2/2]  [Ido Ben-Hur]
* 8d32b88  Settings: Update hide developer status strings  [someone5678]
* 7bc1f85  Settings: Update storage encryption status spoofing strings  [someone5678]
* e035719  Settings: Fix setting device name based on market name  [John Vincent]
* 4ec2e66  Settings: Set device name from marketname if available  [Pranav Vashi]
* 4f4cf67  Settings: deviceinfo: Move Battery info preference back to device info page  [someone5678]
* 68f256d  Settings: Add icon for emergency broadcasts  [Pranav Vashi]
* 5efdc6c  Settings: Add Market Name to device info  [someone5678]
* b919ae1  Make battery cycle count configurable and disable it by default  [Michael Bestas]
* 2e918cf  Hide unavailable battery info  [Michael Bestas]
* 49ecf68  Settings: deviceinfo: Extend Battery info page  [Jyotiraditya Panda]
* fb24665  Make battery info configurable and enable it by default  [Michael Bestas]
* 7caeb14  Settings: Use marketname for App Aspect Ratio summary  [someone5678]
* f8ac6cb  fixup! Add option to reset network settings to factory  [someone5678]

#### vendor/aosp

* be0de32  vendor: Disable vendor restrictions  [Luca Stefani]

#### vendor/google/mainline_modules

* f6a30c4  mainline_modules: Remove now-unexitsted overlays from makefile  [someone5678]

#### vendor/parasite/common

* b2e3e0f  vendor: Remove PhoneLink support  [someone5678]

#### vendor/sony/extra

* 0e539b4  GamingAccessorySettingsCustom: Reflect changes to resources  [someone5678]
* 5aff598  GamingAccessorySettingsCustom: Redirect to Game Space game library  [someone5678]

### 07-26-2024

#### build/make

* 6eee6db  Don't copy recovery.img to BOOTABLE_IMAGES if it doesn't exist  [Cosmin Tanislav]

#### device/qcom/sepolicy_vndr/sm8450

* 7aca987  sepolicy_vndr: Allow init/vendor_init to write proc firmware config  [Luofan Chen]
* fa391f7  sepolicy_vndr: Label proc firmware config node  [Luofan Chen]

#### device/sony/sm8550-common

* 434801f  sm8550-common: Move in wfd config  [someone5678]

#### manifest

* 9a73942  manifest: parasite: Track sm8450/8550 sepolicy_vndr  [someone5678]

#### packages/apps/GameSpace

* 4e90d7f  Fix ClassCastException during onNotificationPosted  [minaripenguin]

#### system/sepolicy

* dada8ea  Allow system server to access tmpfs files  [minaripenguin]
* 7c02cde  Allow ueventd to read apexd property  [Suchang Woo]
* b615112  sepolicy: Allow permissive in recovery on user builds  [Pranav Vashi]

#### vendor/sony/sm8550-common

* 6a0c7cc  sm8550-common: Move out wfd config  [someone5678]

### 07-25-2024

#### device/sony/sm8550-common

* 8dcbe53  Revert "sm8550-common: Add BUILD_BROKEN_INCORRECT_PARTITION_IMAGES"  [someone5678]

#### packages/apps/Updater

* 51ba8b5  Throw actual error when verifying imported updates  [Sefa Eyeoglu]

#### vendor/aosp

* 5a5c37c  kernel: Deduplicate file paths in file_list.txt  [LuK1337]

#### vendor/google/dexopt_profiles

* 7875b02  dexopt_profiles: Update  [someone5678]

#### vendor/google/pixel-framework

* 22c88cd  SettingsGoogle: Match Pixel UDFPS animation padding  [Jake Weinstein]

### 07-24-2024

#### device/sony/pdx234

* 6caac17  pdx234: gms: Copy EEA V2 device config  [someone5678]
* 0fe5722  pdx234: Matches fp and desc to stock EEA  [someone5678]

#### device/sony/sm8550-common

* 11bd55b  sm8550-common: Move DeviceAsWebcam resource to non-RRO  [someone5678]
* 79cda75  sm8550-common: Sync euicc setting to stock  [someone5678]

#### device/xiaomi/sweet

* 627d21b  sweet: Go back to ext4 for cache partition  [someone5678]
* 8922efb  sweet: gms: Increase back GBoard key size to 1.2  [someone5678]

#### hardware/xiaomi

* 27c92a0  vibrator: Add support for TEXTURE_TICK effect  [someone5678]
* 355bd63  vibrator: effect: libqtivibratoreffect: Add libc++fs to static libs  [someone5678]
* ebf4c15  hidl: biometrics: fingerprint: Set thread to high CFS priority  [Nauval Rizky]
* 8a7ad9d  interfaces: fxtunnel: Add fxtunnel 1.0 interface  [bengris32]
* 5f6129e  XiaomiEuicc: Remove references to EuiccPixel  [Bruno Martins]
* 127cf0d  XiaomiEuicc: Move to priv-app and grant required permissions  [someone5678]
* c9857c4  XiaomiEuicc: Disable EuiccGoogle when GMS and GSF are not installed  [Peter Cai]
* 7932f91  Introduce XiaomiEuicc  [Bruno Martins]
* 1049cca  dolby: Convert to SwitchPreferenceCompat  [Michael Bestas]
* c70d6ff  DolbyManager: Migrate to CompoundButton.OnCheckedChangeListener  [Chaohui Wang]
* a00eef1  dolby: Enable use_resource_processor for all sysui deps  [Peter Kalauskas]
* ce2b912  vintf: Add more hals to fcm  [Adithya R]
* ee089a5  xiaomi: Introduce Dolby Atmos  [Adithya R]
* 52f3657  vibrator: effect: Fallback to click if an effect is missing  [Adithya R]
* 23d201b  vibrator: effect: Create double click effect from click if necessary  [Arian]
* 27adc02  vibrator: effect: Read vibration fifo data from vendor  [Arian]
* 1b0f566  vintf: Remove transports from FCM  [Bruno Martins]
* ff205f1  vintf: Add synaptic interfaces to FCM  [Andrey Sprynga]
* 6154c8a  aidl: light: Add RGB sync support  [LuK1337]
* 342962c  aidl: light: Lower battery light priority  [LuK1337]
* a617d73  aidl: light: Support the `left` LED  [danielml]
* e2cc75a  aidl: light: Add support for button-backlight2 device  [LuK1337]
* ed42e89  aidl: light: Add support for timed mode  [Bruno Martins]
* 084bc1f  aidl: light: Refactor  [Sebastiano Barezzi]
* a8cc952  vintf: Add extra GoodixFingerprint interfaces  [Bruno Martins]
* 3078cfe  vintf: Add {goodix 2.1, fingerprintextension, motor} to fcm  [Arian]
* 9020cd6  aidl: Remove useless makefile  [Bruno Martins]
* 337f005  Move to common power-libperfmgr  [Michael Bestas]
* eca1ae3  hidl: biometrics: Add support for the fortsense fingerprint hal  [basamaryan]
* 010354a  power: Remove wakeup behavior from PowerHintSession and PowerSessionManager  [Matt Buckley]
* 1a13686  power: Add better tracing for sendHint and refactor existing tracing  [Matt Buckley]
* 0d88105  ADPF: refine StaleTimeHandler  [Jimmy Shiu]
* 030f713  ADPF: remove unused EarlyBoostHandler  [Jimmy Shiu]
* 5cffe03  vintf: Add fpc and goodix 1.0 extensions to fcm  [Arian]
* 3edf5ca  vintf: Add fingerprint extension to common fcm  [Jens Reidel]
* 4112b54  interfaces: fingerprints: extension: 1.0: Reverse the remaining interfaces  [Giovanni Ricca]
* b2f69de  interfaces: fingerprints: Initial reverse engineered 1.0 extension  [Erfan Abdi]
* 6190e45  interfaces: goodix: Initial reserve engineered 1.0 fingerprintextension  [bengris32]
* 71e7ea3  interfaces: goodix: Reverse the remaining calls  [Giovanni Ricca]
* cbc85de  vintf: Add common xiaomi framework compatibility matrix  [Arian]
* 336bc8e  sensors: Replace writepid with task_profiles command for cgroup migration  [Suren Baghdasaryan]
* 4de7116  megvii: libmegface -> libmegface_xiaomi  [Hazama25]
* a3160f0  megvii: Return a char pointer for some stubs instead  [Tim Schumacher]
* e052c90  megvii: Initial stub libraries  [Sebastiano Barezzi]
* d666a38  sensors: Add new single tap sensor node  [Fabian Leutenegger]
* dd1fc35  sensors: Implement Single Tap Sensor  [Cyber Knight]
* d346b22  sensors: Implement Double Tap Sensor  [Cyber Knight]
* 85baf68  sensors: Implement UDFPS Sensor  [Cyber Knight]
* e18a65e  sensors: Implement `GetPollPath()` and `IsPathValid()`  [Cyber Knight]
* ab07c8f  sensors: Create sysfs polling one shot sensor  [Cosmin Tanislav]
* a7b90e0  sensors: Add udfps long press sensor  [Cosmin Tanislav]
* eedd562  sensors: Fix locking around setOperationMode and activate  [Cosmin Tanislav]
* ad7be5e  sensors: Move one shot sensor out of main class  [Cosmin Tanislav]
* d31a213  sensors: Make sensor set mode operation function virtual  [Cosmin Tanislav]
* c386d65  sensors: Make sensor flush function virtual  [Cosmin Tanislav]
* 80e5b0b  sensors: Make sensor run function virtual  [Cosmin Tanislav]
* d34971b  sensors: Make sensor batch function virtual  [Cosmin Tanislav]
* b99468d  Add dummy sensors sub HAL  [Cosmin Tanislav]

#### vendor/google/gms

* 3b59b2c  fixup! gms: Add support for DSE search engine choice screen and EEA device features  [someone5678]

### 07-23-2024

#### device/xiaomi/sweet

* b45c8c6  sweet: sepolicy: Remove duplicated policies  [someone5678]
* cc95bf6  sweet: Explicitly disable "Enable GL comp backpressure"  [helliscloser]
* a258220  sweet: unset BOARD_USERDATAIMAGE_PARTITION_SIZE  [SGCMarkus]

#### hardware/sony

* 7e712f9  fixup! XperiaParts: Don't setup display HAL on boot if setting is disabled  [someone5678]

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

#### vendor/aosp

* 86566fa  build: Override host metadata  [Danny Lin]
* fd54f67  apns: Fix broken entries  [Sebastiano Barezzi]

