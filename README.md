# Campus Navigator AI

Campus Navigator AI is an Android application designed to help students, staff, and visitors navigate a college campus more easily.

## Features

- Campus navigation and location guidance
- Easy-to-use mobile interface
- Quick access to campus-related information
- Android application support

## Technology Stack

- Kotlin
- Android SDK
- Gradle
- Android Studio

## Project Structure

```text
campus-navigator-ai/
├── app/
│   └── src/
├── gradle/
│   └── wrapper/
├── build.gradle.kts
├── settings.gradle.kts
├── gradle.properties
├── .env.example
└── README.md
```

## Requirements

- Android Studio
- JDK 21
- Android SDK
- Gradle 9.3.1

## Build Instructions

1. Download or clone the project.
2. Open the project folder in VS Code or Android Studio.
3. Ensure Java and Android SDK are configured.
4. Build the debug APK using Gradle.

On Windows PowerShell, run:

```powershell
& "$env:TEMP\gradle-9.3.1\bin\gradle.bat" assembleDebug
```

## APK Output

After a successful build, the APK will be available at:

```text
app/build/outputs/apk/debug/app-debug.apk
```

Transfer the APK to an Android device to install and test the application.

## Configuration

Check `.env.example` for the environment variables required by the project. Configure any required API keys or services before running the application.

If Google Services or Firebase is used, add the appropriate `google-services.json` file as required by the project configuration.

## License & Copyright

**Copyright © 2026 Elayanithish D. All Rights Reserved.**

Campus Navigator AI, including its source code, application design, UI/UX, documentation, and original project materials, is the intellectual work of Elayanithish D, except for third-party components and materials governed by their respective licenses.

**Restrictions:**

- No one may copy, reproduce, redistribute, or republish this project or substantial portions of its source code without prior written permission from the copyright owner.
- You may not claim this project or its original work as your own.
- You may not modify and redistribute this project, or use its original materials in another project, without prior written permission.
- This project is not released under an open-source license. Viewing the repository does not grant permission to reuse its contents.

Third-party libraries, frameworks, and dependencies remain subject to their respective licenses.

For permission to use or collaborate on this project, contact the copyright owner.

**Unauthorized use may result in legal action where permitted by applicable law.**
