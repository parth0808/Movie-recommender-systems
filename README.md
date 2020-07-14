# Movie-recommender-system
### Datasets 

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)

### My Application

I've developed a similar application called "The Movie Cinema" which supports all language movies. But the only thing that differs from this application is that I've used the TMDB's recommendation engine in "The Movie Cinema". The recommendation part developed by me in this application doesn't support for multi-language movies as it consumes 200% of RAM (even after deploying it to Heroku) for generating Count Vectorizer matrix for all the 700,000+ movies in the TMDB. 

Link to my application: https://movie-recommender-app-001.herokuapp.com/

### Libraries Used
1. Flask==1.1.1
2. gunicorn==19.9.0
3. Jinja2==2.10.1
4. MarkupSafe==1.1.1
5. Werkzeug==0.15.5
6. numpy>=1.9.2
7. scipy>=0.15.1
8. nltk==3.5
9. scikit-learn>=0.18
10. pandas>=0.19
11. beautifulsoup4==4.9.1
12. jsonschema==3.2.0
13. tmdbv3api==1.6.1
14. lxml==4.5.1
15. urllib3==1.25.9
16. requests==2.23.0
17. pickleshare==0.7.5
