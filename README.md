# Affirmations App

## Overview
Affirmations is a simple Android application that displays a scrollable list of positive affirmations along with inspiring images. This project demonstrates the implementation of scrollable lists in Android using Jetpack Compose.

## Features
- Display of affirmations in a scrollable list
- Each affirmation presented as a card with:
  - High-quality image
  - Affirmation text
  - Interactive button (placeholder for future functionality)
- Support for both light and dark themes
- Proper handling of system insets for edge-to-edge design
- Material 3 design components

## Technologies Used
- Kotlin
- Jetpack Compose
- Material 3 Design Components
- Compose LazyColumn for efficient scrolling lists

## Project Structure
```
com.example.affirmations/
├── data/
│   └── Datasource.kt         # Provides the list of affirmations
├── model/
│   └── Affirmation.kt        # Data class for affirmation items
├── ui/theme/
│   ├── Color.kt              # App color definitions
│   └── Theme.kt              # Theme configuration
└── MainActivity.kt           # Main activity and composable functions
```

## How It Works
1. `Datasource` provides a list of affirmations with texts and images
2. `AffirmationsApp` contains the main UI layout
3. `AffirmationList` renders each affirmation in a scrollable lazy column
4. `AffirmationCard` displays each affirmation as a card with an image, text, and button

## Setup Instructions
1. Clone the repository
2. Open the project in Android Studio
3. Build and run the application on an emulator or physical device

## Requirements
- Android Studio Flamingo or newer
- Minimum SDK: API 24 (Android 7.0)
- Target SDK: API 33
- Gradle version: 8.5

## License
This project is licensed under the Apache License 2.0 - see the LICENSE file for details.

