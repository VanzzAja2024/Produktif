GRIND OS Android WebView project

Build using GitHub Actions:
1. Upload the contents of this folder to the root of a GitHub repository.
2. Ensure the workflow exists at .github/workflows/build-apk.yml.
3. Open Actions > Build GRIND OS APK > Run workflow.
4. When complete, open the run and download GRIND-OS-APK.
5. Extract the downloaded artifact ZIP and install app-debug.apk on Android.

The HTML is bundled at app/src/main/assets/index.html.
The app uses WebView and requires internet for the original HTML's CDN libraries/fonts.
Local browser storage is retained by WebView. HTML timers may pause when Android backgrounds or closes the app; this build does not provide guaranteed background alarms or native notifications.
