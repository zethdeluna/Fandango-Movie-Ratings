# Fandango-Movie-Ratings
In this project, we'll be analyzing data collected on movies released in 2016 and 2017 and critique Fandango's former practice of rating movies on a 5 star scale. (Now, the ratings seen on Fandango are the "Tomatometer" and "Audience Score" produced by Rotten Tomatoes).

In October 2015, a data journalist named Walt Hickey wrote an article analyzing movie ratings data and found strong evidence to suggest that Fandango's rating system was biased and dishonest. Fandango is a popular website that aggregates movie ratings. Fandango used to display a 5-star rating system on their website, where the minimum ratings is 0 stars and the maximum rating is 5 stars.

Hickey found that there's a significant discrepancy between the number of stars displayed to users and the actual rating, which he was able to find in the HTML of the page. Here's what he found:

The actual rating was almost always rounded up to the nearest half star. For instance, a 4.1 movie would be rounded off to 4.5 stars, not to 4 stars.
In the case of 8% of the ratings analyzed, the rounding up was done to the nearest whole star. For instance, a 4.5 rating would be rounded off to 5 stars.
For one movie rating, the rounding off was completely off. The movie had a real rating of 4, but the website displayed a rating of 5 stars.
Fandango's officials replied that the biased rounding off was caused by a bug in their system rather than being intentional, and they promised to fix the bug as soon as possible.

In this project, we'll analyze more recent movie ratings data to determine whether there has been any change in Fandango's rating system after Hickey's analysis
