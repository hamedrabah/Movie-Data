# Does a Blockbuster Budget make a Blockbuster Film?

###### Hamed Rabah (hr277), William Ford (wbf32), Steven Lai (sl2642)

## About the Data
Our project implemented two data sets. We obtained both of them from Kaggle.com. The first dataset was a collection of movie meta data of the 100 most note worthy movies of all time as judged by revenue. This dataset had many columns: The age of the film, release date, voter score, its total revenue, its popularity, the run time, the budget, and the original language.

The other dataset we used was a TSV focusing on 50 noteworthy films of various budgets and revenues. The data was broken down with rows corresponding to release dates, box office, national box office, worldwide box office, and film budget.

## Data Processing
The datasets were provided in CSV and TSV format, and thus D3 interpreted all the values as strings. For processing, we iterated through each row in each of the datasets and reinterpreted each value as the correct type through casting strings to numbers and plotting numeric objects based on the numeric value of the budget and box office.

## The Argument
Our plot compares the worldwide grossing amount of a film compared to its budget. The intention is to show that while large budget films are often associated with quality, this is not always the case.

What we found was that as in the majority of cases, a large film budget, had a miniscule, if any, affect on the overall success of the film beyond a certain point (~$175 million). While before this point a lower budget is associated with lower revenue, beyond this, with the exception of a few outliers, there appears to be little connection with the budget of a film to its worldwide gross. 
