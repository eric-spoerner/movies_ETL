# ETL Process using movie data
This readme is a work in progress.
## Project overview
Using information about individual feature films from both Kaggle and Wikipedia, along with user ratings data from Kaggle, extract and transform all three data sources using Pandas and Jupyter Lab, and migrate completed data set into a PostgreSQL database.
## Resources
* Postgres/pgAdmin
* Python
* Jupyter lab
* sqlalchemy
* pandas
* numpy
## Design
## Next steps
* Refactor clean_movie() function to consume external csv map for column cleanup
* Refactor code to better ensure encapsulation best practices are enforced.  Eliminate duplicative code among indivdiual .py files.
* Enhanced cleanup of writer column to support unified list with screenwriters etc.git stat