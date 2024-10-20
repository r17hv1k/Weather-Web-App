# Weather Web App

#### Important: The api url(i.e, one call api 2.0) in ``script.js`` is not working as it was the older version. Just ignore it  and use other api call(which is free) or to use same features get the new version of one call api 3.0(subscription is needed).
The Weather Web App is a responsive web application designed to provide real-time weather forecasts for 7-days by default web location, and also for any city around the world. This app is built using HTML, CSS, and JavaScript, and it fetches weather data from the [OpenWeatherAPI](https://openweathermap.org/api). The user can search for the current weather conditions of a city and receive detailed information such as temperature, humidity, and atmospheric pressure.


## Prerequisites

Before you begin, ensure you have met the following requirements:  - You need to have a **web browser** installed. - You must have a **valid API key** from [OpenWeatherAPI](https://home.openweathermap.org/users/sign_up) to make requests.
## Features

- **Search by city:** Users can input a city name to get the current weather information.
- **Real-time weather:** Displays real-time weather data fetched from OpenWeatherAPI.
- **Weather details:** Provides temperature, humidity, wind speed, weather description, and other important weather metrics.
- **Responsive design:** Optimized for both desktop and mobile views.
- **User-friendly interface:** Simple and intuitive UI for ease of use.
## Installation

Follow these steps to get a local copy of the project up and running.

### 1. Clone the repository

```bash
git clone https://github.com/r17hv1k/Weather-Web-App.git
```
```bash
cd Weather-Web-App
```

### 2. Get your OpenWeatherAPI Key

You will need to create an account on the [OpenWeatherAPI](https://openweathermap.org/api) and generate an API key.

### 3. Configure the API Key

##### 1. Open the project files and locate the ```script.js``` (or similar configuration file).
##### 2. Replace the ```API_KEY``` placeholder with your OpenWeatherAPI key.

```js
const API_KEY = 'your_openweather_api_key';
```

### 4. Install dependencies
Depending on the tech stack used (e.g., Node.js, npm, etc.), install the required dependencies if necessary. If there are no dependencies, you can skip this step.

```bash
npm install
```

### 5. Run the app locally

If applicable, run the app using the command:

```bash
npm start
```
Alternatively, you can simply open the index.html file in a web browser to run the app.

## Usage

##### 1. Open the Weather Web App.
##### 2. Enter the name of the city you want to check the weather for.
##### 3. Click the search button or press "Enter."
##### 4. The app will fetch and display the current weather information for the specified city

## Tech Stack


* **HTML5** – Markup language for creating the structure of the app.
* **CSS3** – Styling and layout of the app.
* **JavaScript** – Handles dynamic content and API calls.
* **OpenWeatherAPI** – Provides weather data and forecast.
## API Reference

This app uses the OpenWeatherAPI to fetch weather data. To learn more about how the API works, visit the [OpenWeatherAPI](https://openweathermap.org/api) documentation.


## Contributing

Contributions are welcome! Follow these steps to contribute:

##### 1. Fork the project.
##### 2. Create a new branch ```git checkout -b feature/your-feature```.
##### 3. Commit your changes ```git commit -m 'Add some feature' ```.
##### 4. Push to the branch ```git push origin feature/your-feature```.
##### 5. Open a pull request.

## Acknowledgements

 - [OpenWeatherAPI](https://openweathermap.org/api) for providing the weather data.

```vbnet
Feel free to adjust the "Installation" and "Technologies Used" sections based on your project's actual setup. You might want to add more details or instructions depending on the frameworks, libraries, or deployment methods used.
```

## License

This project is licensed under the MIT license.
