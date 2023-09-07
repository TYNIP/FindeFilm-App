# FINDE-FILM
Do not know what to see? Let's find something to watch!

:D

## How it works?
This is a basic movie recommendation application that allows users to discover random movies based on their selected genre. 
Users can also fine-tune their recommendations by indicating whether they want to see movies with similar or different plots to the currently 
displayed one. The app uses the Movie Database - TMBD API.

## Usage 
3) Select a genre from the available options.
4) Click the "Let's Go" button to generate a random movie recommendation.
5) To indicate that you like the current movie and want to see similar movies, click the green "Like" button.
6) To indicate that you want a different movie with a different plot, click the red "Dislike" button.
7) Repeat the process to discover more movies based on your preferences.

## Limitations
This app is for practical and educational puposes, it may not have the same features and improvements as other movie discover apps may have.

## Getting Started
1) Clone the repository to your local machine.
2) Install the required dependencies.
   ```bash
   npm install
3) In order for the website to work you must obtain you own APIKEY (DO NOT SHARE IT AT ALL) at [TMDB](https://developer.themoviedb.org/reference/intro/authentication#api-key-quick-start). Once
   you have it open file "script.js" and at var tmdbKey, replace <API-KEY> with your APIKEY. [Click to see instructions to how to obtain you APIKEY](https://www.educative.io/courses/movie-database-api-python/set-up-the-credentials).
4) Start app
   ```bash
   npm start


### References:
- API
  + [The Movie Database (TMDB) API](https://developer.themoviedb.org/docs)
