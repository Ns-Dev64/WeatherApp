

---

# WeatherApp

WeatherApp is a simple Java application that fetches weather information from the OpenWeatherMap API based on the user's input location.

## Features

- **Get Weather**: Enter a location and click the "Get Weather" button to fetch weather information including temperature, weather description, longitude, and latitude.
- **GUI Interface**: Utilizes JavaFX for a simple and intuitive graphical user interface.
- **API Integration**: Uses the OpenWeatherMap API to retrieve real-time weather data.

## Getting Started

To run the WeatherApp project locally, follow these steps:

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/Ns-Dev64/WeatherApp.git
   ```

2. **Open in IDE**: 
   Open the project in your favorite Java IDE (such as IntelliJ IDEA or Eclipse).

3. **Build and Run**: 
   Build and run the `WeatherApp` class to start the application.

4. **Enter Location**: 
   Enter the location for which you want to fetch weather information in the text field.

5. **Get Weather**: 
   Click the "Get Weather" button to retrieve weather information for the specified location.

6. **VM Options**:
   Make sure to add the following to your VM options:
   ```
   --module-path "path/to/javafx-sdk/lib" --add-modules javafx.controls,javafx.fxml
   ```

   Replace `"path/to/javafx-sdk/lib"` with the path to your JavaFX SDK directory.

## Dependencies

- JavaFX: [Download JavaFX](https://download2.gluonhq.com/openjfx/20.0.1/openjfx-20.0.1_windows-x64_bin-sdk.zip)
- org.json (JSON processing library): [Download JSON](https://repo.mavenlibs.com/maven/org/json/json/20230618/json-20230618.jar?utm_source=mavenlibs.com)

## Contributing

Contributions are welcome! If you'd like to contribute to the WeatherApp project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m "Add new feature"`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

