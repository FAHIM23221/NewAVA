# AVA OS

Futuristic AI companion app for Android - Kotlin, MVVM, Gemini Live voice,
emotion/personality engine, Room memory, ML Kit vision, overlay orb,
accessibility automation and wake word.

## How the source is stored here

The full Android Studio project (121 files) is stored as a base64-encoded ZIP
split into parts: `AVA_OS.zip.b64.part00` ... `part03`.
GitHub Actions reassembles, unzips and builds it automatically on every push.

To get the project locally: download all 4 parts, then run:

    cat AVA_OS.zip.b64.part* | base64 -d > AVA_OS.zip
    unzip AVA_OS.zip

## Get the APK

Open the **Actions** tab -> latest "Build AVA OS APK" run ->
download the **AVA-OS-debug-apk** artifact.

After installing, open the app Settings and add your own Gemini API key
for live voice features.
