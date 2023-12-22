# WeatherApp
It's a weather app project for practicing javascript concepts. It's build using only HTML5, CSS3 &amp; Vanilla Javascript.
It uses OpenWeatherMap Api to fetch real time data from their servers and it's completely free.



### HTML (index.html)
The HTML file contains the structure of the web page. It includes the following key elements:

- **DOCTYPE Declaration**: Specifies the HTML version and document type.
- **Meta Tags**: Define the character set and viewport for responsive design.
- **Title**: Sets the title of the web page.
- **Link to Stylesheet**: Connects the HTML file to an external CSS file.
- **Body**: Contains the main content of the page, including a card with elements for search, error, and weather information.
- **Script Tag**: Links to an external JavaScript file.

### CSS (style.css)
The CSS file defines the styling for the web page. Here are the main styles:

- **Global Reset**: Removes default margin and padding and sets the font family.
- **Body Styling**: Sets the background color for the entire page.
- **Card Styling**: Defines the appearance of the main card, including width, background gradient, color, margin, border-radius, and padding.
- **Search Styling**: Styles the search bar, input field, and search button.
- **Weather Styling**: Defines the appearance of weather-related elements, including the weather icon, temperature, city name, and additional details.
- **Error Styling**: Styles the error message.

### JavaScript (script.js)
The JavaScript file contains the logic for fetching weather data and updating the UI. Here's a step-by-step explanation:

1. **API Key and URL**: Defines the OpenWeatherMap API key and base URL for weather data.
2. **DOM Selection**: Selects HTML elements using querySelector to interact with them in JavaScript.
3. **checkWeather Function**: This asynchronous function takes a city as a parameter, fetches weather data from the API, and updates the UI based on the response.
   - It uses the `fetch` function to make an asynchronous HTTP request to the OpenWeatherMap API.
   - If the response status is 404 (City Not Found), it displays an error message and hides the weather information.
   - If the response is successful, it parses the JSON data and updates the UI elements with the relevant weather information.
   - It also sets the appropriate weather icon based on the weather condition.
4. **Event Listener**: Listens for a click event on the search button. When clicked, it calls the `checkWeather` function with the city entered in the search input.

### How It Works
1. The user enters a city name in the search input and clicks the search button.
2. The `checkWeather` function is triggered, which fetches weather data from the OpenWeatherMap API based on the entered city.
3. If the city is valid, it updates the UI with the weather information and displays the weather icon.
4. If the city is invalid or not found, it displays an error message.
5. The application is designed to be responsive with a clean and visually appealing interface.

Remember, the OpenWeatherMap API key used in the example may have usage limitations, and you should replace it with your own API key if you plan to use this code in a production environment.