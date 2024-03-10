# MOVIE-APP

The “movie app” project code is an HTML page with accompanying CSS and JavaScript.

It represents a Movie App that allows users to search for movies and displays the results with movie posters, titles, ratings, and overviews.

Here’s a breakdown of the code:

HTML:

•	The HTML structure consists of a header, main section, and a script tag.

•	The header contains a form with an input field for searching movies.

•	The main section has an empty element with the ID "main" where movie results will be displayed.

CSS:

•	The CSS code defines the styles for various elements in the HTML.

•	It sets the background colors, font-family, padding, border, and other visual properties.

•	The styles are applied to the header, search input, main section, movie cards, movie information, and overview.

JavaScript:

•	The JavaScript code fetches movie data from a movie API and displays it on the page.

•	It uses the fetch API to retrieve movie data in JSON format.

•	The retrieved movie data is then processed and rendered on the page using the showMovies function.

•	The showMovies function dynamically creates HTML elements for each movie and appends them to the main section.

•	The getClassByRate function determines the class for the rating span based on the vote average of the movie.

•	The form has an event listener attached to it that triggers a search when the user submits a search term.

•	The search term is used to fetch movie data from the API and display the search results.

Overall, this code creates a basic Movie App interface where users can search for movies and view their details.

It demonstrates the use of HTML, CSS, and JavaScript to build a simple web application.

