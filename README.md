# Movie App

## Overview

The Movie App is a React-based application that allows users to search for movies, view popular movies, and manage their favorite movies. The app utilizes The Movie Database (TMDb) API to fetch movie data and provides a user-friendly interface for movie exploration.

## Features

- Search for movies by title.
- View a list of popular movies.
- Add and remove movies from favorites.
- Responsive design for mobile and desktop views.

## Technologies Used

- React
- Vite
- CSS Modules
- The Movie Database (TMDb) API

## Project Structure

The project is structured as follows:


### File Descriptions

- **App.jsx**: The main application component that sets up the routing and context provider for managing movie favorites.

- **components/**: Contains reusable components.
  - **MovieCard.jsx**: Displays individual movie details, including the title, release date, and a favorite button.
  - **NavBar.jsx**: The navigation bar that allows users to navigate between the home page and the favorites page.

- **contexts/**: Contains context-related files for state management.
  - **MovieContext.jsx**: Provides context for managing favorite movies, including functions to add, remove, and check favorites.

- **pages/**: Contains the main pages of the application.
  - **Favorites.jsx**: Displays the user's favorite movies.
  - **Home.jsx**: The main page where users can search for movies and view popular movies.

- **services/**: Contains API-related functions.
  - **api.js**: Contains functions to fetch popular movies and search for movies using the TMDb API.

- **css/**: Contains styles for the application.
  - **App.css**: General styles for the application.
  - **Favorites.css**: Styles specific to the favorites page.
  - **Home.css**: Styles specific to the home page.
  - **MovieCard.css**: Styles for the movie card component.
  - **Navbar.css**: Styles for the navigation bar.

- **main.jsx**: The entry point of the application that renders the App component into the DOM.

## Getting Started

To run the project locally, follow these steps:

1. Clone the repository:
   ```
   git clone  https://github.com/HarvalKINGA/My_React_Movie_App.git
   ```

2. Navigate to the project directory:
   ```
   cd My_React_Movie_App
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   npm run dev
   ```

5. Open your browser and go to `http://localhost:3000` to view the application.

## License

This project is licensed under the MIT License.
