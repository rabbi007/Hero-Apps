![Homepage Image](https://github.com/rabbi007/Hero-Apps/blob/main/src/assets/appvault.jpg)

# AppVault

Live Link: https://appvault-rabbi.netlify.app/

## Project Overview

AppVault is a mobile app showcase and download platform that allows users to explore a variety of apps, check ratings, and install their favorites. The app provides a clean and user-friendly interface for discovering mobile applications, with key features like real-time search, app details, and local storage for installed apps.

## Key Features

### Header:

Logo that navigates to the home page.

Navigation Links for Home, Apps, and Installation.

GitHub Contribution Button for easy access to the project's source code.

### Home Page:

A banner with buttons for the App Store & Play Store.

Display of Top Apps in a 4-column layout.

Show All button to explore more apps.

### All Apps Page:

A searchable list of apps.

Live filtering options for sorting apps based on categories, ratings, etc.

No-match message when no results are found.

### App Details:

Detailed app information with features and ratings.

Install button with success/failure notifications using React Toastify.

Review chart using Recharts to display user ratings.

App description to help users understand the app's functionality.

### Error & Loading States:

Custom error page for non-existent pages.

Loading animations during data fetch.

"Not Found" messages for empty or incorrect routes.

### LocalStorage Integration:

My Installation Page where users can see their installed apps.

Option to uninstall apps and sort by downloads.

Persistent data using LocalStorage to retain installed apps even after app refreshes.

## Technologies Used

React: Frontend JavaScript framework for building the user interface.

Tailwind CSS + DaisyUI: Styling libraries for creating responsive and modern layouts.

JSON: Used to manage and structure the app data.

Recharts: A charting library used to display app review ratings.

Axios: HTTP client used for making API requests.

LocalStorage: Used for persisting data about installed apps.

React Toastify: Used to display notifications for actions like install/uninstall.

## Run the Project Locally

To run the project locally, follow the steps below:

1. Clone the Repository

Clone the project repository to your local machine:

git clone https://github.com/rabbi007/AppVault.git

2. Install Dependencies

Navigate to the project directory and install the required dependencies:

cd AppVault
npm install

3. Run the Development Server

Start the app locally by running:

npm start


The app should now be accessible in your browser at http://localhost:5173/.

### Notes

Make sure Node.js and npm are installed on your machine.

The app relies on LocalStorage, so ensure your browser supports it.

If you encounter any issues, please open an issue in the GitHub repository.
