---
layout: project
type: project
image: images/moviesearch.jpg
title: Movie Search App
permalink: projects/moviesearch
# All dates must be YYYY-MM-DD format!
date: 2020-11-24
labels:
  - React
  - TMDB API
  - CSS
summary: A movies search app with React.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/moviesearch.jpg">
  <img class="ui image" src="../images/moviesearch2.jpg">
</div>

Movie-Search-App uses the TMDb API to retrieve information about movies. It's built with React and styled with CSS using the BEM syntax.

TECH OVERVIEW:

  - Functional Components
  - React Hooks
  - CSS grid
  - TMDB API

PURPOSE: The project was done to practice the use of functional components, React Hooks and Fetch together with Async/Await feature of JavaScript.

I started building the app by creating the component folders and signing up on the Movies DB to get an API key. Then I added base styles to the app. Next, I created the SearchMovies asyn functional component containing the API call using Fetch. Then I added 2 states - one for input query and the second for movies. For modularity, I created a second functional component called MovieCard for mapping and displaying the list of movies returned by the query string. Lastly, I applied styling for each of the component.

ROADBLOCK: I encountered one major roadblock which was how to conditionally render the text "Loading... Please wait" while awaiting fetch results from the API.

SOLUTION: To solve this, I created in SearchMovies, a isLoading state with initial value of 'false', set it to 'true' just before fetch and set it back to false just after setMovies.

To learn more visit <a href="https://github.com/PJMantoss/movie-search-app"><i class="large github icon "></i>Github</a>

[Movie Search Website](https://pjmantoss.github.io/movie-search-app/).
