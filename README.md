# Election_Analysis
## Project Overview
In this analysis have assist Tom, a Colorado bord employee, in an election audit results for Colorado
in this Analysis we will determine the : 
1.	Total number of votes cast
2.	A complete list of candidates who received votes
3.	Total number of votes each candidate received
4.	Percentage of votes each candidate won
5.	The winner of the election based on popular vote

## Resources
This analysis has been done by using a powerful code editor name Visual Studio Code1.38.1, write our code and run it in to the terminal and python 3.6.1
The data sources is a CSV file provided by the election bord: election_results.cvs
## Summary

The analysis of the election results shows that 

* Total number of votes cast 369 711 votes
* list of candidates who received votes :
  * Charles Casper Stockham
  * Diana DeGette
  * Raymon Antohony Doane
  
* The Total number of votes each candidate received and Percentage of votes each candidate won
  * Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes
  * Diana DeGette: received 73.8% of the vote and 272,892 number of votes
  * Raymon Anthony Doane: received 3.1% of the vote and 11,606 number of votes
  
* The winner of the election based on popular vote
  * Winner of the election is Diana DeGette who received 73.8% of the vote and 272,892 number of votes

# Challenge Election_Analysis

## Project Overview

In this analysis we will be assisting Tom, a Colorado bord employee, in an election audit results.
For that we will determine the : 

1-	The voter turnout for each county
2-	The percentage of votes from each county out of the total count
3-	The county with the highest turnout
5-	The number of votes and the percentage of the total votes each candidate received.
6-	The candidate that won the election, their vote count, and what was their percentage of the total votes

## Resources

This analysis has been done by using a powerful code editor name Visual Studio Code1.38.1, write our code and run it in to the terminal and python 3.6.1
The data sources is a CSV file provided by the election bord: election_results.cvs

## Election-Audit Results: 

The analysis of the election results shows that 

* Total number of votes cast is : 369 711 votes

* Breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  * Jefferson received 10.5% of the vote and 38,855 number of votes
  * Denver received 82.8% of the vote and 306,055 number of votes
  * Arapahoe received 6.7% of the vote and 24,801 number of votes

* County had the largest number of votes ?
  * Denver have the largest number of votes

* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  * Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes
  * Diana DeGette: received 73.8% of the vote and 272,892 number of votes
  * Raymon Anthony Doane: received 3.1% of the vote and 11,606 number of votes

* The candidate that won the election, and its vote count, and  percentage of the total votes?
  * The Winner of the election is Diana DeGette who received 73.8% of the vote and 272,892 number of votes


## Election-Audit Summary

This script can be used for other election as we have address index instead of fixed variable when writing the code.  We will advise the election commission to keep the format of the file the same for its election.
But if the column changed, we will just have to change the index.
For example if the column candidate name move to the second column and the county name to the third we will update the code as below.

Get the candidate name from each row.
        candidate_name = row[1]
        # 3: Extract the county name from each row.
        county_name = row[2]

Also we suggest the election commission to keep the below code in our scrip for to load and save the text result,
But they can also use the direct link to tell python where to load the document directly by using the below codes :
files_to_load = Resources/election_results.csv
files_to_save = analysis/election_results.csv










