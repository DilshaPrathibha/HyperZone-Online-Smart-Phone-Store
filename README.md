# HyperZone

HyperZone is an Android shopping app for phones and accessories. The app includes onboarding, authentication screens, a main store experience, search, compare, cart, wishlist, orders, notifications, settings, and checkout screens.

## Project details

- **App name:** HyperZone
- **Package / Application ID:** `com.example.hyperzone`
- **Root project name:** HyperZone
- **Module:** `app`
- **Language:** Kotlin
- **Compile SDK:** 36
- **Target SDK:** 34
- **Minimum SDK:** 24
- **Java / Kotlin target:** Java 17 / `jvmTarget = "17"`
- **View binding:** enabled
- **Parcelize:** enabled

## Key dependencies (declared in `app/build.gradle.kts`)

- `androidx.core:core-ktx:1.13.1`
- `androidx.appcompat:appcompat:1.7.1`
- `androidx.constraintlayout:constraintlayout:2.2.1`
- `androidx.activity:activity-ktx:1.10.1`
- `androidx.fragment:fragment-ktx:1.8.9`
- `androidx.viewpager2:viewpager2:1.1.0`
- `com.google.code.gson:gson:2.13.1`
- `com.google.android.material:material:1.12.0`
- `androidx.core:core-splashscreen:1.0.1`

## Entry points

- **Application class:** `.MyApp` (from `AndroidManifest.xml`)
- **Launcher activity:** `.ui.SplashActivity`
- **Main activity:** `.ui.MainActivity`

## Screens and features

- Splash screen and onboarding
- Authentication: login and sign up
- Home, categories, product listing and details
- Search, compare, wishlist, cart, orders, notifications
- Settings and checkout (payment method and success screens)

## Project structure

- `app/src/main/AndroidManifest.xml` — manifest and activity declarations
- `app/src/main/java/` — application sources
- `app/src/main/res/` — layouts, drawables, values
- `app/build.gradle.kts` — module build configuration
- `settings.gradle.kts` — root project settings

## Build (local)

From the repository root using the included Gradle wrapper:

Windows (PowerShell):

```powershell
.
\gradlew.bat assembleDebug
```

macOS / Linux:

```bash
./gradlew assembleDebug
```

## Notes

- No license file was found in the repository.
- For implementation details, see `app/build.gradle.kts`, `app/src/main/AndroidManifest.xml`, and `app/src/main/res/values/strings.xml`.

---
Generated from workspace files on 2026-06-14.