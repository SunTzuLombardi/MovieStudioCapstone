
[msft_building.jfif](./images/msft_building.jfif)

# Microsoft Movie Studio Recommendation

## Overview

This project analyzes movie data in order to create a portfolio strategy for entrance into the Entertainment industry.

## Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

## Data

In the folder [zippedData](https://github.com/learn-co-curriculum/dsc-phase-1-project/tree/master/zippedData) are movie datasets from:

- Box Office Mojo (Links to an external site.)
- IMDB (Links to an external site.)
- Rotten Tomatoes (Links to an external site.)
- TheMovieDB (Links to an external site.)
- The Numbers

In the data directory, cleaned data was submitted with the github repo along with more data scraped from The Numbers

## Methods

From the Production Budget perspective and WorldWide Gross perspective, recent data was pinpointed to focus on successful movies in the medium budget range.
- Medium Range of Production Budgets 2M USD to 80M then capped at 65M
- Whose ROI% was greater than 150% or 2.5 times the investment
- Only recent movies since 2010
- Comparing MPAA Ratings and investigating Sources of Content



## Results

Initial movie data shows that 65% of all movies are not successful.  We looked at the 533 which had an ROI% of >= 150%

[roiBoxplot.png](./images/roiBoxplot.png)

Average ROI% of all Genres shows Horror,Mystery, and Thriller as top earners.
[ax4_genre.png](attachment:./images/ax4_genre.png)

Excluding movies with MPAA Rating of R or greater shows a differnet pictur and Horror and Drama actually rank the worst.
[noR_genre.png](./images/noR_genre.png)

## Conclusions

Empower Studios Portfolio Strategy includes<br>
- Embrace or Protect Brand Horror Mystery Thriller Highest ROI% <br>
- Produce No R -Drama, Comedy and Romance, Disney Approach <br>
- Produce 5 to 8 films per year in the <$20M budget Range <br>
- Release in Summer or late Fall <br>
- Looking for 50% Original Content 50% Book Source or Factual Events other


## Next Steps

- Analysis of Successful Producers, Directors, Cinematographers, Actors
- Associating critical rating with success
- Academy Awards nominations with successful box office

## For More Information

See the full analysis in the [Jupyter Notebook](https://github.com/SunTzuLombardi/MovieStudioCapstone/blob/main/code/eda_notebook.ipynb) or review this [presentation](https://github.com/SunTzuLombardi/MovieStudioCapstone/blob/main/presentation.pdf)

For additional info, contact Daniel M. Smith at danielmsmith1@gmail.com

## Repository Structure

├── code<br>
│   ├── __init__.py<br>
│   ├── WebScrape_theNumbers.ipynb<br>
│   ├── initial_load_clean.ipynb<br>
│   └── eda_notebook.ipynb<br>
├── data<br>
├── images<br>
├── __init__.py<br>
├── README.md<br>
├── presentation.pdf<br>
└── student.ipynb<br>

