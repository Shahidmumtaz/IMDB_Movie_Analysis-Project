# Project_1
The Internet Movie Database (IMDb) is a website that serves as an online database of world cinema containing a large number of public data on films such as the title of the film, the year of release of the film, the genre of the film, the audience, budget, revenue, the rating of critics, the duration of the film, the summary of the film, actors, directors and much more.

Scope & Purpose:
Analyze the data available on IMDB for movies released between 2000 and 2019.

Questions that our analysis will answer:
Which genres have the most movies?
Which genres have high production budgets?
Which genres are more profitable?

Data Exploration:
After hunting for data on the internet, we used the IMDB database and an API key to extract raw data.  This database contains a large volume of unstructured data which need to be cleaned and structured for use in research and education.

Data cleanup:
Inventorying data
Data selection
Movie title
Genre
Year
Budget
Revenue
IMDB’s code is HTML, CSS & Javascript, after parsing and recovering data, we developed a csv file and JSON to conduct analysis on.
Used python script to scrape data
Updated python script to not take into account movies with missing data.

Analysis process: Used pandas library to have an overview of the datasets.  The following are category types for our statistical data analysis and modeling:
Genre
Budget
Revenue
Rating

Findings:
Nearly 62% of the titles are comprised of Action, Comedy, and Drama. The other 38% comprises the rest of the genres.
51% of the Total Mean Budget is comprised of Adventure, Animation, Action, Fantasy, Science Fiction. The other 49% comprises the rest of the genres.
Percentage wise, Mean Revenue correlates fairly well with the Mean Budget given the respective genre.
History, Mystery, and Horror genres give the biggest  bang for the buck.
A decent positive correlation exists between Budget and Profit for Adventure films; however, quite a few films showed close to 0 or negative profitability. Given this fact, producers should perform plenty of market research before making an Adventure film.





