# React Weather App

## Overview
A simple weather application built using ReactJS that fetches and displays real-time weather information for a given location.  
This project was created as part of my React learning journey, with a focus on API integration, state management, and clean UI development.

## Features
- Search weather by city/location
- Displays current temperature and weather conditions
- Responsive user interface
- Error handling for invalid input and API failures

## Tech Stack
- ReactJS
- JavaScript (ES6+)
- Axios
- Meteosource Weather API

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/reactjs-weather-app.git
    cd reactjs-weather-app
    ```

2. Install the dependencies:
    ```sh
    npm install
    # or
    yarn install
    ```

3. Create a `.env` file in the root directory and add your Meteosource API key:
    ```env
    REACT_APP_WEATHER_API_KEY=your_api_key_here
    ```

### Usage

1. Start the development server:
    ```sh
    npm start
    # or
    yarn start
    ```

2. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Dependencies

This project uses the following dependencies:

- **axios**: A promise-based HTTP client for making requests to the Meteosource Weather API. It simplifies the process of handling HTTP requests and responses.
- **bootstrap-icons**: A library of free, high-quality icons designed for Bootstrap, but usable in any project. These icons enhance the visual appeal and user experience of the app.

## API Reference

This project uses the Meteosource Weather API to fetch weather data. You can find more information and sign up for an API key at the [Meteosource Weather API page](https://rapidapi.com/MeteosourceWeather/api/ai-weather-by-meteosource).

## Learning Outcomes

1. Integrating third-party APIs in React
2. Handling async data with Axios
3. Component-based UI design
4. Environment variable management in React

## Credits

Inspired by a tutorial from the Code Explained YouTube channel.
This implementation was rebuilt and customized for learning purposes.
