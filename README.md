# 🌤️ Weather App

A Django-based web application that provides real-time weather information for any city around the world using a weather API.

## 🚀 Features

- Search weather by city name
- Displays current temperature, weather condition, and other key metrics
- Clean and responsive UI with CSS styling
- Powered by a live weather API

## 🛠️ Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, JavaScript
- **API:** OpenWeatherMap (or equivalent weather API)

## 📦 Installation & Local Setup

### Prerequisites

- Python 3.x
- pip

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/BhanuPratap0805/Weather-App.git
   cd Weather-App
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables**

   Create a `.env` file in the root directory and add:
   ```
   SECRET_KEY=your_django_secret_key
   WEATHER_API_KEY=your_openweathermap_api_key
   DEBUG=True
   ```

4. **Run migrations**
   ```bash
   python manage.py migrate
   ```

5. **Start the development server**
   ```bash
   python manage.py runserver
   ```

6. Open your browser and visit `http://127.0.0.1:8000`

## 📁 Project Structure

```
Weather-App/
├── WeatherBug/         # Django project settings
├── weather_api/        # Main app with views and API logic
├── templates/          # HTML templates
├── static/             # Static CSS/JS files
├── staticfiles/        # Collected static files
├── manage.py
├── requirements.txt
└── runtime.txt
```

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with ❤️ by [BhanuPratap0805](https://github.com/BhanuPratap0805)
