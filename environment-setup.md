# Environment Setup Documentation

## System Specifications
- **Operating System:** Windows 11, 64-bit
- **Processor:** Intel Core i7-9750H
- **RAM:** 16 GB
- **Storage:** 512 GB SSD
- **Graphics:** NVIDIA GTX 1660 Ti
- **Other Notes:** Any additional relevant hardware details

## Installed Software Versions
- **Node.js:** 20.19.5
- **npm:** 9.8.0 (or your installed version)
- **React Native CLI:** 0.72.3 (or your version)
- **Android Studio:** 2023.1.1
- **VS Code:** 1.91.0
- **Java JDK:** 20.0.1 (if used)
- **Android SDK & Tools:** Platform-tools 34.x, Build-tools 35.x, NDK 27.1.12297006
- **Other Software:** Any other tools you installed (optional)

## Setup Steps Followed
1. Installed Node.js and npm
2. Installed Android Studio and configured SDK paths
3. Set environment variables:
   - `ANDROID_HOME = %LOCALAPPDATA%\Android\Sdk`
   - Added `%LOCALAPPDATA%\Android\Sdk\platform-tools` to `PATH`
4. Created React Native project:
   ```bash
   npx react-native init EnvironmentTest
   cd EnvironmentTest


5. Ran the Android emulator

6. Ran the app:

npx react-native run-android


7. Verified app loaded successfully

Deviations from Instructions

Used npx react-native@latest init instead of older react-native init due to deprecation

Installed additional Android SDK components (NDK, CMake) automatically when prompted by Gradle

Overwrote existing README.md instead of creating a new one

Approximate Time Spent on Major Steps

Installing Node.js & npm: 5 minutes

Installing Android Studio & SDK: 25 minutes

Creating React Native project: 5–10 minutes

Running emulator & first app: 15 minutes

Debugging and configuration adjustments: 15–20 minutes