# Weather Data System
This project is supposed to help you to create your own online weather service. It contains two major parts a Web UI that presents the current weather data to the user, and a server that provides a REST-API that is used to manage weather and user data. 

## Run the System 

The easiest way to run the complete system is to use docker-compose. Clone this repository `git clone --recurse-submodules https://github.com/ChristophBe/weather-data-system.git` and add the needed configuration files described in [weather-data-server](https://github.com/ChristophBe/weather-data-server) and  [weather-data-webapp](https://github.com/ChristophBe/weather-data-webapp).

With all configuration files added you can run `docker-compose up`
the Web UI will be exposed add `//localhost/` and the rest api can be accessed via `//localhost/api/`  
