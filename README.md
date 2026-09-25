# H2 Smart Hub

This repository contains the Android application only. The former React/Vite
website and its Node/Railway server are no longer part of the project.

## Android build

The Android app reads its Gemini key through the Secrets Gradle Plugin:

1. Copy [.env.example](.env.example) to `.env.local`.
2. Set `GEMINI_API_KEY` to the key used by the app.
3. Build or run the `app` module from Android Studio, or use `gradlew.bat :app:assembleDebug`.

`.env.local` is ignored by Git. The key is placed in the Android build
configuration, so do not commit it. Restrict the key in Google AI Studio to the
Android app's package and release certificate where possible.
