# OIBSIP_PYTHON-PROGRAMMING-_task-no-4

🎯 **Objective:**

To develop a beginner-friendly **command-line weather application** in Python that:

* Accepts a city name from the user
* Fetches current weather data using an API
* Displays temperature, humidity, and weather conditions
* Handles invalid input and errors gracefully
* Uses AI-style user interaction to simulate a helpful assistant

 🧰 **Tools Used:**

| Tool/Technology                  | Purpose                                                     |
| -------------------------------- | ----------------------------------------------------------- |
| **Python**                       | Main programming language                                   |
| **Requests library**             | To send HTTP requests to the weather API                    |
| **OpenWeatherMap API**           | Provides real-time weather data                             |
| **JSON library**                 | Parses API responses                                        |
| **Command-line interface (CLI)** | Enables user interaction                                    |
| **Try-Except blocks**            | Handles exceptions like network errors or invalid responses |
| **AI-like response logic**       | Adds friendliness and user guidance in the terminal         |


 🔄 **Steps Involved:**

1. **Set Up Environment:**

   * Install Python
   * Install required libraries (e.g., `requests`)

2. **Get Weather API Key:**

   * Register at [https://openweathermap.org/api](https://openweathermap.org/api)
   * Generate and copy the API key

3. **Write Python Script:**

   * Prompt user to input a city name
   * Validate the input (non-empty)
   * Use `requests` to send a GET request to the API with the city name and API key
   * Parse the JSON response to extract:

     * Temperature
     * Humidity
     * Description of weather (e.g., “clear sky”)
   * Display this information in a user-friendly format

4. **Add AI-Style Features:**

   * Personalized messages (e.g., “Hi! Let’s find your weather...”)
   * Handle errors with friendly messages (e.g., “Oops! Couldn’t find that city.”)

5. **Error Handling:**

   * Handle cases like:

     * No internet connection
     * Invalid city name
     * API failure

6. **Test and Run:**

   * Try with different cities (e.g., "Mumbai", "London")
   * Try invalid inputs (e.g., blank or gibberish)
   * Try disconnecting the internet to see error handling


 ✅ **Outcome:**

| Area                      | Description                                                                                           |
| ------------------------- | ----------------------------------------------------------------------------------------------------- |
| **Functionality**         | Successfully fetches and displays current weather data for user-specified cities                      |
| **User Interaction**      | Friendly, AI-style responses make it easy and engaging to use                                         |
| **Error Resilience**      | Graceful handling of API errors, invalid inputs, and connection issues                                |
| **Learning Outcome**      | User learns about API integration, JSON parsing, input validation, exception handling, and CLI design |
| **Extension Possibility** | Can be upgraded to GUI (Tkinter), add maps/GPS, or unit conversion for advanced users                 |

