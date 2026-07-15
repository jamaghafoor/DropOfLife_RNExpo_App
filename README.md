# DropOfLife - A Blood Donation App

A React Native mobile application built with **Expo** to connect blood donors with those in need.

## Main Functionalities

*   **User Authentication & Onboarding**: Secure login, registration, OTP verification, and password reset functionalities, complete with a welcoming onboarding flow.
*   **Search for Donors**: Locate nearby blood donors using an interactive map.
*   **Donation Requests**: Create and manage requests for blood donations to quickly reach out to potential donors.
*   **Profile Management**: Users can set up and manage their donor profiles.
*   **Reporting**: In-app reporting features.

## Tech Stack

*   **Frontend**: [React Native](https://reactnative.dev/), [Expo](https://expo.dev/)
*   **Navigation**: React Navigation
*   **Maps**: React Native Maps
*   **Storage**: Async Storage

## Setup Process

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

*   [Node.js](https://nodejs.org/) installed on your machine.
*   [Yarn](https://yarnpkg.com/) (recommended) or npm.
*   [Expo CLI](https://docs.expo.dev/get-started/installation/) installed globally.
*   [Expo Go](https://expo.dev/client) app installed on your iOS or Android device, or an emulator/simulator setup.

### Installation

1.  **Clone the repository** (if you haven't already):
    ```bash
    git clone <repository-url>
    cd DropOfLife_RNExpo_App
    ```

2.  **Install dependencies**:
    ```bash
    yarn install
    # or
    npm install
    ```

3.  **Start the development server**:
    ```bash
    yarn start
    # or
    npm start
    ```

4.  **Run the app**:
    *   Press `a` to run on an Android emulator.
    *   Press `i` to run on an iOS simulator.
    *   Press `w` to run on the web.
    *   Or, scan the QR code in the terminal using the Expo Go app on your physical device.

## Available Scripts

*   `yarn start`: Starts the Expo development server.
*   `yarn android`: Starts the app on Android.
*   `yarn ios`: Starts the app on iOS.
*   `yarn format:write`: Formats the code using Prettier.
*   `yarn lint:fix`: Fixes linting errors using ESLint.
