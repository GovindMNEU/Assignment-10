# Weather Forecasting Application using React

This project is a weather forecasting application built with React. It showcases a 5-day weather forecast, displaying daily high and low temperatures, along with images depicting different weather conditions (sunny, rainy, cloudy, snowy). Initially, it utilizes fake hard-coded data for rendering purposes until the functionality is implemented accurately.

## Features

- Displays a 5-day weather forecast with high and low temperatures for each day.
- Illustrates weather conditions with corresponding images (sunny, rainy, cloudy, snowy).
- Click on a specific day to view its hourly forecast.
- Integration of React Router for navigation:
  - `/` route presents the 5-day forecast.
  - `/[name-of-day]` route exhibits the hourly forecast for a specific day.

## Setup

1. Clone this repository.
2. Install project dependencies using `npm install`.
3. Obtain a free API key from [OpenWeatherMap](https://openweathermap.org/) and add it to the project.

## Usage

- Run the application using `npm start`.
- Access the 5-day forecast at the root route (`/`).
- Click on a specific day to view its hourly forecast by navigating to `/[name-of-day]`.

## API Integration

This application fetches real 5-day forecast data from the OpenWeatherMap API. Make sure to include your API key for seamless data retrieval.

## Technology Stack

- React
- React Router
- OpenWeatherMap API

## Contributions

Contributions are encouraged! Feel free to submit issues or pull requests.

## License

This project is licensed under the [MIT License](LICENSE).



# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
