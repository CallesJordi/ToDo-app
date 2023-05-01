## MoviesContext

- Stores:
  - movie[]
  ## Actions
  - addMovie
  - updateMovie
  - removeMovie
  - showDetails
  - filterMovie

## UIContext

- isLoder
- isError
  - Actions:
    - setloading
    - showLoading
    - hideLoading
    - showError
    - hideError

## App

- Render MovieCard
- Render MovieList

## Header

- Show logo
- Logo receives click to back to home

## MoviesList

-

## Loading

-

## Form

## Filter

- Issue an action to filter movies from the MoviesContext with payload with parameter

## MovieCard

- Receives movie from the MoviesContext
- Show information of movies
- Show favorite button
- Show delete button

## Button

- Show a button
- Receives a text from props
- Receives a prop with the action on click
