# Weather App

This is a simple React-based Weather App that displays weather information for a specific city. The app allows users to search for a city and view its current weather details such as temperature, humidity, and weather conditions.

## Features

- **City Search**: Search for weather information by city name.
- **Weather Details**: Displays the following weather information:
  - Current temperature
  - Minimum and maximum temperature
  - Humidity
  - Weather condition (e.g., haze, clear, etc.)
- **Dynamic Updates**: The app dynamically updates the weather information based on user input.

## Components

1. **WeatherApp**:
   - The main component that manages the state of the weather information.
   - Contains the `SearchBox` and `InfoBox` components.
   - Uses React's `useState` hook to manage weather data.

2. **SearchBox**:
   - A child component that allows users to input a city name.
   - Calls the `updateInfo` function in the parent component to update the weather information.

3. **InfoBox**:
   - A child component that displays the weather details passed as props from the parent component.

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd WeatherApp-react


Procedure to Execute:

use command : npm run dev
This will give Local host url  so follow that cpurl

Enter the city name: -

![image](https://github.com/user-attachments/assets/47e1768d-2a7b-4cd9-936d-95b0a02f164a)


If You enter correct city:-

![image](https://github.com/user-attachments/assets/3e575845-6cac-436f-b15b-748ab628f939)


If you enter wrong city name: 

![image](https://github.com/user-attachments/assets/0d06cf9d-5de1-4a9f-97ee-72409ba5104d)


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
