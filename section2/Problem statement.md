# Formulate the question

How can we maximize our revenue (of a movie)

# Gather the data

We need two pieces of information: 

## Data on feature 
Movie budgets in USD

## Data on target
Movie revenue in USD

This data was gathered from the website The Numbers. 

# Clean the data

First, we delete movies that have not been released.
We do this by deleting the movies with exactly 0 in revenue. 
Then, we dont care if it was domestic gross or worldwide gross, we just care about the total gross, and budget. we dont even care about the title, release date, rank, etc. 