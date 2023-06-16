# HA-auto-irrigation
Script to automate irrigation systems in Home Assistant based on weather.

1. Request API key at https://openweathermap.org
2. Configure OpenWeatherMap integration
3. Measure baseline running seconds for 10mm of simulated rain
4. Change user input variables to include baseline and wished precipitation for normal and hot days
5. Create automation using returned value as switch off delay
