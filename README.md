Exercise: Weather Forecast Retrieval Using HttpClient

In this exercise, you will practice using Apache HttpClient to retrieve weather forecast data from a weather API. Follow the guidelines below to complete the exercise:

### Guidelines:

1.  **Choose a Weather API**: Select a weather API that provides weather forecast data in JSON format. Some popular options include OpenWeatherMap, WeatherAPI, or any other weather API of your choice.
    
2.  **Register for an API Key**: Sign up for the chosen weather API and obtain an API key. The API key will be required to authenticate your requests to the API.
    
3.  **Maven Dependency:**
    

org.apache.httpcomponents httpclient 4.5.13

1.  **Write Java Code**: Write a Java program that uses Apache HttpClient to send an HTTP GET request to the weather API's endpoint for retrieving weather forecast data.
    
2.  **Include API Key**: Make sure to include your API key in the request URL as a query parameter or as part of the request headers to authenticate your requests.
    
3.  **Parse JSON Response**: Parse the JSON response received from the API to extract relevant weather forecast information such as temperature, humidity, wind speed, and weather conditions.
    
4.  **Display Forecast Data**: Display the retrieved weather forecast data to the user in a meaningful format, such as printing it to the console or displaying it in a graphical user interface (GUI).
    
5.  **Handle Errors**: Implement error handling in your code to handle cases where the API request fails (e.g., due to network issues, invalid API key, etc.). Provide informative error messages to the user when errors occur.
    
6.  **Test Your Program**: Test your Java program with different locations and verify that it retrieves accurate weather forecast data from the API.
