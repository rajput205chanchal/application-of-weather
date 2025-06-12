const weatherInput = document.querySelector(".search-input");
const searchButton = document.querySelector(".search-button");

const weatherInfo = document.querySelector("#weather-info");

const cityName = document.querySelector("#city-name");
const weatherLocation = document.querySelector("#weather-location");
const weatherTemperature = document.querySelector("#weather-temperature");
const weatherDescription = document.querySelector("#weather-description");
const sunrise = document.querySelector("#sunrise");
const sunset = document.querySelector("#sunset");
const humidity = document.querySelector("#humidity");
const windSpeed = document.querySelector("#wind-speed");
const pressure = document.querySelector("#pressure");
const visibility = document.querySelector("#visibility");
const cloudiness = document.querySelector("#cloudiness");

const convertUnixTimestampToTime = (timestamp) => {
  const date = new Date(timestamp * 1000);
  const hours = String(date.getHours()).padStart(2, "0");
  const minutes = String(date.getMinutes()).padStart(2, "0");
  return `${hours}:${minutes}`;
};
weatherInfo.style.display = "none";

searchButton.addEventListener("click", async () => {
  const apiKey = "066828f1425519ba1a18462a6aa1ab79";
  const city = weatherInput.value.trim();

  if (!city) {
    alert("Please enter a city name");
    return;
  }

  try {
    const url = `https://api.openweathermap.org/data/2.5/weather?q=${city}&units=metric&appid=${apiKey}`;
    const response = await fetch(url);
    const data = await response.json();

    if (data.cod !== 200) {
      alert("City not found, please try again.");
      return;
    }

    cityName.textContent = `Weather in ${data.name}`;
    weatherLocation.textContent = `Location: ${data.name}`;
    weatherTemperature.textContent = `${data.main.temp}°C`;
    weatherDescription.textContent =
      data.weather[0].description.charAt(0).toUpperCase() +
      data.weather[0].description.slice(1);
    sunrise.textContent = `Sunrise: ${convertUnixTimestampToTime(
      data.sys.sunrise
    )}`;
    sunset.textContent = `Sunset: ${convertUnixTimestampToTime(
      data.sys.sunset
    )}`;
    humidity.textContent = `Humidity: ${data.main.humidity}%`;
    windSpeed.textContent = `Wind Speed: ${data.wind.speed} m/s`;
    pressure.textContent = `Pressure: ${data.main.pressure} hPa`;
    visibility.textContent = `Visibility: ${data.visibility / 1000} km`;
    cloudiness.textContent = `Cloudiness: ${data.clouds.all}%`;

    weatherInfo.style.display = "block";
  } catch (error) {
    console.error("Error fetching weather data:", error);
    alert(
      "An error occurred while fetching the weather data. Please try again."
    );
  }
});
