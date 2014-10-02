JTSHardwareInfo
===============

A convenient and thorough utility for referencing iOS device hardware information.

## Features

- **Comprehensive** – Includes hardwared identifiers for all iOS devices released by Apple, from the original iPhone to the iPhone 6 and 6 Plus.

- **AirDrop** – Check for general AirDrop availability.

## Supported Devices

Here's the current enum of all hardware types:

```objc
typedef NS_ENUM(NSInteger, JTSHardwareType) {
    
    JTSHardwareType_NotAvailable,
    JTSHardwareType_Simulator,
    
    JTSHardwareType_iPhone_Unreleased,
    JTSHardwareType_iPodTouch_Unreleased,
    JTSHardwareType_iPad_Unreleased,
    
    JTSHardwareType_iPhone,
    JTSHardwareType_iPhone_3G,
    JTSHardwareType_iPhone_3G_China,
    JTSHardwareType_iPhone_3GS,
    JTSHardwareType_iPhone_3GS_China,
    JTSHardwareType_iPhone_4_GSM,
    JTSHardwareType_iPhone_4_GSM_2012,
    JTSHardwareType_iPhone_4_CDMA,
    JTSHardwareType_iPhone_4S,
    JTSHardwareType_iPhone_4S_China,
    JTSHardwareType_iPhone_5_GSM,
    JTSHardwareType_iPhone_5_Global,
    JTSHardwareType_iPhone_5C_GSM,
    JTSHardwareType_iPhone_5C_Global,
    JTSHardwareType_iPhone_5S_GSM,
    JTSHardwareType_iPhone_5S_Global,
    JTSHardwareType_iPhone_6,
    JTSHardwareType_iPhone_6_China,
    JTSHardwareType_iPhone_6Plus,
    JTSHardwareType_iPhone_6Plus_China,
    
    JTSHardwareType_iPodTouch_1Gen,
    JTSHardwareType_iPodTouch_2Gen,
    JTSHardwareType_iPodTouch_3Gen,
    JTSHardwareType_iPodTouch_4Gen,
    JTSHardwareType_iPodTouch_5Gen,
    
    JTSHardwareType_iPad,
    JTSHardwareType_iPad_Cellular,
    JTSHardwareType_iPad_2_WiFi,
    JTSHardwareType_iPad_2_GSM,
    JTSHardwareType_iPad_2_CDMA,
    JTSHardwareType_iPad_2_Mid_2012,
    JTSHardwareType_iPad_3_WiFi,
    JTSHardwareType_iPad_3_GSM,
    JTSHardwareType_iPad_3_CDMA,
    JTSHardwareType_iPad_4_WiFi,
    JTSHardwareType_iPad_4_GSM,
    JTSHardwareType_iPad_4_Global,
    JTSHardwareType_iPad_Air_WiFi,
    JTSHardwareType_iPad_Air_Cellular,
    JTSHardwareType_iPad_Air_China,
    JTSHardwareType_iPad_Mini_WiFi,
    JTSHardwareType_iPad_Mini_GSM,
    JTSHardwareType_iPad_Mini_Global,
    JTSHardwareType_iPad_Mini_Retina_WiFi,
    JTSHardwareType_iPad_Mini_Retina_Cellular,
    JTSHardwareType_iPad_Mini_Retina_China,
};
```
