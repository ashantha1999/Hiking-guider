# Hiking Guider — Expo Android project

This project is configured to produce an installable Android APK using Expo Application Services (EAS Build).

## Build an APK (requires an Expo account and a computer or cloud development terminal)
1. Install Node.js LTS: https://nodejs.org/
2. Unzip this folder and open a terminal inside `Hiking-Guider-Expo`.
3. Run:
   ```bash
   npm install
   npm install -g eas-cli
   eas login
   eas build -p android --profile preview
   ```
4. If prompted, let EAS create/configure Android credentials.
5. When the cloud build finishes, open the build URL EAS prints and download the `.apk` to your Android phone.
6. Open the APK and allow installation from that source if Android asks.

## Important
- This ZIP is source code, not the APK itself. A cloud EAS build must complete to create the APK.
- Hiking locations and details in this prototype are demo data and may be approximate. Confirm trail access, permits, weather and route conditions locally before hiking.
- The map and navigation features may need further configuration/data before being suitable for real-world navigation.
