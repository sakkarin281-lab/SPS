# SPS — S.P. School Android Prototypes

โครงการต้นแบบ Android สำหรับเว็บไซต์ [S.P. School](https://sp-school-v5.vercel.app/#hub) (ไม่ใช่แอปอย่างเป็นทางการของโรงเรียน)

This repository contains the source archive `SP_School_GitHub_APK_Ready.zip` with two standalone Android Studio projects:
- `01_SP_School_WebView`: WebView app showing the public S.P. School site
- `02_SP_School_Native`: Native Android demo screens, with locally stored public information

**Build the APKs**:
1. Open the **Actions** tab in this repository.
2. Select **Build S.P. School Android APKs**.
3. Select **Run workflow** if necessary.
4. After the run completes successfully, download both named artifacts from its summary. Each artifact is a ZIP containing `app-debug.apk`.

This GitHub Actions workflow uses Java 17, Android SDK 35, Gradle 8.9, and Android Gradle Plugin 8.7.3. Debug APKs are for testing, not Google Play distribution. Source snapshot and school content should be verified before public release.

> GitHub Actions unpacks the committed source archive at build time. To edit projects, extract `SP_School_GitHub_APK_Ready.zip` locally.