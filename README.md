# Weather App

This Weather App is a simple web application that allows users to check the weather conditions for a specific city. It provides information such as temperature, humidity, and wind speed, along with a corresponding weather icon.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Weather Information:** Retrieve real-time weather data for a specified city.
- **Responsive Design:** The app is designed to be visually appealing and responsive on various devices, including desktops, tablets, and smartphones.
- **Error Handling:** Display an error message when the entered city is not found.

## Getting Started

Follow the instructions below to get a copy of the project up and running on your local machine.

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd weather-app
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

## Usage

1. Open the `index.html` file in your preferred web browser.

2. Enter the name of the city in the search input.

3. Click the search button to retrieve and display the weather information.

## Customization

- **API Key:** Replace the placeholder API key in `script.js` with your own OpenWeatherMap API key. Obtain an API key by signing up at [OpenWeatherMap](https://openweathermap.org/).
  
- **Images:** Ensure that the images for weather conditions (clouds.png, clear.png, rain.png, drizzle.png, mist.png) are available in the specified paths.

## Contributing

Contributions are welcome! Please follow the [Contributing Guidelines] for details on how to contribute to this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md] file for details.


## How It Works

The user enters a city name in the search input and clicks the search button.
The checkWeather function is triggered, which fetches weather data from the OpenWeatherMap API based on the entered city.
If the city is valid, it updates the UI with the weather information and displays the weather icon.
If the city is invalid or not found, it displays an error message.
The application is designed to be responsive with a clean and visually appealing interface.
Remember, the OpenWeatherMap API key used in the example may have usage limitations, and you should replace it with your own API key if you plan to use this code in a production environment.