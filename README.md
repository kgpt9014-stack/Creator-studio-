# Creator Studio - Native Android Multimedia Suite

Built with Kotlin, Jetpack Compose, and Android Media3 Transformer.

## Features
- **Video Editor**: Preview, trim, playback speed (0.5x - 2.0x), split, filters, subtitle overlays, volume controls, and hardware-accelerated MP4 export to gallery.
- **Photo Editor**: Crop ratios (1:1, 4:5, 16:9, 9:16), rotate 90°, flip, brightness/contrast/saturation tuning, artistic filters, stickers, drawing canvas, and PNG/JPEG export.
- **Thumbnail & Design Maker**: YouTube 16:9 thumbnails, Reels/Shorts 9:16, post 1:1, editable multi-layers, badge elements, gradient backgrounds, and high-res export.
- **Collage Maker**: 2-photo, 3-photo, and 4-grid layouts with adjustable spacing and corner radius.
- **Audio Tools**: Waveform visualizer, audio trim, amplification gain, and WAV export.
- **Zero Cost**: 100% free, no subscriptions, no accounts, offline capable.

## How to Build APK
1. Open this directory in **Android Studio Ladybug (2024.2+)** or later.
2. Ensure Android SDK 35 (Android 15) and JDK 17 are installed.
3. Sync Gradle project.
4. Run or Build:
   - For Debug APK: `./gradlew assembleDebug` (Output: `app/build/outputs/apk/debug/app-debug.apk`)
   - For Release APK: `./gradlew assembleRelease`
