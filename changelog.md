# Changelog 14/08/2026
- Update blobs from V816.0.34.0.ULIMIXM
- Update WFD system blobs from dada OS2.0.217.0.WOCMIXM
- Dropped Dolby Atmos blobs properties
- Include Dolby Atmos
- Sync with Spatial Audio
- Move c2_manifest_vendor.xml to device
- Import Dolby Media Codec
- Sync kernel to latest Source
- Add missing camera resource amd patch camera blobs
- Migrate to AIDL camera provider
- Build dynamic sensors hal
- Allow the sensor HAL to access dynamic sensor properties.
- Allow the sensor HAL to access raw HID devices.
- Shim libmisight with libjsoncpp_shim
- Switch to OSS libnotifyaudiohal
- Shim _ZN4Json5ValueC1Ex for libmisight

# Changelog 03/04/2026
- Bluetooth: Changing vendor ID as QTI for Device ID Profile
- audio: audio: Sync with audio_policy_configuration.xml
- Remove references to a2dp module
- audio: Fix disabling A2DP offload
- audio: Switch to AOSP BT stack
- Removing NfcOverlay
- audio: Increase max volume
- audio: Rework/cleanup on volumes
- audio: Import OOS modified volumes

# Changelog 23/03/2026
- Fix IMS and force enable telephony toggles
- Fix battery and USB OTG detection in recovery mode
- Unmount /firmware after fastbootd starts
- Disable high performance transitions
- FrameworkOverlay: Specify ambient color temperature sensor

# Changelog 18/02/2026
- Disable high performance transitions
- Specify ambient color temperature sensor
- Fix-up audio io policy voip_rx flags

# Changelog 06/02/2026
- Revert "sm8350-common: tetheroffload: Version 1.1"
- Shim libcodec2_hidl with libbase_shim
- Add GraphicBufferSource shim for libcodec2_hidl
- launcher3: Reduce blur radius
- Build missing libcamera_metadata.vendor

# Changelog 26/01/2026
- Prepend soong ns to lib_driver_cmd_qcwcn
- Enable support for kernel idle timer
- Restrict apps access to /proc/net/unix
- Switch to ssg i/o scheduler
- Add Diag framework matrix vintf configs
- Drop duplicate genfs_contexts entries
- Switch to SwitchPreferenceCompat
- Apply Expressive theme
- Defer applying divider
- Cleanup unnused configuration
- Update some soong config variables to bool type
