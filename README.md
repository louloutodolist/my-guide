# TodoOfflineApp

This project wraps your offline to‑do HTML in an Android WebView.

## How to build an APK on GitHub
1. Upload this entire folder to a new GitHub repo at the repository root.
2. Ensure the workflow exists at `.github/workflows/build-apk.yml`. (If your OS hides `.github`, copy from `workflow-copy/build-apk.yml` into that path).
3. Put your HTML in `app/src/main/assets/index.html`.
4. In your repo, go to **Actions → Build APK (Debug) → Run workflow**.
5. After ~2–4 minutes, download the **app-debug** artifact (`app-debug.apk`) and install it on your Android phone.
