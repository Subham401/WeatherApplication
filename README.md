## 🌦️ Weather Application

A simple and efficient Java-based Weather Application that fetches and displays current weather data using a third-party weather API. Built with **Spring Boot** and follows MVC architecture.

---

### 🧰 Features

* 🌍 Get current weather for any city
* ☁️ Displays temperature, weather conditions, humidity, etc.
* 🔧 Configurable API integration
* 🧩 Modular and clean code (MVC pattern)

---

### 📸 Screenshot (Optional)
> <img width="1919" height="678" alt="image" src="https://github.com/user-attachments/assets/6fa16286-e443-4e09-b766-fbba7e832ccf" />

---

### 🚀 Technologies Used

* Java 23
* Spring Boot
* Maven
* REST API (OpenWeatherMap)
* IntelliJ IDEA

---

### ⚙️ Getting Started

#### 1. Clone the repository

```bash
git clone https://github.com/Subham401/WeatherApplication.git
cd WeatherApplication
```

#### 2. Add your API key

Edit the `application.properties` file in:

```
src/main/resources/application.properties
```

Add:

```
weather.api.key=YOUR_API_KEY_HERE
```

#### 3. Run the application

If using Maven:

```bash
./mvnw spring-boot:run
```

Or with IntelliJ:

* Open project
* Run `WeatherAppApplication.java`

---

### 📁 Project Structure

```
WeatherApplication/
├── src/
│   └── main/
│       ├── java/com/example/weather_app/
│       │   ├── Controller/
│       │   ├── Model/
│       │   └── WeatherAppApplication.java
│       └── resources/
│           └── application.properties
├── pom.xml
└── README.md
```

---

### 🧪 Sample API Endpoint

```
GET /weather?city=London
```

Returns:

```json
{
  "temperature": "22°C",
  "condition": "Clear",
  "humidity": "60%"
}
```

---

### 🧑‍💻 Author

**Subham Bose**
[GitHub: Subham401](https://github.com/Subham401)
