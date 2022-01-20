# election_analysis
Module 3 Election Analysis Project
## Overview of Election Audit:
The purpose of this project was to complete an audit of election results using Python and Visual Studio code. We wanted to further examine results by county, looking at total votes per county, turnout percentages, and which county had the highest votes. We also wanted to take a deeper dive into the winning candidate, how many votes each candidate received, and each candidates' vote share. Once we had our results, we copied them to a text file to share with Seth, Tom, and the election commission.

![alt text](https://github.com/aisligrace/election_analysis/blob/main/Module%203%20Deliverable%201%20Results.png)


## Election-Audit Results:
* How many votes were cast in this congressional election?

  369,711
  

* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

  Jefferson: 10.5% (38,855)

  Denver: 82.8% (306,055)

  Arapahoe: 6.7% (24,801)
  


* Which county had the largest number of votes?

  Denver
  

* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

  Charles Casper Stockham: 23.0% (85,213)

  Diana DeGette: 73.8% (272,892)

  Raymon Anthony Doane: 3.1% (11,606)
  

* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

  Diana DeGette: 272,892 total votes (73.8%)
  
## Election Audit Summary
Now that we have created this script that includes all our findings, it would be both efficient and cost effective to use it again for future elections. You would only need to make simple changes depending on what you were looking for. For example, if you wanted to examine at the precinct level instead of county, you would just sub out the county specific code for precinct. 

As opposed to:

county_options = []
county_votes = {}

You could use:

precinct_option = []
precinct = {} 

And go from there. The code can be customized to fit the specific variables you are looking for. For example, if you were looking at a ballot initiative election instead of candidates, the following could be subbed out:

candidate_options = []
candidate_votes = {}

For this:

question_options = []
candidate_votes = {}

There are numerous ways to change this code to fit a specific election so we would highly suggest using it in the future as opposed to starting from scratch again. 

  
