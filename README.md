# Anti-EmuDetector
unlike method name hardcoded-based scripts such as this [script](https://codeshare.frida.re/@khantsithu1998/bypass-react-native-emulator-detection/), Anti-EmuDetector is a frida script that bypass the emulator detection techniques in android such as [device_info's flutter plugin](https://github.com/flutter/plugins/blob/8dca37e27f95617552b1a9f202dde75a914835ff/packages/device_info/android/src/main/java/io/flutter/plugins/deviceinfo/DeviceInfoPlugin.java#L82-L104) without relying on a hardcoded method name

# Usage

```
frida -U -f your.app.id -l script.js --no-pause 
```
