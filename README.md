Realtime Clock with Date and Weather

Overview

This is a simple Python GUI application that displays the current time, date, and real-time weather updates for a specified city. The application is built using Tkinter for the user interface and fetches weather data from the OpenWeatherMap API.

Features

Live Clock: Updates every second to display the current time.

Live Date: Displays the current date.

Weather Updates: Fetches and displays the temperature and weather description for a specified city.

Error Handling: Handles API failures and network issues gracefully.

Prerequisites

Ensure you have Python installed on your system. You can download it from python.org.

Required Python Libraries

You need to install the following dependencies before running the script:

pip install requests

Installation & Setup

Clone the repository (or download the script):

git clone https://github.com/your-username/realtime-clock-weather.git
cd realtime-clock-weather

Set Up the API Key:

Obtain an API key from OpenWeatherMap.

Store it in an environment variable named OPENWEATHER_API_KEY for security.

On Windows (Command Prompt):

set OPENWEATHER_API_KEY=your_api_key_here

On macOS/Linux (Terminal):

export OPENWEATHER_API_KEY=your_api_key_here

Run the Application:

python main.py

Customization

Change the City: Modify the CITY variable in the script to fetch weather for your preferred location.

Modify the UI: Adjust font styles, colors, or layout in the Tkinter setup section.

Troubleshooting

Requests Module Not Found: Install it using pip install requests.

Weather Not Updating: Ensure your API key is valid and not exceeding the free tier limit.

Connection Issues: Check your internet connection and retry.

License

This project is open-source under the MIT License.

Author
Humphrey

