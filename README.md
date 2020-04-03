# TMDB Movie Dataset Exploration
## by Alicia Bosch

## Data set

This notebook will explore a dataset that contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

## Main goal

The final goal of this analysis is to understand what makes a film more profitable. I will try to understand different features around its profitability and will finally fulfil this goal. I will mainly answer the following questions related to the profit:

- What are the top 20 most profitable movies?
- What are the top 20 actors who always work in highly profitable films?
- What genres are most popular from year to year? Is it related to a higher profit?

## Summary of main findings 

#### What are the top 20 most profitable movies?

This plot depicts how 'Star Wars' and 'Avatar' are the clear winner, with $2.75 B in profits.The top 5 films in profits are:
> 'Star Wars', 'Avatar', 'The Exorcist', 'Jaws', 'E.T'

Star Wars (only its top 5 films, not ALL the saga) made in PROFITS the amount of $8 B

#### What are the top 20 actors who always work in highly profitable films?

Out of the actors/actresses who have at least casted in 10 films, Daniel Radcliffe was the one actor that acted in really profitable films by a huge difference. Harry Potter's films paid off. He almost doubles the second in the list. He overpasses the 500M$ whereas the second in the list is around $27M.
Top 5 in this list are:
> Daniel Radcliffe, Robert Downey Jr., Will Smith, Tom Cruise, Kristen Stewart

Surprisingly there are only 4 woman out of the top20 list: Kristen Stewart, Kate Winslet, Sandra Bullock and Julia Roberts.

#### What genres are most popular from year to year?
Looking into the total number of films throughout the years, it seems that the Drama and Documentary genres are the winners in absolute terms. Funnily, in 2015 Documentaries seem to get a bid drop in its releases (from 26 to 15).

However, in relative terms, the tendency changes from the absolute ones. Drama and Comedy were highly popular until just before the 2000s. From the new century onwards, Drama continues on this popularity trend but the Comedy genre suddenly plummets, letting the Documentary genre come strongly into play and increase its popularity tendency.


## Resources
https://scentellegher.github.io/programming/2017/07/15/pandas-groupby-multiple-columns-plot.html
https://stackoverflow.com/questions/23377108/pandas-percentage-of-total-with-groupby
