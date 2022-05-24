# **Election-analysis**

## *Overview*

The purpose of this election audit analysis was to determine the performance of each candidate in the election, and the turnout of each county within the respective precint. Regarding candidate information, this analysis provides the results of each candidates' vote counts, the percentage of votes won, the winning candidate, and the winning candidate's vote count and percentage. We also are able to see information for counties such as their turnouts regarding vote counts and percentages for each county as well as the county with the largest turnout.

## *Election-Audit Results*

* Total Congressional Votes: 369,711
* County vote count and percentage breakdown:
  * Jefferson: 10.5% (38,855)
  * Denver: 82.8% (272,892)
  * Arapahoe: 6.7% (24,801)
* County with the largest voter turnout: Denver
* Candidate vote count and percentage breakdown:
  * Charles Casper Stockham: 23.0% (82,213)
  * Diana DeGette: 73.8% (272,892)
  * Raymon Anthony Doane: 3.1% (11,606)
* Winning cadidate: Diana DeGette
  * Winning Vote Count: 272,892
  * Winning Percentage: 73.8%

## *Election-Audit Summary*

As seen in the provided .txt file in the repository, this script is able to output results based on the CSV data provided. I believe that this makes this script quite versatile. By just changing the file path to a different CSV data set, you will be able to conduct multiple analyses while achieving the same results (given that the CSV is formatted in a similar way). Another modification that could be made would be to add in a worst performer metric, by using the same logic as the script used in to produce the winning candidate results. However you would have to initialize the vote variable to infinity and use the < rather than > within the if statement. 
