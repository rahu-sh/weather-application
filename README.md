# 🌦️ Weather Application

A simple and responsive **Weather Application** built using **HTML, CSS, and JavaScript** that fetches real-time weather data from the **OpenWeatherMap API**.
This project is beginner-friendly and perfect for learning how to use APIs, manipulate the DOM, and host projects on **GitHub Pages**.

---

## 🧠 Features

* 🌤 Fetches **real-time weather data** (temperature, humidity, wind speed, and weather description)
* 📍 Supports **city-based search**
* 💡 Displays **weather icons** dynamically
* 📱 **Responsive design** for all screen sizes
* ⚙️ Easy setup using OpenWeatherMap API key
* 🚀 Ready to deploy on **GitHub Pages**

---

## 🛠️ Technologies Used

* **HTML5** – for structure
* **CSS3** – for styling and layout
* **JavaScript (ES6)** – for logic and API integration
* **OpenWeatherMap API** – for weather data

---

## 📦 Folder Structure

```
weather-app/
│
├── index.html          # Main HTML file
├── style.css           # Styling for the app
├── script.js           # JavaScript logic and API calls
└── README.md           # Project documentation
```

---

## ⚙️ Setup Instructions

### 1️⃣ Get the Weather API Key

1. Go to [OpenWeatherMap API](https://openweathermap.org/api)
2. Sign up for a free account.
3. Navigate to **My API Keys** and **copy** your key.

---

### 2️⃣ Add the API Key

Open `script.js` and replace this line:

```js
const apiKey = "YOUR_API_KEY_HERE";
```

with your actual key:

```js
const apiKey = "abcd1234efgh5678";
```

---

### 3️⃣ Run Locally

You can simply open the `index.html` file in your browser to run it locally.
Or use a local server (optional):

```bash
npx serve
```

Then open: `http://localhost:3000`

---

## 💻 Code Overview

### **index.html**

Defines the structure of the app, including:

* Search bar
* Weather result container
* Icons and text placeholders

### **style.css**

Handles all visual styling such as:

* Background colors
* Font design
* Card layout
* Responsive design for mobile view

### **script.js**

Contains the main logic:

* Fetching weather data from API
* Handling user input
* Updating UI dynamically
* Error handling for invalid city names

---

## 🚀 Deployment (GitHub Pages)

1. Go to your [GitHub](https://github.com) account.
2. Create a new repository, e.g. `weather-app`.
3. Upload all files (`index.html`, `style.css`, `script.js`, `README.md`).
4. Go to **Settings → Pages**.
5. Under **Source**, select `main` branch and `/ (root)`.
6. Click **Save**.
7. Your live app will be available at:

   ```
   https://<your-username>.github.io/weather-app/
   ```

---

## 🧩 Example Output

**Example Search:**
City → *London*
Output →

```
Temperature: 15°C  
Humidity: 78%  
Wind Speed: 5.2 m/s  
Condition: Cloudy ☁️
```

---

## 🧰 API Reference

**Endpoint:**

```
https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}&units=metric
```

**Example:**

```
https://api.openweathermap.org/data/2.5/weather?q=Delhi&appid=abcd1234efgh5678&units=metric
```

**Response Parameters:**

* `main.temp` → Temperature
* `main.humidity` → Humidity
* `wind.speed` → Wind speed
* `weather[0].description` → Description of weather

---

## 🔧 Future Improvements

* Add **5-day forecast** feature
* Integrate **geolocation** (auto-detect user city)
* Add **dark/light mode** toggle
* Save **search history**

---

## 🧑‍💻 Author

**Rahul Kumar Sharma**
🎓 B.Tech CSE | 2nd Year
📧 [rahulsharma15855@gmail.com](mailto:rahulsharma15855@gmail.com)
🌐 [GitHub Profile](https://github.com/)

---

## 🪪 License

This project is licensed under the **MIT License** — free to use and modify.

---

### ⭐ Don’t forget to give this project a star if you like it!
