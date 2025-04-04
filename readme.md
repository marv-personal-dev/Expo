# Setting Up an Expo App

Follow these steps to set up an Expo app:

## Prerequisites
1. Install [Node.js](https://nodejs.org/) (LTS version recommended).
2. Install [Expo CLI](https://docs.expo.dev/) globally:
    ```bash
    npm install -g expo-cli
    ```
3. Ensure you have a code editor like [VS Code](https://code.visualstudio.com/).

## Steps to Create and Run an Expo App
1. Create a new Expo project:
    ```bash
    expo init my-new-project
    ```
    - Choose a template (e.g., "blank").
    - Navigate to the project directory:
      ```bash
      cd my-new-project
      ```

2. Start the development server:
    ```bash
    expo start
    ```

3. Open the app:
    - Use the Expo Go app on your mobile device (available on iOS and Android).
    - Scan the QR code displayed in the terminal or browser.

## Additional Tips
- To test on an emulator, install the required tools:
  - [Android Studio](https://developer.android.com/studio) for Android.
  - [Xcode](https://developer.apple.com/xcode/) for iOS (macOS only).
- To build a standalone app, refer to the [Expo build documentation](https://docs.expo.dev/build/introduction/).