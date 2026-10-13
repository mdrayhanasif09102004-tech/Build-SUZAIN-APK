# SUZAIN Android starter

This project wraps the supplied `SUZAIN_full_app_demo.html` in a simple Android WebView app and includes a GitHub Actions workflow to build a debug APK.

## Build in GitHub
1. Create a GitHub repository named `SUZAIN`.
2. Upload all files/folders from this project to the repository root.
3. Open **Actions** and allow workflows if prompted.
4. Run **Build SUZAIN APK** using **Run workflow**, or push to `main`.
5. Open the successful workflow run, scroll to **Artifacts**, and download `SUZAIN-debug-APK`.
6. Extract the ZIP and install `app-debug.apk` on your Android phone. If Android asks, allow installing apps from that source.

## Important
This is the first APK wrapper around the supplied HTML demo. Rooms, games, coin balance, gifts, VIP, and profile content are currently demo UI only. Real accounts, voice chat, payments, server-side wallet, moderation, and admin tools require backend services and additional implementation. This is a debug APK, not a signed Play Store release.
