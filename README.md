# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


Weather Application

Overview:

This Weather Application is a responsive web app that allows users to fetch and display current weather information for any valid location (city name or zip code). The app is built using HTML, Tailwind CSS, JavaScript, and React with Vite as the build tool. Weather data is fetched from the Open Weather API.

Features:- 

1) Display current location, temperature, date, and time.
2) Input field for users to enter a location (city name or zip code).
3) Button to fetch and display weather information for the entered location.
4) Handle API responses and errors gracefully.
5) Responsive design ensuring compatibility with desktop, tablet, and mobile devices.

Installation:-

1)Install dependencies:
>>npm install
2) Start the development server:
>>npm run dev
3) Build the application for production:-
>>npm run build


Usage:-

1) Open the application in your browser (usually at http://localhost:3000 when running the development server).
2) View the current weather for your location displayed by default.
3) Enter a city name or zip code in the input field.
4) Click the search button to fetch and display the weather information for the entered location.

API Integration:- 

The application uses the Open Weather API to fetch weather data.
Added my API key to the application. Created a ".env" file in the root of your project and added :

VITE_OPEN_WEATHER_API_KEY="https://openweathermap.org/api"


Error Handling:-

If the user enters an invalid location or there is an issue with the API connection, an error message is displayed to inform the user.
Feedback is provided to the user in case of invalid input or connection issues.

File Structure:-

WETHER-APP
> node_modules
> public
> src
.eslintrc.cjs
.gitignore
<> index.html
{} package-lock.json
{} package.json
JS postcss.config.js
README.md
JS tailwind.config.js
JS vite.config.js


Development Notes:-

1) HTML: Basic structure of the application.
2) Tailwind CSS: Used for styling the application.
3) JavaScript: For the application's logic.
4) React: Framework used to build the UI components.
5) Vite: Build tool for development and production builds.
