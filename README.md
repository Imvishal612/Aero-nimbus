# Weather Web App

A lightweight and visually appealing weather forecast web application using HTML, CSS, and JavaScript. The app fetches real-time weather data for any city using the OpenWeatherMap API and displays temperature, humidity, wind speed, and a dynamic weather icon.

## Features

* **Search Weather**: Enter any city name to get the current weather.
* **Dynamic Display**: Weather icons and data update based on real-time API responses.
* **Responsive UI**: Clean card-based interface with gradient styling.
* **API Integration**: Uses OpenWeatherMap API for live weather updates.

## Demo

![Screenshot](Aeronimbus.png)


## Technologies Used

* **HTML5** – Markup and layout
* **CSS3** – Styling with gradients and flexible layout
* **JavaScript (ES6+)** – DOM manipulation and API fetching
* **OpenWeatherMap API** – Source of real-time weather data

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/imvishal612/Aero-nimbus.git
   cd Aero-nimbus
   ```

2. **Add your API Key:**


   ```js
   const apiKey = "YOUR_API_KEY_HERE";
   ```

   You can get a free API key from [OpenWeatherMap](https://openweathermap.org/api).

3. **Run the App:**

   Open `Weather.html` in any modern web browser.

## Project Structure

```
weather-app/
│
├── Weather.html     # Main HTML file with script
├── style.css        # Styling for layout and weather card
├── images/          # (Optional) Folder for icons like sun.png, rain.png, etc.
```

## Customization

* Add more weather conditions and icons by extending the `if` conditions in the JavaScript.
* Customize background gradients or fonts in `style.css`.

## License

This project is open-source and available under the [MIT License](LICENSE).

