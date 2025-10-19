
# PyQt5 Weather App 🌤️

A simple, clean, and modern desktop weather application built with Python and the PyQt5 framework. It fetches real-time weather data from the OpenWeatherMap API and displays the temperature, a descriptive emoji, and a weather summary.




## Features

-   **Real-time Data**: Get the current temperature for any city in the world.
-   **Dynamic UI**: Displays temperature (°C), a weather description, and a matching emoji (e.g., ☀️, ☁️, 🌧️).
-   **Robust Error Handling**: Gracefully handles common errors like invalid city names, network issues, or API problems.
-   **Clean Interface**: A simple and intuitive user interface built with PyQt5.

## How to Run

To run this application on your local machine, follow these steps.

### Prerequisites

-   Python 3.x
-   An API key from [OpenWeatherMap](https://openweathermap.org/api). It's free!

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/parameswari019/PyQt5-Weather-App.git](https://github.com/parameswari019/PyQt5-Weather-App.git)
    cd PyQt5-Weather-App
    ```

2.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Add your API Key:**
    Open the `weather_app.py` file and replace the placeholder with your own API key.

    ```python
    # Find this line in the get_weather method:
    API_key="YOUR_API_KEY_HERE" 
    ```
   

4.  **Run the application:**
    ```bash
    python WeatherApp.py
    ```

## Technologies Used

-   **Python**: The core programming language.
-   **PyQt5**: For creating the desktop graphical user interface (GUI).
-   **Requests**: For making HTTP requests to the OpenWeatherMap API.
