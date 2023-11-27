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
  
8\**.Snapshots**
![Screenshot 2023-11-27 180213](https://github.com/SrinidhiVS/API-for-weather-forecast/assets/125716129/8b5f6a8f-0197-44ae-8013-f7cf932f2e52)
![Screenshot 2023-11-27 180245](https://github.com/SrinidhiVS/API-for-weather-forecast/assets/125716129/cfc446d1-2bc4-4d09-883d-c4e4ff9073fc)
![Screenshot 2023-11-27 180326](https://github.com/SrinidhiVS/API-for-weather-forecast/assets/125716129/7eb17f82-69cf-4624-936d-d1c1ac1173a4)
![Screenshot 2023-11-27 180316](https://github.com/SrinidhiVS/API-for-weather-forecast/assets/125716129/6ce86d68-a8de-43a1-a147-20de6f0f767d)
![Screenshot 2023-11-27 181158](https://github.com/SrinidhiVS/API-for-weather-forecast/assets/125716129/7b89000d-a492-4f2a-8b71-a48d3a01cc5a)
![Screenshot 2023-11-27 181224](https://github.com/SrinidhiVS/API-for-weather-forecast/assets/125716129/072e8882-e9f3-4d1d-92ea-c645aaf9db6e)

