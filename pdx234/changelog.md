# pdx234

### 10-10-2024

#### device/sony/pdx234

* 293f8c7  pdx234: Moving core 64 bit only makefile  [Shashank Sivakumar]

#### device/sony/sm8550-common

* 1c47b1f  sm8550-common: Switch to 64 bit only builds  [chandu078]
* ca1e342  sm8550-common: Drop libQnnHtpV73 and libQnnHtpV73Skel  [Luofan Chen]
* 129490a  sm8550-common: Add leds-qpnp-flash-common to modules.load list  [Luofan Chen]
* 7e258bc  sm8550-common: Drop soong configs for audio service  [Bruno Martins]
* 606bb9b  sm8550-common: usb_compositions: Move config to odm  [Bruno Martins]
* 1243167  sm8550-common: Move to OSS FM and HFP libs  [Bruno Martins]
* 3f1cd74  sm8550-common: Do not manually build dependencies  [Cosmin Tanislav]
* 221f0f3  sm8550-common: Add module suffix for prebuilts to avoid duplicated definitions  [someone5678]
* 914cad7  sm8550-common: Libraries are now automatically added to PRODUCT_PACKAGES  [Michael Bestas]
* 8ef8d05  sm8550-common: Remove elf files in copy files check  [Aaron Kling]
* 0a97455  sm8550-common: Resolve missing symbols on libqtikeymint  [Bruno Martins]
* 1027fde  sm8550-common: Work around using prebuilt HWC  [Michael Bestas]
* 885db80  sm8550-common: Work around using prebuilt audio primary HAL  [Bruno Martins]
* 431dad1  sm8550-common: Patch libwfdservice to resolve duplicate dependencies  [Michael Bestas]
* 7b35121  sm8550-common: Add dummy libqti-perfd-client to namespace  [someone5678]
* 58f7301  sm8550-common: Add dummy libidd to namespace  [someone5678]
* 3640efa  sm8550-common: Setup check ELF files  [Luofan Chen]
* 1e09da6  sm8550-common: Restore QSPM blobs  [someone5678]

#### kernel/sony/sm8550

* fe36513  ARM64: configs: Enable kprobes  [LuK1337]
* 4ad8c57  configs: sony: Enable Kallsyms  [someone5678]
* ed74358  drivers: qcom: Make CONFIG_QCOM_SOC_SLEEP_STATS_ON_SYSFS depend on DEBUGFS  [Luofan Chen]
* a0002bf  Makefile.lib: Lower kernel gzip compression to fastest  [Angelo G. Del Regno]
* b94aa33  configs: sony: Enable ZRAM writeback  [Luofan Chen]
* ca07c23  arch: configs: sony: Disable CONFIG_QCOM_SOC_SLEEP_STATS_ON_SYSFS  [Luofan Chen]
* 74c9db1  configs: Move sony specific config to its fragment  [Luofan Chen]
* 04635fd  sony: config: Use 1M for kernel log  [Juhyung Park]
* 2c249b2  sony: config: Disable most of the debugging configs  [Pranav Vashi]
* 6182ffe  sony: config: Disable wcd-usbss  [Bruno Martins]
* 164a927  sony: config: Unset all configs related with crow chipset  [Bruno Martins]
* e036e6b  power: Import wakeup_irq_debug driver  [Luofan Chen]
* 7bc67c1  ARM64: dts: vendor: Add symlink to sm8550-devicetrees  [Bruno Martins]
* 899c4c8  et6xx: Align implementation in sm8550  [Luofan Chen]
* a7b4a8e  et6xx: Remove reference to hardware_info  [Luofan Chen]
* 78c9bb5  drivers: sony: Import et6xx driver from 68.0.A.0.768  [Luofan Chen]
* 5d462c1  drivers: Import sony drivers to build inline  [Luofan Chen]
* 8301daf  tools/resolve_btfids: Skip unresolved symbol warning for empty BTF sets  [Kumar Kartikeya Dwivedi]
* a3c5f1b  minimal sony changes  [Luofan Chen]
* 8cbcad2  Merge tag 'KERNEL.PLATFORM.2.0.r1-19000-kernel.0' of https://git.codelinaro.org/clo/la/kernel/msm-5.15 into HEAD  [Bruno Martins]
* 736394e  Merge tag 'ASB-2024-10-05_13-5.15' of https://android.googlesource.com/kernel/common into HEAD  [Bruno Martins]
* 0140d0c  Merge tag 'ASB-2024-09-05_13-5.15' of https://android.googlesource.com/kernel/common into HEAD  [Bruno Martins]
* 0075dfa  Merge branch 'android13-5.15-lts' of https://android.googlesource.com/kernel/common into HEAD  [Bruno Martins]

#### kernel/sony/sm8550-modules

* c67a232  [TMP] cam_flash: Fix build  [someone5678]

#### vendor/sony/sm8550-common

* 3ba3239  sm8550-common: Switch to 64 bit only builds  [someone5678]

### 10-09-2024

#### device/sony/extra

* 18dee05  extra: Setup check ELF files  [someone5678]

#### device/sony/pdx234

* c0eb94e  pdx234: Disable ELF checks for some blobs  [someone5678]
* 7cdd66e  pdx234: Add module suffix to Camera_QNN blobs to avoid duplicated definition  [someone5678]
* 4646738  pdx234: Add dummy libqti-perfd-client to namespace  [someone5678]
* 4d54d6a  pdx234: Add dummy libidd to namespace  [someone5678]
* 67b589e  pdx234: Setup check ELF files  [someone5678]

#### frameworks/base

* e5643db  [SQUASH] Deprecates Google Sound Search tile  [someone5678]

#### packages/modules/Bluetooth

* 615fa8e  l2cap: Restore l2cu_send_peer_info_req  [someone5678]

#### vendor/google/gms

* 7b76ba6  gms: Run setup-makefiles.sh  [someone5678]
* ffe06ff  gms: Disable check ELF for shared object  [someone5678]
* eb6e375  gms: Run setup-makefiles.sh  [someone5678]
* d15d848  gms: Setup check ELF  [someone5678]
* 9b4149f  gms: Sync extract-files.sh to template  [someone5678]

#### vendor/google/mainline_modules

* ab060b2  mainline_modules: Run setup-makefiles.sh  [someone5678]
* 531602d  mainline_modules: Sync extract scripts to template and enable check ELF  [someone5678]

#### vendor/google/overlays/ThemeIcons

* 5d64d04  lawnicons: Update  [someone5678]

#### vendor/google/pixel-additional

* 91604f2  pixel-additional: Rename libpowerstatshaldataprovider  [someone5678]
* efbb810  pixel-additional: Add missing blobs  [someone5678]
* 407b2e2  pixel-additional: Update forgotten radio blobs  [someone5678]
* f7985ea  pixel-additional: Run setup-makefiles.sh  [someone5678]
* 49eafb9  pixel-additional: Merge separated extract scripts into one  [someone5678]
* e978bf0  pixel-additional: Run setup-makefiles.sh  [someone5678]
* 638cbf3  pixel-additional: Disable check ELF for shared objects  [someone5678]
* 09c1684  pixel-additional: Run setup-makefiles.sh  [someone5678]
* 982a193  pixel-additional: Sync extract scripts to template and enable check ELF  [someone5678]

#### vendor/google/pixel-framework

* 3e3efa5  pixel-framework: Run setup-makefiles.sh  [someone5678]
* ed037c6  pixel-framework: Sync extract scripts to template and enable check ELF  [someone5678]

#### vendor/parasite/prebuilts

* 588e0d1  prebuilts: Update Gramophone  [someone5678]

#### vendor/sony/extra

* dbb1e53  extra: Setup check ELF files  [someone5678]

#### vendor/sony/pdx234

* 37f5498  pdx234: Disable ELF checks for some blobs  [someone5678]
* 42607e7  pdx234: Add module suffix to Camera_QNN blobs to avoid duplicated definition  [someone5678]
* 37d564c  pdx234: Import dummy libqti-perfd-client to namespace  [someone5678]
* 2422e59  pdx234: Add dummy libidd to namespace  [someone5678]
* a7fc362  pdx234: Setup check ELF files  [someone5678]

#### vendor/sony/sm8550-common

* 4d4b8cb  sm8550-common: Move to OSS FM and HFP libs  [someone5678]
* 3208df4  sm8550-common: Add module suffix for prebuilts to avoid duplcated definitions  [someone5678]
* e985d93  sm8550-common: Resolve missing symbols on libqtikeymint  [someone5678]
* dabee9a  sm8550-common: Patch libwfdservice to resolve duplicate dependencies  [someone5678]
* 2259f06  sm8550-common: Add dummy libqti-perfd-client to namespace  [someone5678]
* 5737c42  sm8550-common: Restore QSPM blobs  [someone5678]
* e0780f8  sm8550-common: Add dummy libidd to namespace  [someone5678]
* c75a716  sm8550-common: Setup check ELF files  [someone5678]

### 10-08-2024

#### build/make

* 1d15d14  build: Allow installing APEX internal module to system  [someone5678]

#### packages/modules/Bluetooth

* 591e293  l2cap: Remove the code that sents extra packets  [Kavish Devar]
* f7a4eb3  Bluetooth: Make libbluetooth_jni platform available  [someone5678]

#### vendor/dolby

* 9df51f9  Run bpfmt  [someone5678]

#### vendor/google/gms

* c7d0604  Run bpfmt  [someone5678]

#### vendor/google/mainline_modules

* afffd66  Run bpfmt  [someone5678]

#### vendor/google/overlays/ThemeIcons

* 7d9d56c  lawnicons: Update  [someone5678]

#### vendor/google/pixel-additional

* 0063c53  Run bpfmt  [someone5678]

#### vendor/google/pixel-framework

* 9f1170b  Run bpfmt  [someone5678]

#### vendor/parasite/common

* 83ec081  Run bpfmt  [someone5678]

#### vendor/parasite/prebuilts

* 88c0986  Run bpfmt  [someone5678]
* 362a94c  prebuilts: Update Gramophone and Omni  [someone5678]

#### vendor/parasite/signatures

* 7ea8dd1  Run bpfmt  [someone5678]

### 10-07-2024

#### frameworks/base

* 37f3073  PhoneWindowManager: Add vibration when using physical camera button gesture  [blackshibe]

#### manifest

* 0f13063  manifest: parasite: Track packages/modules/Bluetooth  [someone5678]

#### packages/modules/common

* 58ffafb  Merge tag 'android-14.0.0_r74'  [someone5678]

#### vendor/aosp

* a4a80eb  vendor: Conditionally ship customized libbluetooth_jni to system  [someone5678]

### 10-06-2024

