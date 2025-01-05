# Task Manager

This project implements a simple Android application using Jetpack Compose to demonstrate the usage of composables and alignment properties. The application showcases a "Task Completed" screen featuring an image and two text elements, centrally aligned on the screen. The application is based on the [Basic Android Kotlin Compose Practice Problems](https://developer.android.com/codelabs/basic-android-kotlin-compose-composables-practice-problems?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-compose-unit-1-pathway-3%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-compose-composables-practice-problems#2) codelab provided by Android Developers.

## Features

- Displays a central image and two text elements.
- Uses Jetpack Compose's `Column` for layout.
- Aligns content both vertically and horizontally in the center of the screen.
- Simple and clean UI design, ideal for beginners to understand Compose basics.

## Code Structure

### MainActivity.kt

This file contains the main logic of the app:

- `TaskCompletedScreen`: A composable function that creates the UI with an image and two text elements.
- `TaskCompletedPreview`: A preview function for design-time rendering in Android Studio.

## Components

### TaskCompletedScreen Composable

This composable displays:

- **Image**: Loaded using `painterResource`, representing the "Task Completed" status.
- **Text Elements**: A bold title "All tasks completed" and a subtitle "Nice work!" for positive reinforcement.

### TaskCompletedPreview

Allows previewing the `TaskCompletedScreen` in Android Studio to validate UI design.

## Dependencies

The app uses the following dependencies:

- **Jetpack Compose Material3**: For styling and theming.
- **painterResource**: To load images from resources.
- **Android Gradle Plugin**: To build and run the app efficiently.

## How to Run

1. Clone the repository or copy the project files into your Android Studio workspace.
2. Ensure you have the necessary tools installed (Android Studio, Kotlin, Emulator or Physical Device).
3. Open the project in Android Studio and sync Gradle.
4. Build and run the app on an emulator or physical device.

## Screenshots
![Alt Text]([image_url](https://drive.google.com/file/d/1CHtlkpmf59utguJLQJnTrcy2L9-wd0m6/view?usp=sharing))



## Learning Outcomes

By building this app, you will:

- Understand how to use `Column` and alignment properties in Jetpack Compose.
- Learn to load and display images using `painterResource`.
- Create responsive and visually appealing layouts.

## License

This project is provided for educational purposes under the Android Basics in Kotlin course. Feel free to use it for learning and personal development.

