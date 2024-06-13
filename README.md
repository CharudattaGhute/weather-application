# Weather Application

This is a simple weather application built using HTML, CSS, JavaScript, and Node.js. It fetches weather data from the OpenWeather API and displays related images for different weather conditions

## Features

- **Real-time Weather Data**: Utilizes the OpenWeather API to fetch real-time weather data for any location worldwide.
- **Dynamic Image Display**: Displays weather-related images dynamically based on the current weather conditions, providing users with visual cues.
- **Search Functionality**: Allows users to search for weather information for different locations, providing flexibility and convenience.
- **Responsive Design**: Offers a responsive design that ensures optimal viewing experience across various devices, including desktops, tablets, and smartphones.

## Installation

1. **Clone the Repository**: Begin by cloning the repository to your local machine:

    ```bash
    git clone https://github.com/CharudattaGhute/weather-application.git
    ```

2. **Navigate to Project Directory**: Move into the project directory:

    ```bash
    cd projectone
    ```

3. **Initialize the Project**: Initialize the project and create the `package.json` file:

    ```bash
    npm init -y
    ```

4. **Install Dependencies**: Install Express (if not already installed) and any other dependencies:

    ```bash
    npm install express
    ```

5. **Get API Key**: Obtain your API key from [OpenWeather]https://api.openweathermap.org/data/2.5/weather?units=metric&q=${city}&appid=replace `YOUR_API_KEY` in the `config.js` file.

6. **Start the Server**: Start the server using Node.js:

    ```bash
    node server.js
    ```

7. **View Application**:
- Open your preferred web browser and visit `http://localhost:9001` to access the application.

# Demo Video


https://github.com/CharudattaGhute/weather-application/assets/122104600/0ba55806-a9fc-46c9-88a2-0071f5b42e6e



## Usage

- **Search for Weather**: Enter the name of a city in the search bar and press Enter or click the search button to retrieve the current weather information for the specified location.
- **Visual Weather Representation**: View weather-related images alongside the weather information to get a visual representation of the current conditions.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
