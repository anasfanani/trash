# SM-A260G

## Device specs

|Name|Value|
|------------|------------|
|Codename | a2corelte|
|Model|SM-A260G|
|Name|Galaxy A2 Core|
|Country|Indonesia (XID)|
|OS Version|Android 8.1.0 Oreo|
|Build Date|25-10-2021|
|Product code|XID|

## Step by step

1. Download the `AP_A260GDDSCAUJ2_CL15641782_QB44812985_REV00_user_low_ship_meta.tar.md5`
2. Patch the file with Magisk 2004 ( I have blank screen issue after patch with new magisk 2600 ) , you can choose patch boot.img only or whole AP file
3. Make sure in developer option OEM UNLOCK is enabled, or you can see in download mode `KG STATE : Checking` not `KG STATE : Prenormal`, to enable it : Change date to manual -> connect wifi/data -> select update device from settings -> update until device is registered -> check developer option again, if not listed the `OEM UNLOCK` option, try reboot.
4. Flash with odin in AP Section.
5. Reboot and setup the phone, goto step 3 again and make sure OEM UNLOCK is enabled.
6. Open magisk app and setup first use, this will reboot your phone once. ( If oem unlock is not shown in developer option, your phone will failed to boot )
7. Done

## Notes 

https://samfw.com/firmware/SM-A260G/CAM/A260GDDSCAUJ2
