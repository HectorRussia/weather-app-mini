1.create file file config.js 
2.in file below

const constants = {
    openWeatherMap: 
    {
        BASE_URL: "https://api.openweathermap.org/data/2.5/weather?q=",
        SECRET_KEY: "Your api KEY" <----
    }
}

module.exports = constants;