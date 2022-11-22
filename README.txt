README.txt

VIDINFO v.1.0.0:
	-Four functioning pages:
		*SEARCH: obtain a list of movies based on optional filters
		*OVERVIEWS: get a detailed overview of a specific movie
		*GENERATOR: get a random movie with three optional filters
		*COMPARISON: compare competitive data of two different movies

--------------------------------------------------------------------------
--------------------------------------------------------------------------

INSTRUCTIONS:
	
Before use, make sure you have the following installed:
	-PostgreSQL
	-Flask
	-psycopg2

1.) Unzip the 'psql' folder and run the following command from that directory:
		
	psql -U [YOUR USERNAME] [DATABASE NAME] < data.sql

2.) Create a 'config.py' in the top directory, with the following lines:
	
	database = '[YOUR DATABASE NAME]'
	user = '[YOUR USERNAME]'
	password = '[YOUR PSQL PASSWORD]'

3.) Run the following command in the top directory:
	
	python3 app.py localhost 5000

4.) Navigate to http://localhost:5000 OR http://127.0.0.1:5000 on your browser

--------------------------------------------------------------------------
--------------------------------------------------------------------------

AUTHORS: Aaron Bronstone and Jack Owens

--------------------------------------------------------------------------
--------------------------------------------------------------------------

DATA: A PSQL dataset of over 45,000 movies, with the following metadata:
	-Titles
	-Directors
	-Cast
	-Crew
	-Collections
	-Genres
	-Keywords
	-Languages
	-Production companies
	-Production countries
	-Popularity
	-Average rating

--------------------------------------------------------------------------
--------------------------------------------------------------------------

Copyright:
	Vidinfo 2022
	Kaggle raw CSV files: https://www.kaggle.com/datasets/saurabhbagchi/books-dataset


--------------------------------------------------------------------------
--------------------------------------------------------------------------
