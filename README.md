# Weather App

A real-time weather web application built using **Node.js**, **Express.js**, and **OpenWeatherMap API**.  
It allows users to search for any city and fetch current weather details like **temperature**, **weather condition**, and **location** using a clean, responsive UI.

---

## Features
- Search for real-time weather using city names
- Auto-detect user location and show local weather
- Display temperature, weather condition, and icons
- Dynamic date rendering
- Custom 404 page for unknown routes
- Fully responsive weather widget UI

---

## Technologies Used
- **Node.js** – Backend runtime environment
- **Express.js** – Web framework
- **hbs (Handlebars.js)** – View templating engine
- **OpenWeatherMap API** – Source of live weather data
- **HTML + CSS** – UI structure and design
- **JavaScript** – Frontend behavior and interaction
- **Geolocation API** – Auto-fetch user location
- **OpenStreetMap** – Reverse geocoding for location names

---

## How It Works
**1. Search Weather:**
  - Users enter a city name in the input field.
  - The city is sent to the backend using fetch() from frontend JS.

**2. Backend Request:**
  - The Express route /weather receives the request.
  - It calls the OpenWeatherMap API using request in weatherData.js.
    
**3. Data Display:**
  - The temperature (in Celsius), condition, and icons are returned and displayed on the UI.
  - If the user grants location access, weather is fetched automatically for their current location using Geolocation + OpenStreetMap APIs.

---

## Screenshot

![Screenshot 2025-06-04 175720](https://github.com/user-attachments/assets/0216caf0-929a-4ca0-a919-bcbbee77d4f6)

---

### Developed By
Khushi Kumari | sharmakhushi1501@gmail.com

