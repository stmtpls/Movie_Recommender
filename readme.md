# Movie Recommender using MapReduce

## TLDR

The program uses as input parsed data from online platforms, in the form of csv files and by providing a userId and movieId and returns a top 5 movie selection using the following criteria:

1. Gengres' relativity (movies with the highest matching in relation to the given movie appear on top)
2. Populatity and ratings (aggregate of all the ratings by users that have evaluated each movie)
3. Release year (presenting movies close to the release year of the given movie - in the same decade)

All the steps of the process are thoroughly presented in the project's report.

## Tools used

- Python 3
- Jupiter Notebook
- PySpark


## Key take-aways

- Genres are the most important aspect in regards to movie recommendation
- Parallel computing can significantly improved performance and be scaled into large changing databases


## Areas for improvement

- Analysis of the past movie selections / evaluations of the current user creating personalized suggestions
- Filtering and weighting of other users' reviews, focusing on users similar to the current user optimizing the results