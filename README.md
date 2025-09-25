<img width="947" height="625" alt="490743562-9062240b-7e9b-4772-a4af-cb910b052f0d" src="https://github.com/user-attachments/assets/b3a19355-81ea-46b6-9af4-4a2f55ba77f8" />


# Live Weather Application

This is a simple, responsive web application that provides real-time weather information, including current conditions, a 5-day forecast, today's hourly forecast, air quality index, and sunrise/sunset times for any searched city.

## ✨ Features

*   **Current Weather**: Displays current temperature, sky description, city name, date, and time.
*   **Detailed Metrics**: Shows humidity, pressure, "feels like" temperature, and visibility.
*   **Air Quality Index (AQI)**: Provides readings for CO, SO2, O3, and NO2.
*   **Sunrise & Sunset Times**: Displays the local sunrise and sunset times.
*   **5-Day Forecast**: Presents a summary of the weather for the next five days.
*   **Today's Hourly Forecast**: Offers a breakdown of today's weather at specific hourly intervals.
*   **Responsive Design**: Optimized for viewing on various devices, from desktops to mobile phones, using Bootstrap.
*   **Dynamic Updates**: All weather data is fetched dynamically from the OpenWeatherMap API.

## 🚀 Technologies Used

*   **HTML**: For the structure of the web page.
*   **CSS**: For styling, including custom styles (`index.css`) and the Bootstrap framework.
*   **JavaScript**: For fetching data from APIs, processing it, and dynamically updating the DOM.
*   **OpenWeatherMap API**: Used to retrieve current weather, 5-day/3-hour forecast, and air pollution data.

## 🛠️ Setup and Installation

To get this project up and running on your local machine, follow these steps:

1.  **Clone the repository (if applicable):**
    ```bash
    git clone <repository-url>
    cd weather-app
    ```
    *(If you downloaded the files directly, skip this step and navigate to the project folder.)*

2.  **Obtain an OpenWeatherMap API Key:**
    *   Go to the [OpenWeatherMap website](https://openweathermap.org/api).
    *   Sign up for a free account.
    *   Navigate to your API keys section and copy your personal API key.

3.  **Update API Key in `script.js`:**
    *   Open the `script.js` file located in the project directory.
    *   Replace all occurrences of `d28274b5fe592e1f1e558103a5e66370` with your actual OpenWeatherMap API key.
    *   **Note**: There are three API calls in `script.js` that need to be updated:
        *   `fetchAQIData` function
        *   `nextFiveDays` function
        *   `todayTemps` function
        *   `fetchData` function (for current weather)

4.  **Open in Browser:**
    *   Simply open the `index.html` file in your preferred web browser. You can do this by double-clicking the file or by right-clicking and choosing "Open with...".

## 💡 Usage

1.  **Enter City Name**: Type the name of the city you want to check the weather for into the "Search City" input field.
2.  **Search**: Click the search icon next to the input field.
3.  **View Weather**: The application will display the current weather, forecast, and other details for the entered city.

---
