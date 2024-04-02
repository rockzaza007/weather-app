# Weather Data Collection App

## Overview

This project is a web application built with React.js, using the TMD Data and API to fetch weather data for Thailand. Additionally, it implements CRUD operations with Firestore, a Firebase database, to manually collect weather data. The application allows users to view weather information fetched from the TMD API and to add, edit, and delete manual weather data entries.

## Features

- Fetch weather data from TMD API for Thailand.
- Perform CRUD operations to collect manual weather data.
- View weather information including temperature, humidity, wind speed, etc.
- Add new weather data entries manually.
- Edit existing weather data entries.
- Delete weather data entries.

## Technologies Used

- React.js
- TMD Data and API
- Firestore (Firebase)
- Yarn
- Firebase (for deployment)

## Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/weather-data-collection-app.git
```

2. Navigate to the project directory:

```bash
cd weather-data-collection-app
```

3. Install dependencies using Yarn:

```bash
yarn install
```

## Usage

1. Start the development server:

```bash
yarn start
```

2. Open your web browser and navigate to `http://localhost:3000` to access the application.

3. Explore the weather data fetched from the TMD API and use the CRUD functionality to manage manual weather data entries.

## Deployment

This project can be deployed to Firebase hosting. Ensure you have Firebase CLI installed and configured.

1. Build the project:

```bash
yarn build
```

2. Deploy to Firebase:

```bash
firebase deploy
```

## Contributors

- [Your Name](https://github.com/your-username)

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize the content according to your project's specific details and requirements.