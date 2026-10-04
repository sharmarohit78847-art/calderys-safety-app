# Calderys Safety Android App

This project is ready for GitHub Actions.

## GitHub build
1. Upload the complete contents of this ZIP to the repository (including the `.github` folder).
2. Open **Actions**.
3. Select **Build Android APK**.
4. Press **Run workflow**.
5. After it finishes, download **CalderysSafety-debug**.

The workflow installs Android SDK 35 explicitly, uses Java 17, configures Gradle, builds the debug APK, and uploads the APK as an artifact.

## App content
- Plant search database
- Visitor journey
- Common safety rules
- 52 safety missions
- Offline-friendly bundled training data

Site-specific emergency numbers, assembly points, maps and restricted zones must be verified against approved plant information before operational use.
