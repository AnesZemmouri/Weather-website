# Weather App

## Description

The Weather App allows users to search for current weather information for any city. It retrieves data from the OpenWeatherMap API and displays the weather details including temperature, humidity, and wind speed. The app also shows an appropriate weather icon based on the weather conditions.

## Features

- Search for weather by city name.
- Displays current temperature, humidity, and wind speed.
- Shows different weather icons based on the weather conditions (e.g., clear, rain, clouds).
- Provides error handling and user alerts for empty input and API errors.

## Technologies Used

- **HTML**: Structure of the web application.
- **CSS**: Styling of the application for both light and dark modes.
- **JavaScript**: Fetching data from the OpenWeatherMap API and handling user interactions.
- **OpenWeatherMap API**: Provides weather data.

## Setup

1. **Clone the Repository**

   ```bash
   git clone <repository-url>
   Navigate to the Project Directory
   ```

bash
Copy code
cd <project-directory>
Add Your API Key

Replace the placeholder API key in script.js with your own key:

javascript
Copy code
const apiKey = "your-api-key";
Open index.html in a Browser

Simply open index.html in your preferred web browser to start using the application.

Usage
Enter the name of a city in the search box.
Click the search button or press Enter to fetch weather data.
View the current temperature, humidity, wind speed, and a relevant weather icon.
Example
html
Copy code

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="boxicons.min.css" />
    <link rel="stylesheet" href="style.css" />
    <title>Weather</title>
  </head>
  <body>
    <div class="card">
      <div class="search">
        <input type="text" placeholder="Enter city's name" spellcheck="false" />
        <button class="search-btn">Search</button>
      </div>
      <div class="weather">
        <img src="images/weather-icon.png" class="weather-icon" />
        <h1 class="temp">22°C</h1>
        <h2 class="city">Madrid</h2>
        <div class="details">
          <div class="col">
            <img src="images/humidity.png" />
            <div>
              <p class="humidity">50%</p>
              <p>Humidity</p>
            </div>
          </div>
          <div class="col">
            <img src="images/wind.png" />
            <div>
              <p class="wind">15 km/h</p>
              <p>Wind Speed</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <script src="script.js"></script>

  </body>
</html>
Contributing
If you want to contribute to this project, please fork the repository and create a pull request with your changes. Contributions, bug fixes, and feature requests are always welcome!

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any questions or feedback, please contact Your Name.

Copy code 2. Add and Commit the README.md File
Stage the README.md File:

bash
Copy code
git add README.md
Commit the File:

bash
Copy code
git commit -m "Add README file" 3. Push the Changes to GitHub
Push the Commit:

bash
Copy code
git push origin main
If your default branch is named master instead of main, use master in place of main.

4. Verify on GitHub
   Go to your GitHub repository page and refresh it. You should now see the README.md file with your content displayed.
   Additional Notes
   Formatting: You can use Markdown syntax in the README.md file to format text, add images, links, and more.
   Updating: You can always edit the README.md file locally and repeat the add, commit, and push steps to update it on GitHub.
# Weather-website
