NAME: AYEGBUSI CHRISTIAN TOLUWALASE
MATRIC NO: 24/15155
DEPARTMENT: COMPUTER SCIENCE
COURSE: SEN 201


SEN ASSIGNMENT
Project Title
Weather Forecast Application (WeatherApp)
1. Introduction to the Project
The project selected for this Software Engineering (SEN) assignment is a Weather Forecast Application, hereafter referred to as WeatherApp.
WeatherApp is a software system designed to fetch real-time weather data and forecast information from a public Weather API and present it to users in a clear and user-friendly format. The application allows users to search for a city and view relevant weather parameters such as temperature, humidity, weather conditions, and short-term forecasts.
This project was chosen because it is a real-world system that demonstrates the complete Software Development Life Cycle (SDLC), from requirements gathering to deployment and maintenance, while also involving API integration, which is a common practice in modern software engineering.
2. Software Development Life Cycle (SDLC) of WeatherApp
The development of WeatherApp follows the classical SDLC phases, which are explained below in the context of this project.
2.1 Requirement Analysis Phase
Objective:
The goal of this phase is to identify what the system must do and the constraints under which it must operate.
Functional Requirements:
The WeatherApp system must:
-	Allow users to enter a city name.
-	Fetch current weather data from a Weather API.
Display:
-	Temperature
-	Weather condition (e.g., sunny, cloudy)
-	Humidity
-	Wind speed
-	Display weather forecast for upcoming days.
-	Handle invalid city names gracefully.
Non-Functional Requirements
-	The system must be fast and responsive.
-	API calls must be secure.
-	The application should have a simple and intuitive UI.
-	The system should be maintainable and scalable.
2.2 System Design Phase
This phase focuses on how the system will work internally.
Architectural Design:
WeatherApp uses a client–API–server interaction model:
-	Frontend: User Interface (HTML/CSS/JavaScript)
-	API Layer: Weather API (e.g., OpenWeatherMap API)
-	Backend Logic: JavaScript functions that handle data fetching and processing
Component Design
The system is divided into the following components:
1.User Interface Module
-	Search bar
-	Weather display section
2.API Service Module
-	Handles API requests
-	Parses JSON responses
3.Data Processing Module
-	Converts temperature units
-	Formats forecast data
4.Error Handling Module:
-	Displays error messages for invalid input or network issues
Note: All component names used here are the same as those implemented in the project source code.
2.3 Implementation (Coding) Phase
In this phase, the system design is translated into actual working code.
Technologies Used:
-	HTML – Structure of the application
-	CSS – Styling and layout
-	JavaScript – Application logic and API interaction
-	Weather API – Source of real-time weather data
-	Git & GitHub – Version control and repository hosting
Implementation Logic:
-	The user enters a city name.
-	JavaScript sends an HTTP request to the Weather API.
-	The API returns weather data in JSON format.
-	The application extracts required values.
-	Weather data is displayed dynamically on the UI.
2.4 Testing Phase
Testing ensures the application works as expected.
Testing Performed:
-	Unit Testing
Tested API fetch functions
-	Input Validation Testing
-	Invalid city names
-	Empty input fields
-	Integration Testing
-	API integration with frontend
-	User Acceptance Testing
-	Ensured data is readable and accurate
2.5 Deployment Phase
After successful testing:
-	The project is hosted locally and verified.
-	The complete project files are pushed to a GitHub repository.
The repository includes:
-	Source code
-	README documentation
-	API configuration instructions
2.6 Maintenance Phase
Post-deployment maintenance includes:
-	Updating API versions if required.
-	Fixing bugs reported by users.
-	Improving UI design.
-	Adding new features such as hourly forecasts or location-based weather detection.
3. Project Implementation Summary
The WeatherApp is fully implemented using consistent naming conventions across design and code. It demonstrates:
-	Proper SDLC execution
-	Real-world API usage
-	Clean modular design
-	Maintainable code structure
4. GitHub README (Markdown Format)
Below is a ready-to-use README.md that you can copy directly into your GitHub repository.

# WeatherApp – SEN Assignment

## 👤 Student Details
- **Name:** Ayegbusi Christian Toluwalase  
- **Matric Number:** 24/15155  
- **Course:** Software Engineering (SEN)

---

## 📌 Assignment Question
Pick any project of your choice and explain the full Software Development Life Cycle (SDLC) of that project.  
Implement the project and push it to a GitHub repository.  
Ensure that names and nomenclatures used in the design match those used in the implementation.

---

## 🌦️ Project Overview
**WeatherApp** is a simple and functional weather forecast application developed as part of a Software Engineering (SEN) assignment.  
The application fetches real-time weather data and forecast information from a public Weather API and displays it in a user-friendly format.

---

## 📂 Project Contents
This repository contains:
- `index.html` – Application structure
- `style.css` – Styling and layout
- `script.js` – Application logic and API integration
- `README.md` – Project documentation

---

## 🧠 What the Project Is About
WeatherApp allows users to:
- Search for a city
- View current weather conditions
- View short-term weather forecasts
- Receive feedback for invalid city inputs

The project demonstrates the full SDLC process including requirement analysis, design, implementation, testing, deployment, and maintenance.

---

## ⚙️ How the Application Functions
1. The user enters a city name in the search bar.
2. The application sends a request to the Weather API.
3. The API returns weather data in JSON format.
4. JavaScript processes the data.
5. Weather information is dynamically displayed on the screen.

---

## 🛠️ Technologies Used
- HTML
- CSS
- JavaScript
- Weather API
- Git & GitHub

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/christiancode-sketch/SEN-201-Assignments.git
