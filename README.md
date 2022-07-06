# WebScraping

Here I wrote python program to scrap public data available in the web for the following scenarios -
* Gather the statistics of all NBA players in 2021-22 season from the [Basketball-reference](https://www.basketball-reference.com/leagues/NBA_2022_totals.html) site. This data is available in one long table in one page, which we will scrap and populate the data into a dataframe for future analysis.

* Gather the statistics of all time top 1000 movies from [IMDB](https://www.imdb.com/list/ls006266261/) site. This data is divided into multiple pages, each page has information of 100 movies. So our program will scrap each page to collect the necessary information of each movie and then go to the next page to repeat the process till it reaches to the last page. We are going to store the data into two dataframes for future analysis
