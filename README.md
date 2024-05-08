# Atlas of Solidarity App

## Overview
The Atlas of Solidarity app is designed to facilitate aid and resources distribution in response to emergencies, starting with the recent floods in Brazil. This app connects donors, volunteers, and those in need by providing a platform to coordinate donations and volunteer activities effectively.

## Features
- **User Authentication:** Securely manage user sessions.
- **Profile Management:** Users can manage their profiles and post updates.
- **Donation Handling:** Register and manage pickup points for donations.
- **Volunteer Coordination:** Manage volunteer sign-ups and post new opportunities.
- **Real-time Dashboard:** View real-time data on donations and volunteering needs.

## Tech Stack
- **Frontend:** React Native
- **Backend:** Node.js with Express
- **Database:** MongoDB
- **Real-Time Data Handling:** Socket.IO (alternative: Firebase)
- **APIs:** Google Maps for location services

## Project Structure

### Backend
Located in the `myApp-backend` directory:
- `server.js`: Main server file.
- `config/`: Directory for configuration files.
- `models/`: Mongoose models for MongoDB.
- `routes/`: Express routes for API endpoints.
- `controllers/`: Business logic for handling requests.

### Frontend
Located in the `myApp` directory:
- `App.js`: Entry point of the React Native app.
- `screens/`: Contains different screens of the app.
- `components/`: Reusable components.
- `navigation/`: Navigation setup.

## Setup Instructions

### Backend Setup
1. Navigate to the backend directory: `cd myApp-backend`
2. Install dependencies: `npm install`
3. Start the server: `npm start`

### Frontend Setup
1. Navigate to the frontend directory: `cd myApp`
2. Install dependencies: `npm install`
3. Start the app: `npx react-native run-android` or `npx react-native run-ios`

## Contributions
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
Distributed under the MIT License. See `LICENSE` for more information.