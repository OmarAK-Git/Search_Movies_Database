# Search Movies Database
Easy tool to search, rank, store and view your favorite movies. 
## what does it do?
This code creates a database known as "movies.db" using SQLAlchemy and proceeds to host that information on a webpage generated by Flask. The website is enhanced visually by using bootstrap, takes its data by sending a GET request to The Movie Database (TMDB) API, and finally, takes movie rating and comments from the user using wtform and sorts them by their rank.
## How to use it
<ol><li> Sign up for free at https://api.themoviedb.org </li>
Obtain API Key and insert it into the headers constant. 
<li>Create a flask secret key for security purposes</li>
Feel free to save it as an enviromental variable if you're taking this code publicly. 
<li> Run the code</li>
Search the library for movies, Add them, Rate them, and watch them fall in line
</ol>

## What does it look like?
Home Page

![Screenshot 2023-11-26 145336](https://github.com/OmarAK-Git/Fav_movie_list/assets/151792697/42d50333-3e53-465f-a3cb-e39155f6c44a)<img> <br>
Hovering over the card displays the fetched information from TMDB plus the rating provided and personal comment.<br>

![image](https://github.com/OmarAK-Git/Fav_movie_list/assets/151792697/a7fb1b58-7b0b-482c-a014-f018873f5801) <br>
Add a movie by searching it by name. <br>

![Screenshot 2023-11-26 145509](https://github.com/OmarAK-Git/Fav_movie_list/assets/151792697/0a4ae6c8-434e-48a5-82b1-4b36c0596c70) <br>
Select the relevant result. <br>

![Screenshot 2023-11-26 145521](https://github.com/OmarAK-Git/Fav_movie_list/assets/151792697/16b0775f-db92-449b-8190-309be68187dc) <br>
Once selected, get redircted to insert a rating and leave a comment. <br>

![Screenshot 2023-11-26 145528](https://github.com/OmarAK-Git/Fav_movie_list/assets/151792697/089d8042-e0df-4c1e-9866-780f7be073c1) <br>
Movie gets sorted and ranked by rating and added to the homepage. <br>

![Screenshot 2023-11-26 145607](https://github.com/OmarAK-Git/Fav_movie_list/assets/151792697/6e7fb9b2-8b2d-4a9c-aca6-23f3ff344d51) <br>
