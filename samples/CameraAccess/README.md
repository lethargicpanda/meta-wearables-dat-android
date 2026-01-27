> **Note:** this repository is a fork of Meta's Android demo of "Meta Wearables Device Access Toolkit" to connect to the Meta Glasses.
> It include an integration of Gemini Live via [Firebase AI Logic](https://firebase.google.com/docs/ai-logic/live-api). 

# Camera Access App

A sample Android application demonstrating integration with Meta Wearables Device Access Toolkit. This app showcases streaming video from Meta AI glasses, capturing photos, and managing connection states.

## Features

- Connect to Meta AI glasses
- Stream camera feed from the device
- Capture photos from glasses
- Timer-based streaming sessions
- Share captured photos

## Prerequisites

- Android Studio Arctic Fox (2021.3.1) or newer
- JDK 11 or newer
- Android SDK 31+ (Android 12.0+)
- Meta Wearables Device Access Toolkit (included as a dependency)
- A Meta AI glasses device for testing (optional for development)

## Building the app

### Using Android Studio

1. Clone this repository
1. Open the project in Android Studio
1. Add your personal access token (classic) to the `local.properties` file (see [SDK for Android setup](https://wearables.developer.meta.com/docs/getting-started-toolkit/#sdk-for-android-setup))
1. Create a Firebase project and connect Firebase by adding a Firebase config file (`google-services.json`) to the `/app` directory. You can learn more about it in the [Firebase documentation](https://firebase.google.com/docs/ai-logic/get-started?platform=android&api=dev#set-up-firebase) and the [Android-specific setup guide](https://firebase.google.com/docs/android/learn-more?authuser=0#google-services-plugin-and-file).
2. Click **File** > **Sync Project with Gradle Files**
1. Click **Run** > **Run...** > **app**

## Running the app

1. Turn 'Developer Mode' on in the Meta AI app.
1. Launch the app.
1. Press the "Connect" button to complete app registration.
1. Once connected, the camera stream from the device will be displayed
1. Use the on-screen controls to:
   - Set stream time limits
   - Capture photos
   - View and save captured photos
   - Disconnect from the device

## Troubleshooting

For issues related to the Meta Wearables Device Access Toolkit, please refer to the [developer documentation](https://wearables.developer.meta.com/docs/develop/) or visit our [discussions forum](https://github.com/facebook/meta-wearables-dat-android/discussions)

## License

This source code is licensed under the license found in the LICENSE file in the root directory of this source tree.
