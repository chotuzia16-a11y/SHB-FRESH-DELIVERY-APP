# SHB Fresh Delivery — Cloud APK Build

This project is prepared for a GitHub Actions cloud build.

## Build APK from a phone

1. Create a GitHub repository.
2. Upload the contents of this project to the repository (including `.github/workflows/build-apk.yml`).
3. Open the repository → **Actions** → **Build Android APK**.
4. Tap **Run workflow**.
5. Wait for the workflow to finish.
6. Open the completed workflow run.
7. Under **Artifacts**, download **SHB-Fresh-Delivery-APK**.
8. Extract the downloaded artifact and install `app-debug.apk` on Android.

## Important
The current app uses local order storage. The UPI address in the source is a placeholder:
`shbfresh@upi`
Replace it with the real business UPI ID before accepting payments.


Gradle wrapper could not be generated in this environment.
