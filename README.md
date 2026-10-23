# proprietary_vendor_oneplus (hotdogg + sm8150-common)

Generated with LineageOS extract-files.py (kang mode, -k) from the OnePlus 7T Pro 5G McLaren (HD1925) OxygenOS 12 firmware
HD1925_11_F.04 (partitions vendor, odm, product, system, system_ext). The repo root is vendor/oneplus/.

Intentionally NOT included: firmware images (abl, xbl, modem, ...; the McLaren keeps its own), 4 Google hotword apps, and one
wifidisplaysession_aidl-V2-ndk.so that the McLaren firmware does not ship (it only has the HIDL wifidisplaysession@1.0).
Added for the McLaren (also in PixelOS working McLaren list): calibrationOutput_uw/wt.rc, vendor/etc/acdbdata/MTP/*.
Checked: every file referenced by the Android.bp / *.mk files exists, and no module is defined in both trees.
The common list was edited locally for this run only (WfdCommon.jar patch skipped: the McLaren jar already has the method).
Contains OnePlus/Qualcomm proprietary files from the owner own phone.
