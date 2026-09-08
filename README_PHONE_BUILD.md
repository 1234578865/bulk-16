# Bulk 16 — Phone-only APK build

This project includes a GitHub Actions workflow at `.github/workflows/build-apk.yml`.

Phone-only method:
1. Create a GitHub repository in your mobile browser.
2. Upload the contents of this folder (not the outer folder itself).
3. Open the repo's **Actions** tab.
4. Select **Build Bulk 16 APK** and tap **Run workflow**.
5. When the run finishes, open the run and download the **Bulk16-debug-apk** artifact.
6. Extract the artifact and install `app-debug.apk` on your Android phone.

If GitHub asks for permission to run workflows, allow it for this repository.
