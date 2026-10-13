# OttoCarLink

Android app that makes your phone act like a car head unit for an Ottocast box.
USB cable: phone (USB host / OTG) -> Ottocast box.

## Get the APK (no Android Studio needed)
1. Make a free account at github.com and create a new empty repository.
2. Upload all files of this folder (keep the `.github` folder!).
3. Open the repository -> Actions tab -> "Build APK" -> wait about 5 minutes.
4. Open the finished run -> Artifacts -> download `OttoCarLink-apk` (zip) -> unzip.
5. Copy `app-debug.apk` to the phone and install it (allow "unknown sources").

## Use
1. Phone must support USB OTG. Use a data cable (not charge-only). The phone
   powers the box, so use a powered USB hub if the box does not start.
2. Open the app, plug in the box, tap Connect, allow the USB permission.
3. Press the Log button to see what the box says. Send me that log if it does not work.

## Settings
Video size, fps and dpi are in `app/src/main/java/com/ottocarlink/Protocol.kt` (object Config).
Not done yet: microphone (Siri / calls), multi-touch.
