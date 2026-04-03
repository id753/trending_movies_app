# 🍿Trending Movies 🎥 Search App
## A dynamic web application for discovering movies🎬, featuring real-time search and detailed cinema insights by integrating the TMDB API.

<p align="center">
  <img src="https://github.com/user-attachments/assets/d0b4ad1e-be76-4633-b43b-de317e2b78b5" alt="Trending Movies Search App Screenshot" width="450" />
  <br>
  <sub>Trending Movies Search App Screenshot</sub>
</p> 

## [Live Project](https://trending-movies-app-omega.vercel.app/) 
## API Integration: Built using [TMDB Documentation](https://developer.themoviedb.org/docs/getting-started) for comprehensive media data retrieval.

## 🎨 Tech Stack
- Core: React, JavaScript (ES6+).
- Routing: React Router v6 (Nested Routes, Dynamic Params).
- Data Fetching: Axios, TMDB REST API.
- State & Optimization: React Hooks (useEffect, useState, useRef, useMemo), React.lazy, Suspense.
- Forms: Formik.
- Styling: CSS Modules (for component-scoped styles).
- Build & Deployment: Vite, Vercel.

## Features
### Frontend Experience
- 📚 **Dynamic Data Fetching**: Implemented asynchronous API integration using Axios to fetch trending movies, detailed descriptions, cast lists, and user reviews.
- 🚀 **Advanced Routing & Navigation**: Utilized React Router for complex navigation, including nested routes for cast/reviews and a robust "Go Back" functionality using useLocation and useRef.
- 💾 **Performance Optimization**: Applied Code Splitting with React.lazy and Suspense to reduce initial bundle size and improve page load speed.
- ⚡ **Stateful Search Logic**: Developed a search interface with URL persistence via useSearchParams, allowing users to share specific search results through the browser link.
- 🧱 **Graceful Data Handling**: Integrated loading states, custom "404 Not Found" handling, and placeholder image logic for missing movie posters or actor profiles.
- ✏️ **Form Management**: Built a clean search interface using Formik for efficient form handling and submission logic.


## 🧭Application Navigation
The following routes have been implemented in the application:
- '/' – HomePage: The main landing page displaying a list of currently trending movies.
- '/movies' – MoviesPage: A dedicated page for searching movies by keyword.
- '/movies/:movieId' – MovieDetailsPage: A detailed view providing comprehensive information about a specific movie.
- '/movies/:movieId/cast' – MovieCast: Displays the cast members, rendered as a nested component at the bottom of the MovieDetailsPage.
- '/movies/:movieId/reviews' – MovieReviews: Displays user reviews, rendered as a nested component at the bottom of the MovieDetailsPage.
- NotFoundPage: A fallback component that renders for any non-existent routes, including a Link to redirect users back to the Home page.
    
    
## ✅ Getting Started (Frontend)
Clone the repository
      
    git clone git@github.com:id753/trending_movies_app.git
Install dependencies

     npm install
Run the app

    npm run dev
Open http://localhost:3000 in your browser.

### Previous version of the project: https://github.com/id753/goit-react-hw-05
