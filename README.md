# NASA APOD App

This project is a simple web application built with React that fetches and displays NASA's Astronomy Picture of the Day (APOD) using NASA's public API. The app caches the data in localStorage to avoid repeated API calls and provides an option to view additional information through a modal sidebar.

## Features

- **Fetch NASA APOD**: Retrieves the Astronomy Picture of the Day from NASA's API.
- **Caching**: Caches the API response in the browser's localStorage to minimize API calls.
- **Loading Indicator**: Displays a loading icon while fetching data from the API.
- **Modal Sidebar**: Toggles a sidebar with more details about the image or content displayed.
- **Footer**: Displays additional data or controls for interaction.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nasa-apod-app.git
   cd nasa-apod-app
   npm install
   VITE_NASA_API_KEY=your_nasa_api_key_here
   npm start
