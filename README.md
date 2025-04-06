# Backpack Flight Information UI

This project demonstrates a simple flight information user interface (UI) built using the Backpack Design System for Android. It showcases how to create visually appealing and consistent UIs following Skyscanner's branding guidelines.

## Overview

The app displays flight details in a card-based layout, including:

*   Flight Number
*   Departure Airport, Terminal, Gate and Time
*   Arrival Airport and Time

The UI is designed with a clean and modern look, utilizing Backpack components and styling to ensure a cohesive user experience.

## Technologies Used

*   Kotlin
*   Android SDK
*   Backpack Design System for Android
*   Gradle

## Setup Instructions

1.  Clone the repository:

    ```
    git clone https://github.com/devsbruno/backpack-flight-info-ui.git
    ```
2.  Open the project in Android Studio.
3.  Ensure you have the Android SDK and necessary build tools installed.
4.  Build and run the project on an emulator or physical device.

## Key Components

*   `BpkCardView`: Used to create the card-based layout for flight information.
*   `BpkText`: Used to display text with consistent styling and branding.
*   `ConstraintLayout`: Used to manage the layout and positioning of UI elements.

## Color Palette

*   **Background:** White (\#FFFFFF)
*   **Card Background:** Skyscanner Blue (\#0D72FF) - `bpkPrimary`
*   **Text:** White (\#FFFFFF) with varying opacities for different levels of emphasis.

## Typography

*   Titles: 18sp Bold with letter-spacing
*   Airport Codes/Times: 24sp Bold
*   Labels: 12sp (80% opacity)

## Layout Structure

The layout is structured using a `LinearLayout` within a `ConstraintLayout` to organize the flight information cards. Each card contains details for Flight Information, Departure, and Arrival.

## Dependencies

*   Backpack Design System:
    ```
    implementation 'net.skyscanner.backpack:backpack-android:<version>'
    ```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please submit a pull request or create an issue.

## License

[MIT License](LICENSE)

## Credits

*   Built with ❤️ by devsbruno

