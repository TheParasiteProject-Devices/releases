# pdx234

### 10-21-2024

#### bootable/recovery

* d514267  install: Allow select apk file  [someone5678]

#### device/sony/extra

* f462dc0  extra: Guard custom componenets  [someone5678]

#### frameworks/base

* 1b99af8  fixup! base: cmds: Add support for variant booanimation in non-product partition  [someone5678]

#### kernel/xiaomi/sweet

* eae0969  syscall: Increase fake uname to 6.6.40  [Tim Zimmermann]
* 8727e54  syscall: Only fake uname on very first call of netbpfload  [Tim Zimmermann]
* c02a632  BACKPORT: bpf: fix unconnected udp hooks  [Daniel Borkmann]
* 75619b8  BACKPORT: bpf: enforce return code for cgroup-bpf programs  [Alexei Starovoitov]
* 0f6a03d  bpf: Hooks for sys_sendmsg  [Andrey Ignatov]
* 8f498ce  syscall: Increase bpf fake uname to 5.4.186  [Tim Zimmermann]
* 8b0704c  syscall: Increase bpf fake uname to 5.4  [Tim Zimmermann]

#### vendor/dolby

* 42e1ca5  dolby: Remove vendorsetup.sh  [someone5678]

#### vendor/google/dexopt_profiles

* b0ed74a  dexopt_profiles: Update  [someone5678]

#### vendor/google/gms

* f12c8e2  gms: Remove vendorsetup.sh  [someone5678]

#### vendor/google/mainline_modules

* 1a1af9c  mainline_modules: Directly extract google-staged-installer-whitelist  [someone5678]

#### vendor/google/overlays/ThemeIcons

* 6dd139c  lawnicons: Update  [someone5678]

#### vendor/sony/extra

* 424d173  extra: Guard custom componenets  [someone5678]
* 9db4ca7  extra: Remove vendorsetup.sh  [someone5678]

### 10-20-2024

#### build/soong

* 3c5dc01  soong: Whitelist jq  [someone5678]

#### device/sony/extra

* a148c0a  extra: Fix duplication  [someone5678]

#### device/sony/sm8550-common

* 60c15e7  fixup! sm8550-common: Declare EGL libs as symlinks during extraction  [someone5678]

#### packages/apps/Settings

* a81435d  Settings: advanced: Allow to disable Pixel Launcher customisation  [someone5678]

#### vendor/certification

* 977d25b  certificaion: Remove vendorsetup.sh  [someone5678]

#### vendor/custom-preference

* 63ee30b  YASP: OverlaySwitchPreference: Fixup wrong defStyleAttr  [Ido Ben-Hur]
* 33c659b  YASP: OverlaySwitchPreference: Allow config dkey on night mode only  [Ido Ben-Hur]

#### vendor/google/gms

* a3ccb09  gms: PixelLauncherBlurOverlay: Move to non-static  [someone5678]
* 2b0987c  gms: Separates blur customization from PixelLauncherOverlayCustom  [someone5678]
* 70bd23a  gms: Correctly generates symlinks for blobs  [someone5678]

#### vendor/google/mainline_modules

* e3e122f  mainline_modules: Allow to customize APEX certificate  [someone5678]

#### vendor/google/overlays/ThemeIcons

* 68dee84  PixelLauncherIconsOverlay: Add "icons" to package name  [someone5678]
* 992d1b2  PixelLauncherIconsOverlay: Move to non-static  [someone5678]
* 96ed100  lawnicons: Update  [someone5678]

#### vendor/google/pixel-additional

* 5b728a5  pixel-additional: Use libpowerstatshaldataprovider from gms directly  [someone5678]
* 2cee02d  TurboAdapter_NoBatt: Rename symlink  [someone5678]

#### vendor/sony/extra

* 155df89  extra: Fix duplication  [someone5678]

#### vendor/sony/sm8550-common

* f8edb86  fixup! sm8550-common: Setup check ELF files  [someone5678]

### 10-19-2024

#### device/sony/sm8550-common

* b3a0c4a  sm8550-common: Setup sim restart shell script  [egaunnac]

#### hardware/sony

* 31c02b7  sony: Setup sim restart shell script  [egaunnac]

#### vendor/google/gms

* 010e74f  gms: Add .xml suffix to xml module names  [someone5678]
* 720d418  device_config: Disable always screen on  [althafvly]
* 11716e6  device_config: Save discrete app op history for more permissions  [Danny Lin]

### 10-18-2024

#### device/sony/pdx234

* af293a4  pdx234: Update  [someone5678]

#### frameworks/av

* 8703e11  [TMP] av: prioritizes AUDIO_DEVICE_IN_BUILTIN_MIC over AUDIO_DEVICE_IN_BACK_MIC  [someone5678]

#### frameworks/base

* a1d972c6  SystemUI: Add ability to hide carrier name on lockscreen  [blackshibe]

#### hardware/xiaomi

* 0aa2ba8  dolby: Exempt installing package in clone or private space  [Pranav Vashi]

#### packages/apps/Settings

* 727c6c9  Settings: Add ability to hide carrier name on lockscreen  [blackshibe]

#### vendor/google/gms

* 45a8810  gms: Move google-staged-installer-whitelist to mainine_modules  [someone5678]

#### vendor/google/gms-common-proprietary

* 082f6b8  gms: Move google-staged-installer-whitelist to mainline_modules  [someone5678]

#### vendor/google/mainline_modules

* 99402f1  mainline_modules: Import Staged Installer config again  [Fede2782]
* c814683  mainline_modules: Update mainline_modules.mk  [Fede2782]
* 38f8f4e  mainline_modules: Make tethering optional  [Fede2782]
* d00014c  mainline_modules: DeviceLock is also optional in GMS  [Fede2782]
* e15e43b  mainline_modules: Guard Google NetworkStack  [someone5678]
* b69fef7  mainline_modules: Align with GMS  [Fede2782]
* be03a77  fixup! mainline_modules: Move NetworkStackGoogle under MAINLINE_INCLUDE_WIFI_MODULE flag  [someone5678]
* a1402fd  mainline_modules: Fix typo  [Fede2782]
* 97dd7ee  mainline_modules: Update overrides list to avoid duplicates from prebuilts/module_sdk  [hurtcopain]

#### vendor/sony/pdx234

* b4ea401  pdx234: Update  [someone5678]

#### vendor/sony/sm8550-common

* 821b250  sm8550-common: Update  [someone5678]

### 10-17-2024

#### bootable/recovery

* 9ab48c2  recovery_ui: Opt-out battery monitoring on battery-less devices  [Yumi Yukimura]

#### device/sony/sm8550-common

* ed7831c  sm8550-common: Set vendor.audio.3rd_mic_attached  [Luofan Chen]

#### external/libncurses

* 0ad6497  libncurses: Add recovery variant  [Yumi Yukimura]

#### external/nano

* 30d82ca  nano: Add recovery variant  [Yumi Yukimura]

#### kernel/sony/sm8550-devicetrees

* 4df0f58  sm8550-devicetrees: camera: Add thermal_names  [someone5678]

#### vendor/aosp

* 8857d0c  config: common: Build nano_recovery  [Yumi Yukimura]

#### vendor/google/overlays/ThemeIcons

* 243dde1  lawnicons: Update  [someone5678]

