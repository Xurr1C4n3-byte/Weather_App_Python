# Weather App - Python Tkinter Mini Project

This is a simple Weather Application built with **Python** and **Tkinter**, using external APIs and libraries to display the current weather for a specified city. It includes time zone conversion and localized time display.

## Features

- GUI built with **Tkinter**
- City-based weather search
- Displays:
  - Temperature (in Celsius)
  - Weather condition and description
  - Wind speed
  - Humidity
  - Atmospheric pressure
  - Local time and time zone

## Requirements

- Python 3.9+
- Required Python libraries (install with `pip install`):
  ```
  pip install geopy pytz timezonefinder requests
  ```
- Get your OpenWeatherMap API Key:
  - Create a free account at https://openweathermap.org/
  - Go to your profile > API keys, and generate one.
  - Replace "your_api_key_here" in the code with your API key.
- Set your own user-agent:
```
geolocator=Nominatim(user_agent="myemail@gmail.com")  #Replace with your gmail account
```
- Make sure the following image files are in the same directory as your script:
  - search.png
  - search_icon.png
  - logo.png
  - box.png

## How to run
```
python Weather_App_Python.py
```



