# LIRI Bot : Language Interpretation and Recognition Interface

## LIRI is a command line node app that takes in parameters and gives you back data based off the following parameters:

* **concert-this**
* **spotify-this-song**
* **movie-this**
* **do-what-it-says**


**concert-this**: this command will search Bands in Town Artist Events API to provide the following information: 

* Name of the venue
* Venue location
* Date of the event 

![Screenshot](/images/concert-this.png)


**spotify-this-song**: this command will search Spotify to provide the following information:

* Artist
* Name of the song
* A preview link of the song from Spotify
* The albumn the song is from

![Screenshot](/images/spotify-this-song.png)


**movie-this**: this command will search the OMDB API to provide the following information:

* Title of the movie
* Year the movie came out
* IMDB rating
* Rotten Tomatoes rating
* Country where the movie was produced
* Language of the movie
* Plot of the movie 
* Actors in the movie

![Screenshot](/images/movie-this.png)


**do-what-it-says**: This command will use the text from random.txt and call on each of the LIRI's commands

![Screenshot](/images/do-what-it-says.png)


**Technologies used:**

* Spotify API
* OMDB API
* Bands In Town API
* Node.js
* Javascript
* NPM packages
