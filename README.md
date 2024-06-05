----------------------Simple Weather Application--------------------

This application allows users to fetch and display current weather information for a specified city. It includes features such as displaying the current system time, geo-coded address (placeholder), and saving the last searched city name using SharedPreferences.

------------------ Features------------------
- City Input: EditText for the user to input the city name.
- Fetch Weather: Button to fetch weather data.
- Geo-coded Address: Display the geo-coded address (placeholder).
- Current Time: Display the current system time.
- Weather Information: Display weather information including temperature, humidity, and weather description in a TextView.
- Data Persistence: Save and load the last searched city name using SharedPreferences.

-----------------Setup Instructions------------
1. Clone the repository.
2. Open the project in Android Studio.
3. Add your OpenWeatherMap API key in `MainActivity.java`:
   ```java
   private static final String API_KEY = "YOUR_API_KEY";
4. Build and run the application on an emulator or physical device.
