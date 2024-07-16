# Google Places API Autocomplete with React Native Expo

This project demonstrates the use of the Google Places API for autocomplete functionality in a React Native application built with Expo.

## Features

- Autocomplete search using the Google Places API
- Styled input fields with focus state handling
- Background image and custom styles

## Prerequisites

- Node.js and npm installed
- Google API Key (you need to generate your own key from the [Google Cloud Console](https://console.cloud.google.com/))

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/MohIdrees-Mohammadi/Google-places-Api-using-React-Native-Expo.git
    cd repo-name
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the root of the project and add your Google API Key:

    ```
    API_KEY=your-google-api-key
    ```

## Running the App

Start the Expo development server:

    ```bash
    npm start
    ```

Scan the QR code with the Expo Go app on your mobile device, or use an emulator to run the app.

## Usage

The app contains a search input field powered by the Google Places API. Type in the input field to get autocomplete suggestions for places. When you select a suggestion, the address will be logged to the console.
