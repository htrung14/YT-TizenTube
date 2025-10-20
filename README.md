# YouTube-Branded TizenTube

A YouTube-branded version of TizenTube Cobalt with automated builds and auto-update functionality.

## Features

- ✅ **YouTube Branding**: App displays as "YouTube" with official YouTube logo
- ✅ **Automated Builds**: GitHub Actions automatically builds APKs on code changes  
- ✅ **Auto-Updates**: App can automatically check for and install updates
- ✅ **Ad Blocking**: Inherited from TizenTube Cobalt
- ✅ **SponsorBlock**: Skip sponsored segments automatically
- ✅ **Speed Control**: Adjust playback speed

## Download

Download the latest APK from the [Releases](https://github.com/htrung14/YT-TizenTube/releases) page.

## Auto-Updates

The app will automatically check for updates when launched. You can also manually check for updates in the app settings.

## Building

This project uses GitHub Actions to automatically build APKs. Every push to main/develop triggers a build, and releases are automatically created with signed APKs.

To build locally:
1. Set up Android SDK with NDK and CMake
2. Run: `cd starboard/android/apk && ./gradlew assembleDebug`

## Based On

This project is based on [TizenTubeCobalt](https://github.com/reisxd/TizenTubeCobalt) by reisxd.

## License

Inherits the BSD-3-Clause license from the original TizenTubeCobalt project.
