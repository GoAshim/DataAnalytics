# WebScraping

Here I wrote python programs to scrap public data available in the web for the following scenarios -

* Gather the statistics of all NBA players in 2021-22 season from the [Basketball-reference](https://www.basketball-reference.com/leagues/NBA_2022_totals.html) site. This data is available in one long table in one page, which we will scrap and populate the data into a dataframe for future analysis.

* Gather the statistics of all time top 1000 movies from [IMDB](https://www.imdb.com/list/ls006266261/) site. This data is divided into multiple pages, each page has information of 100 movies. So our program will scrap each page to collect the necessary information of each movie and then go to the next page to repeat the process till it reaches to the last page. We are going to store the data into two dataframes for future analysis.
 
* In this program we will again work on statistics of NBA players. However instead of scraping stat of 2021-22 season of the players, which we did on the first program, we will take every players played in 2021-22 season and then go to their individual page and collect the statistics of every seson that player has played both in regular and playoff season. So essentially we will end up having the entire career statistics of every players played in 2021-22 season, we then will populate the data into a dataframe for future analysis.
