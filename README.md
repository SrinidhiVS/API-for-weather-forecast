**Weather API using Express and Axios Documentation**

**-SRINIDHI V S**

1\. **Introduction**

- This code demonstrates how to create a simple Node.js server using Express to fetch weather data from the OpenWeatherMap API.
- It utilizes Axios to make HTTP requests to the weather API endpoint.

2\**. Prerequisites**

- Node.js and npm must be installed on your system.
- An API key from OpenWeatherMap is required. Obtain it by signing up on their website and create a .env file to store the API key securely.

3\. **Code Explanation**

- Import necessary modules 
- Load environment variables
- Create an Express app 
- Load the API key from environment variables 
- Define the server port 
- Endpoint to fetch weather data 
- Fetch weather data from OpenWeatherMap API 
- Send HTML response with weather information 
- Start the server 

4\**. API Endpoint**

- Endpoint: GET /
- Description: This endpoint fetches weather data for the specified city using the OpenWeatherMap API.
- Parameters:
  - address: (Required) City name for which weather information is requested.

5\. **Usage**

- Ensure the server is running.
- **Send GET requests to http://localhost:3033/?address=cityName where cityName is the name of the desired city.**

6\. **Response**

- The response is an HTML page with weather information (City Name, Temperature in Celsius, and Sunset Time) for the specified city.

7\**. Error Handling**

- If an error occurs while fetching data from the weather API, a 500 Internal Server Error response is sent with an error message
