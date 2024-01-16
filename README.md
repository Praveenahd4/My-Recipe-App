# MyRecipeApp

Welcome to MyRecipeApp! This Android application allows users to explore a variety of recipes from different categories using data from TheMealDB API. The app is built following the MVVM (Model-View-ViewModel) architecture, and it leverages Retrofit for API calls, Coroutines for asynchronous programming, and Flow for reactive data streams.

## Features

- **Recipe Categories**: Browse through a list of recipe categories fetched from TheMealDB API.
- **Grid Layout**: Categories are displayed in a lazy column with a 2-grid layout for an aesthetically pleasing user experience.
- **Recipe Details**: Tap on a specific category to view detailed information and recipes related to that category.
- **Asynchronous Programming**: Utilizes Coroutines for handling asynchronous operations, ensuring a smooth and responsive user interface.
- **Reactive Data**: Leverages Flow to handle reactive data streams and update the UI in response to changes.
- **Retrofit and JSON Parsing**: Implements Retrofit for making API calls and efficiently parses JSON responses to extract relevant data.

## Installation

1. Clone the repository
2. Open the project in Android Studio.
3. Build and run the app on an emulator or physical device.

## Tech Stack

- **MVVM Architecture**: Organizes the app into Model, View, and ViewModel components for a clean and maintainable codebase.
- **Retrofit**: HTTP client for making API calls to TheMealDB API.
- **Coroutines**: Asynchronous programming for managing background tasks.
- **Flow**: Reactive programming for handling data streams.
- **Lazy Column**: Jetpack Compose's lazy column is used for displaying recipe categories with a 2-grid layout.

