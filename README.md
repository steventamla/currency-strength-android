# Currency Strength Android APK

A separate Android WebView wrapper for the existing Currency Strength Meter website. It does not modify the existing web project or Market Activity Monitor.

The app opens https://currency-strength-meter-m1ro.onrender.com/ and uses the existing web app's interface and scoring behavior. Android WebView storage is separate from Chrome browser storage, so scores previously saved in Chrome will not automatically transfer to the APK. Network access is required to load the website.

## Build
GitHub Actions runs the workflow named "Build Currency Strength APK". After a successful run, download the currency-strength-debug-apk artifact and extract app-debug.apk. This is a debug APK for personal installation, not a Play Store release.
