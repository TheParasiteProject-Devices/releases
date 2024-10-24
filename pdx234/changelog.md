# pdx234

### 10-24-2024

#### device/xiaomi/mondrian

* cbef5f6  mondrian: Split large files  [someone5678]
* 9499250  mondrian: Enable xiaomi vibrator effect stream  [someone5678]
* 03c9b5a  mondrian: Use market name for PRODUCT_MODEL  [someone5678]
* 8bf8c94  mondrian: Use EEA fp and desc  [someone5678]
* e978b4f  mondrian: Inherit libinit  [someone5678]
* 5d657d4  mondrian: Parasitizing  [someone5678]
* 28dbda5  mondrian: Give execution permission to shell scripts  [someone5678]

#### device/xiaomi/sm8450-common

* 8c49fe9  sm8450-common: overlay: Enable dt2w support  [someone5678]
* 1f30147  sm8450-common: rootdir: Add usbotg to recovery fstab  [someone5678]
* 567a82c  sm8450-common: Import QCOM audio effects from OnePlus 9R  [someone5678]
* 2f6fb41  sm8450-common: audio: use QCOM Implementation for Audio Effects  [ANUSH MADATHUMKARA]
* 47461aa  sm8450-common: Switch to armv9-a ARCH variant  [Pranav Vashi]
* 2b57d63  [DEBUG] sm8450-common: Permissive  [someone5678]
* ab5bf7b  sm8450-common: BoardConfig: Set loop.max_part to 8  [someone5678]
* 3070e18  sm8450-common: Panic to recovery, not bootloader  [Peter Cai]
* 14ea189  sm8450-common: properties: Set frame rate multiple threshold to 120  [kubersharma001]
* a711022  sm8450-common: properties: audio: extend buffer size to 256kb for offload playback  [justinweng]
* 21d4a98  sm8450-common: props: Update volume steps props  [someone5678]
* 827afb5  sm8450-common: Build sounddose interfaces  [someone5678]
* 07db1da  sm8450-common: init: Give proper permissions for /dev/diag  [Yohan Black]
* 7b737ba  sm8450-common: rootdir: Kill WALT CPU boosting  [Sugakesshaa]
* 8dd4a1f  sm8450-common: Do not balance msm_drm and kgsl_3d0 IRQs  [Jake Weinstein]
* 87f48bc  sm8450-common: powerhint: Drop CPU freqs boosting on INTERACTION  [bheatleyyy]
* d9da38c  sm8450-common: powerhint: Follow taro's CPU freqs for little cluster  [bheatleyyy]
* 7a3235f  sm8450-common: powerhint: Adapt and tune for SM8475 (cape)  [bheatleyyy]
* 7daa0e7  sm8450-common: rootdir: Do not allow foreground tasks to run on CPU7  [Jake Weinstein]
* 0f7fdb7  sm8450-common: rootdir: Move background cpuset to CPU0-1  [Jake Weinstein]
* 1a79f2f  sm8450-common: rootdir: Set restricted cpuset to the same CPUs as system-background  [Jake Weinstein]
* 0608274  sm8450-common: rootdir: Enable powerhint parsing after boot completion  [Bruno Martins]
* 6ff9641  sm8450-common: Import powerhint.json from lahaina  [bheatleyyy]
* c654081  sm8450-common: Migrate to common libqti-perfd-client and power-libperfmgr  [Bruno Martins]
* c841ec8  sm8450-common: Remove QTI perfd  [Wei Wang]
* 3983e63  [DEBUG] sm8450-common: Log udfps vendor code  [someone5678]
* db460cb  sm8450-common: Include dtbo in recovery image  [LuK1337]
* 680fe7e  sm8450-common: configs: audio: Fix mic issues in apps like WhatsApp  [markakash]
* 72ba738  universal7885: configs: audio: Disable DRC  [roynatech2544]
* e58a111  sm8450-common: Remove FM Tuner from audio input devices  [iovxw]
* 7261f57  sm8450-common: configs: audio: Sync hotword input to primary input  [someone5678]
* a7c08ab  sm8450-common: configs: audio: Add hotword input for hotword mic concurrency  [Jasmine Cha]
* 932a0a6  sm8450-common: Update ERoFS LZ4HC compression rate to 12  [someone5678]
* 2723f6d  sm8450-common: Update EROFS PCLUSTER SIZE  [timocapa]
* f8165fd  Drop ext4 for userdata  [kondors1995]
* c762649  sm8450-common: fstab: Support F2FS compressions and garbage collector  [Panchajanya1999]
* afffbb2  sm8450-common: Enable LZ4 Compression for ramdisks  [Lisa Liu]
* 6fe4a34  BoardConfig: set erofs pcluster size  [John Galt]
* aaf5a2a  sm8450-common: move to erofs  [timocapa]
* 3508afd  sm8450-common: Use += for vintf inclusion  [someone5678]
* 70528f1  sm8450-common: Update partition flags  [someone5678]
* 029a3d4  sm8450-common: Reserve more space on /product  [LuK1337]
* 5a332a7  sm8450-common: Setup additional options for ota  [someone5678]
* b1c101d  sm8450-common: Include mainline common board config  [someone5678]
* 6f27761  sm8450-common: Enable blur  [someone5678]
* 5903860  sm8450-common: Build android.hardware.audio@7.1-impl  [someone5678]
* 1a53142  sm8450-common: Sync PRODUCT_SHIPPING_API_LEVEL with BOARD_SHIPPING_API_LEVEL  [someone5678]
* dd790ae  sm8450-common: Signing build with custom key  [someone5678]
* 3ea8223  Set BOOT_SECURITY_PATCH during build  [Garret Kelly]
* 69b7a9a  Set VENDOR_SECURITY_PATCH to platform  [Chris Fries]
* 2ff6ef3  sm8450-common: Parasitizing  [someone5678]
* 195b7ee  sm8450-common: Import missing AtFwd2 app  [Arian]

#### frameworks/base

* a776d78  services: Introduce Reality Display engine [1/2]  [minaripenguin]
* a7e75fb  Revert "services: Introduce X-reality display engine mode [1/2]"  [someone5678]

#### hardware/sony

* 591bba2  Revert "XperiaDisplay: Introduce X-Reality Engine"  [someone5678]

#### kernel/xiaomi/sm8450

* 23b462b  configs: mondrian: Enable Kallsyms  [someone5678]

#### kernel/xiaomi/sm8450-devicetrees

* c7b6a18  sm8450-devicetrees: cape/diwali: Move to erofs  [someone5678]

#### packages/apps/Settings

* c4dfce4  colors: Enable Triluminos Display engine  [someone5678]
* 44bef5e  colors: Introduce Reality display engine [2/2]  [minaripenguin]
* 0047506  Revert "Settings: Add color mode category"  [someone5678]
* ba9ae36  Revert "display: Introduce X-Reality Engine display mode [2/2]"  [someone5678]

#### vendor/google/overlays/ThemeIcons

* f8290f6  lawnicons: Update  [someone5678]

#### vendor/xiaomi/firmware/mondrian

* 1446f1a  mondrian: firmware: Don't remove original file  [someone5678]
* d9286dd  mondrian: firmware: Update  [someone5678]
* acb1ab7  mondrian: firmware: Split large files  [someone5678]
* e5e3cf6  mondrian: firmware: Add vendorsetup.sh  [someone5678]
* dd64053  Add .gitignore  [someone5678]

#### vendor/xiaomi/mondrian

* fe70fd5  mondrian: Update  [someone5678]

#### vendor/xiaomi/sm8450-common

* e34bd87  sm8450-common: Sync to device  [someone5678]
* 3a1617b  sm8450-common: Import QCOM audio effects from OnePlus 9R  [someone5678]
* 555c6db  sm8450-common: Do not balance msm_drm and kgsl_3d0 IRQs  [someone5678]

### 10-23-2024

#### device/xiaomi/sm6150-common

* c358f0b  sm6150-common: Build vbmeta_system image  [someone5678]
* b9f4701  sm6150-common: Add back legacy hidl android.hardware.bluetooth.audio for compat  [someone5678]
* 25b709e  sm6150-common: hidl: Update manifest version to 2.0  [someone5678]
* 6b5ad0d  sm6150-common: sm6150.mk -> common.mk  [someone5678]
* 888a78b  sm6150-common: Move to android.hardware.soundtrigger 2.3  [someone5678]
* 88d5d17  sm6150-common: Move to android.hardware.audio 7.1  [someone5678]

#### device/xiaomi/sweet

* 138eaf9  Add back google network modules  [someone5678]

#### kernel/xiaomi/sm6150

* bfbbf51  syscall: Fake uname to 4.19 also for netbpfload  [Tim Zimmermann]
* 1260a29  gen_headers_{arm, arm64}: Add btf.h to the list  [Cyber Knight]
* 2b9f55d  syscall: Fake uname to 4.19 for bpfloader/netd  [Tim Zimmermann]
* 3273876  BACKPORT: devmap: Allow map lookups from eBPF  [Toke Høiland-Jørgensen]
* 09fbd01  BACKPORT: xdp: Add devmap_hash map type for looking up devices by hashed index  [Toke Høiland-Jørgensen]
* 9075952  kernel: bpf: devmap: Create __dev_map_alloc_node  [Tim Zimmermann]
* 9d656e1  BACKPORT: bpf: Post-hooks for sys_bind  [Andrey Ignatov]
* 4bda20f  BACKPORT: bpf: Hooks for sys_connect  [Andrey Ignatov]
* 2b4c9f4f  BACKPORT: net: Introduce __inet_bind() and __inet6_bind  [Andrey Ignatov]
* ba4cb09  BACKPORT: bpf: Hooks for sys_bind  [Andrey Ignatov]
* bbf4268  BACKPORT: bpf: introduce BPF_PROG_QUERY command  [Alexei Starovoitov]
* 6c296ee  BACKPORT: bpf: Check attach type at prog load time  [Andrey Ignatov]
* 64f0226  bpf: offload: rename the ifindex field  [Jakub Kicinski]
* dcf0a7b  BACKPORT: bpf: offload: add infrastructure for loading programs for a specific netdev  [Jakub Kicinski]
* 337f634  BACKPORT: net: bpf: rename ndo_xdp to ndo_bpf  [Jakub Kicinski]
* 288755d  bpf: btf: fix truncated last_member_type_id in btf_struct_resolve  [Lorenz Bauer]
* 96f843b  bpf/btf: Fix BTF verification of enum members in struct/union  [Yoshiki Komachi]
* 2a63b39  bpf: fix BTF limits  [Alexei Starovoitov]
* f6e341e  bpf, btf: fix a missing check bug in btf_parse  [Martin Lau]
* fb7b873  bpf: btf: Fix a missing check bug  [Wenwen Wang]
* e5648e3  bpf: btf: Fix end boundary calculation for type section  [Martin KaFai Lau]
* 2cbb9f5  bpf: fix bpf_skb_load_bytes_relative pkt length check  [Daniel Borkmann]
* 9494be6  bpf: btf: Ensure the member->offset is in the right order  [Martin KaFai Lau]
* d2c28e0  bpf: btf: Clean up BTF_INT_BITS() in uapi btf.h  [Martin KaFai Lau]
* f85ebaf  bpf: btf: Fix bitfield extraction for big endian  [Okash Khawaja]
* 7e96dc5  bpf: btf: Ensure t->type == 0 for BTF_KIND_FWD  [Martin KaFai Lau]
* 8f07a0c  bpf: btf: Check array t->size  [Martin KaFai Lau]
* b54e83e  bpf: btf: avoid -Wreturn-type warning  [Arnd Bergmann]
* 8b438c6  bpf: btf: Avoid variable length array  [Martin KaFai Lau]
* f5bf3be  bpf: btf: Remove unused bits from uapi/linux/btf.h  [Martin KaFai Lau]
* d64a137  bpf: btf: Check array->index_type  [Martin KaFai Lau]
* cb84be9  bpf: btf: Change how section is supported in btf_header  [Martin KaFai Lau]
* 1a2da82  bpf: Fix compiler warning on info.map_ids for 32bit platform  [Martin KaFai Lau]
* 2496e5c  bpf: btf: Avoid WARN_ON when CONFIG_REFCOUNT_FULL=y  [Martin KaFai Lau]
* b0df631  BACKPORT: bpf: btf: Clean up btf.h in uapi  [Martin KaFai Lau]
* b8455fa  bpf: btf: Add BPF_OBJ_GET_INFO_BY_FD support to BTF fd  [Martin KaFai Lau]
* 7323684  BACKPORT: bpf: btf: Add BPF_BTF_LOAD command  [Martin KaFai Lau]
* dad4656  bpf: btf: Add pretty print capability for data with BTF type info  [Martin KaFai Lau]
* 847cc1dc  bpf: btf: Check members of struct/union  [Martin KaFai Lau]
* 7c8b0a3  bpf: btf: Validate type reference  [Martin KaFai Lau]
* cb8c3ce  bpf: Update logging functions to work with BTF  [Tim Zimmermann]
* 0c34c74  BACKPORT: bpf: btf: Introduce BPF Type Format (BTF)  [Martin KaFai Lau]
* 4d4a72c  BACKPORT: bpf: Rename bpf_verifer_log  [Martin KaFai Lau]
* 4d86b7d  BACKPORT: bpf: encapsulate verifier log state into a structure  [Jakub Kicinski]
* 98051e6  BACKPORT: bpf: add skb_load_bytes_relative helper  [Daniel Borkmann]

#### packages/modules/Connectivity

* 0812360  netd: Remove <4.14 kernel restrictions  [Michael Bestas]
* 51cc279  netbpfload: Support <4.14 kernels  [Michael Bestas]
* 4c4f8ad  netbpfload: Relax kernel version requirement  [Nanhumly]
* 384e0dc  NetBpfLoad: more 4.9-T support  [Maciej Żenczykowski]
* 517a271  netbpfload: add back support for 4.9-T kernels  [Maciej Żenczykowski]

#### vendor/google/mainline_modules

* a852ef8  mainline_modules: Move Google Cell Broadcast components  [someone5678]

### 10-22-2024

#### bootable/recovery

* 9fa4fd8  install: Allow selecting apk file  [someone5678]

#### device/sony/extra

* f462dc0  extra: Guard custom componenets  [someone5678]

#### device/xiaomi/sm6150-common

* a000e86  sm6150-common: Parasitizing  [someone5678]

#### device/xiaomi/sweet

* 279089f  sweet: sm6150.mk -> common.mk  [someone5678]
* 3e80279  Set VENDOR_SECURITY_PATCH to platform  [Chris Fries]
* 8685d6a  Set BOOT_SECURITY_PATCH during build  [Garret Kelly]
* 8b3d7d6  sweet: Setup libinit  [someone5678]
* 5057830  sweet: Disable unsupported mainline modules  [someone5678]
* 259eb57  sweet: Parasitizing  [someone5678]

#### frameworks/base

* 1b99af8  fixup! base: cmds: Add support for variant booanimation in non-product partition  [someone5678]

#### kernel/xiaomi/sm6150

* 7e769f0  sweet: Enable kallsyms  [someone5678]

#### vendor/google/gms

* f12c8e2  gms: Remove vendorsetup.sh  [someone5678]

#### vendor/sony/extra

* 424d173  extra: Guard custom componenets  [someone5678]
* 9db4ca7  extra: Remove vendorsetup.sh  [someone5678]

### 10-21-2024

#### build/soong

* 3c5dc01  soong: Whitelist jq  [someone5678]

#### vendor/certification

* 977d25b  certificaion: Remove vendorsetup.sh  [someone5678]

#### vendor/google/dexopt_profiles

* b0ed74a  dexopt_profiles: Update  [someone5678]

#### vendor/google/mainline_modules

* 1a1af9c  mainline_modules: Directly extract google-staged-installer-whitelist  [someone5678]
* e3e122f  mainline_modules: Allow to customize APEX certificate  [someone5678]

#### vendor/google/overlays/ThemeIcons

* 6dd139c  lawnicons: Update  [someone5678]

### 10-20-2024

#### device/lineage/sepolicy

* 3a02308  sepolicy: Label `ro.recovery.batteryless` property  [Yumi Yukimura]

#### device/sony/extra

* a148c0a  extra: Fix duplication  [someone5678]

#### device/sony/sm8550-common

* 60c15e7  fixup! sm8550-common: Declare EGL libs as symlinks during extraction  [someone5678]

#### device/xiaomi/sm6150-common

* 9146d14  sm6150-common: overlay-lineage: Disable turbulence noise  [basamaryan]

#### packages/apps/Settings

* a81435d  Settings: advanced: Allow to disable Pixel Launcher customisation  [someone5678]

#### vendor/custom-preference

* 63ee30b  YASP: OverlaySwitchPreference: Fixup wrong defStyleAttr  [Ido Ben-Hur]
* 33c659b  YASP: OverlaySwitchPreference: Allow config dkey on night mode only  [Ido Ben-Hur]

#### vendor/google/gms

* a3ccb09  gms: PixelLauncherBlurOverlay: Move to non-static  [someone5678]
* 2b0987c  gms: Separates blur customization from PixelLauncherOverlayCustom  [someone5678]
* 70bd23a  gms: Correctly generates symlinks for blobs  [someone5678]
* 010e74f  gms: Add .xml suffix to xml module names  [someone5678]

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

