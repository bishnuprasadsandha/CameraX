# Video Recorder with CameraX

A simple Android app that uses CameraX to record videos and save them to internal storage.

## Features

- Record videos using CameraX.
- Save videos to internal storage.
- Simple UI with a record button.

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/video-recorder-camerax.git

2. **Open the project in Android Studio.**

3. **Add necessary permissions in AndroidManifest.xml:**
    ```bash
   <uses-permission android:name="android.permission.CAMERA" />
    <uses-permission android:name="android.permission.RECORD_AUDIO" />
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />

4. **Request permissions at runtime if needed.**

Usage

    1. Press the "Record Video" button to start recording.

    2. Press again to stop recording.

    3. Find the saved video in the device’s internal storage under:
        data/data/com.yourapp/files
