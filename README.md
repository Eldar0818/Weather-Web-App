### Weather App using Python Flask and OpenWeather API
This is a simple weather app built with Python Flask that fetches weather data from the OpenWeather API. Users can input a city name, and the app will display current weather conditions.

### Features
1. City Search: Enter the name of a city to get real-time weather information.
2. Temperature Units: The app displays temperature in Fahrenheit.
3. Weather Conditions: You’ll see details like weather description, humidity, wind speed, and more.

### Prerequisites
Before you begin, ensure you have the following installed:
1) Python 3.x
2) Flask (pip install flask)
3) An API key from OpenWeather

### Getting Started
1. Clone this repository:
https://github.com/Eldar0818/Weather-Web-App.git
2. Create a virtual environment (optional but recommended):
cd weather-app
python -m venv venv
source venv/bin/activate
3. Install dependencies:
pip install -r requirements.txt
4. Set up your API key:
Create API_KEY in .env file with your actual OpenWeather API key.
5. Run the app:
flask run
6. Open your browser and navigate to http://localhost:5000.

### Usage
1) Enter a city name in the search box.
2) Click the “Get Weather” button.
3) View the weather details displayed on the page.

### Contributing
Contributions are welcome! If you find any issues or want to add new features, feel free to submit a pull request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.