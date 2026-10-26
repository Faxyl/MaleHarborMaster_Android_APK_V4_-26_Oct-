# Malé Harbor Master — Android APK Project
**Created by Ahmed Fazeel**

A 2D Maldives Port & Seaplane Control Game set across **Malé**, **Hulhulé (Velana International Airport)**, **Hulhumalé**, and the **Sinamalé Bridge**.

## Features Included
- **Path-Drawing Controls:** Touch and drag routes for Local Dhonis, Cargo Ships, and Maldivian Seaplanes.
- **Maldives Atoll Map:** Authentic layout with Malé Local Jetties (#1 & #2), Malé Commercial Harbour (SW), and Velana Water Runway.
- **Hulhangu Monsoon Storm Events:** Dynamic tropical squalls with slanted rain, lightning flashes, thunder, crosswinds, and harbour swells.
- **Multi-Level Uplifting Soundtrack:** 5 original Web Audio API themes (*Malé Sunrise*, *Velana Seaplane Breeze*, *Hulhumalé Express*, *Atoll Horizon*, and *Dhivehi Ocean Rush*) that change as you level up.
- **Immersive Fullscreen Android Wrapper:** Hardware-accelerated WebView (`mv.fazeel.maleharbormaster`) with Web Audio autoplay enabled, high-score `localStorage` persistence, and custom launcher icons.

## How to Generate the `.apk` File (3 Easy Ways)

### Option 1: Build in Android Studio (Local PC/Mac)
1. Extract this ZIP archive to a folder on your computer.
2. Open **Android Studio** and select **Open** -> choose the extracted `MaleHarborMaster_Android` folder.
3. Let Android Studio sync Gradle automatically, then click **Build > Build Bundle(s) / APK(s) > Build APK(s)** from the top menu.
4. Click **Locate** in the notification popup to get your installable `app-debug.apk` (`app/build/outputs/apk/debug/app-debug.apk`) and transfer it to your Android phone.

### Option 2: Zero-Install Cloud Build via GitHub Actions (No Android Studio Needed)
1. Create a free repository on GitHub and upload the contents of this folder.
2. Click the **Actions** tab in your GitHub repository -> select **Build Malé Harbor Master Android APK** -> click **Run workflow**.
3. In ~90 seconds, download `MaleHarborMaster-AhmedFazeel-APK` directly from the workflow summary page and install it on your phone!

### Option 3: Instant Install on Android Phone (PWA / Add to Home Screen)
1. Copy `app/src/main/assets/index.html` or host it on any static host (GitHub Pages, Netlify, Vercel).
2. Open it in **Chrome on Android**, tap the **⋮** menu, and select **Add to Home screen** / **Install app** to run it fullscreen like a native Android game.
