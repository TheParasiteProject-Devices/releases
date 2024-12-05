# pdx234

### 12-05-2024

#### device/sony/pdx234

* f1ceb95  pdx234: nfc: Add config file for FeliCa (Type-F).  [kyasu]
* 4b89fc1  pdx234: Add kernel config file for pdx234  [kyasu]
* 1b1158c  pdx234: Decommonize some proprietary firmware blobs  [kyasu]

#### device/sony/sm8550-common

* 378f185  sm8550-common: fstab: Remove non-existent qmcs entry  [kyasu]
* a70f2c7  sm8550-common: Add FeliCa (NFC Type-F) support for yodo JP models  [kyasu]
* 9f2043d  sm8550-common: Decommonize some proprietary firmware blobs  [kyasu]
* ad71387  sm8550-common: Add Xperia 5 V family (pdx237) support  [kyasu]

#### frameworks/base

* a279533  wm: Show rounded corners on freeform window on internal display  [Adithya R]

#### kernel/sony/sm8550

* a3b5a22  arm64: configs: Add pdx23{4,7}.config for building split DTBs  [kyasu]

#### kernel/sony/sm8550-devicetrees

* 224acab  qcom: Add pdx237 DTB build support  [kyasu]
* dcba995  sm8550-devicetrees: pdx237: Unify compatible, qcom,msm-id tags  [kyasu]
* ed384fd  sm8550-devicetrees: Import pdx237 dts files from sony copyleft 67.0.A.8.xxx  [kyasu]

#### kernel/sony/sm8550-modules

* 920ea18  semc: sony_camera: Add dual camera support for pdx237  [kyasu]

#### packages/apps/Settings

* 6ac9323  Settings: Organize misc security and privacy settings  [someone5678]
* 6860410  fixup! Settings: Add additional security settings preference  [someone5678]
* c4cfa1c  fixup! Settings: Allow toggling privacy indicators [2/2]  [someone5678]
* 820040d  Settings: Avoid enforcing weird backgrounds  [El Dainosor]

#### vendor/sony/pdx234

* 3de27c5  pdx234: Sync to device  [someone5678]

#### vendor/sony/sm8550-common

* 7cf03f2  sm8550-common: Sync to device  [someone5678]

### 12-04-2024

#### packages/apps/Settings

* aec928d  Settings: Expose clipboard auto clear setting [2/2]  [Oliver Scott]

### 12-03-2024

#### device/sony/pdx234

* ca71b12  pdx234: Set TARGET_COLUMBUS_MODEL to crosshatch  [someone5678]

#### frameworks/base

* b2189a3  Settings: Expose clipboard auto clear setting [2/2]  [someone5678]

#### packages/apps/Settings

* 23f3b75  fixup! Settings: Add Glide library  [someone5678]

#### vendor/google/gms

* d4cd909  gms: configs: Add more camera apps to processKeep  [someone5678]
* 5159b4d  gms: Add flags to set columbus model  [someone5678]

### 12-02-2024

#### packages/apps/Settings

* 45c714a  Settings: Move extended/L back swipe to MainSwitchPreference  [someone5678]
* 4f10cb2  Settings: island: Move to MainSwitchPreference  [someone5678]

#### prebuilts/custom-sdk

* 7cd5d5d  custom-sdk: Add dummy manifest  [someone5678]
* 7bf4c82  Run ./gradlew generateBp  [someone5678]
* bea8c5b  custom-sdk: Initial configs for Lineage generateBp  [someone5678]
* c960d43  Initial commit  [someone5678]

### 12-01-2024

