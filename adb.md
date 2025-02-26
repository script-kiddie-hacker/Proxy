# Android Debug Bridge (adb)

## Install adb
```sh
apt install adb
```

## Display help information
```sh
adb --help
```

## List connected devices
```sh
adb devices
```

## List devices with additional details
```sh
adb devices -l
```

## Connect to a remote adb device
```sh
adb connect 192.168.1.202:5555
```

## Open an interactive shell on the device
```sh
adb shell
```

## Install an APK file
```sh
adb install app-release.apk
```

## Uninstall an app by package name
```sh
adb uninstall com.example.exploit_app
```

## Pull a file from the device to a local directory
```sh
adb pull /sdcard/Download/Vida_app/Vida.apk /d-data/cobaltcore/PT28082/Vida.apk
```

## List running processes
```sh
adb shell ps
```

## List all running processes
```sh
adb shell ps -A
```

## Display thread information for processes
```sh
adb shell ps -T
```

## Monitor real-time system resource usage
```sh
adb shell top
```
