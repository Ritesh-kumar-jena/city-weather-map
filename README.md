# City Weather Map

City Weather Map is a simple and interactive weather forecasting web application. It allows users to search any city and instantly view current weather details, temperature, wind, clouds, sunrise/sunset time, and a 5-day forecast. The app also displays the selected city on an embedded Google Map.

## 🔗 Deployed Link

👉 [Live Demo](https://city-weather-map-by-ritesh.netlify.app/)


## Screenshot

![City Weather Map Screenshot](https://res.cloudinary.com/dy9gltg7s/image/upload/v1762710829/Screenshot_2025-11-09_232156_qgtt0a.png)

## Features

- Search weather by city name  
- View current temperature, min/max temperature, wind speed, clouds  
- Shows sunrise and sunset time  
- Displays weather icon dynamically  
- 5-day weather forecast  
- Integrated Google Map for searched city  
- Responsive layout  
- Built using HTML, CSS, JavaScript, OpenWeatherMap API, and Google Maps Embed

## Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript**
- **OpenWeatherMap API**
- **Google Maps Embed API**

## How It Works

1. Enter a city name in the search bar.  
2. Fetches live weather data using OpenWeatherMap API.  
3. Updates UI with weather details and forecast.  
4. Google Map iframe auto-updates to show that location.  

## API Used

- **Current Weather API:**  
  `https://api.openweathermap.org/data/2.5/weather?q={city}&appid={APIkey}`

- **5-Day Forecast API:**  
  `https://api.openweathermap.org/data/2.5/forecast?q={city}&appid={APIkey}`

## Folder Structure

```
CityWeatherMap/
│── index.html
│── index.js
│── README.md
```

## How to Run Locally

1. Clone the repository  
   ```
   git clone https://github.com/Ritesh-kumar-jena/city-weather-map.git
   ```
2. Open **index.html** in your browser.  
3. Replace the API key in `index.js` if needed.

## Future Enhancements

- Add location autocomplete  
- Improve UI responsiveness  
- Add temperature unit toggle (°C / °F)

## 💼 Author

**Ritesh Kumar Jena**  
Frontend Developer & MERN Stack Enthusiast 
- Email: jenariteshkumar85@gmail.com  
[GitHub](https://github.com/Ritesh-kumar-jena) | [LinkedIn](http://www.linkedin.com/in/ritesh-kumar-jena-aa6407270)

---

Interactive weather app built using JavaScript, APIs, and clean UI.
