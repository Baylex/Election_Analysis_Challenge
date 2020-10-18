# Election_Analysis_Challenge
UT Data Boot Camp Module 3 Challenge Using Python to Analyze Election Results

## Project overview
A Colorado Board of Elections employee assigned the following tasks to the analyst to complete the election audit of a recent local congressional elections.  After the winners were determined, the representation of county votes was also calculated. 

1. Calculate the total number of votes cast.
2. Get the complete list of county votes.
3. Calculate the total number of votes by county. 
4. Calculate the percentage of representation by county. 
5. Determine the county with the largest voter turnout. 
6. Get a complete list of candidates who received votes.
7. Calculate the total number of votes each candidate received.
8. Calculate the percentage of votes each candidate von.
9. Determine the winner of the election based on popular vote.

## Resources 
- Data Source : election_results.csv
- Software : Python 3.7.9, Visual Studio Code version 1.50.1

## Challenge Overview of Results
1. Total Votes in the Colorado Board of Elections: 369,711
2. Votes by County:
 - Jefferson: 10.5% (38,855)
 - Denver: 82.8% (306,055)
 - Arapahoe: 6.7% (24,801)
3. Largest County Turnout: Denver
4. Votes by Candidate:
 - Charles Casper Stockham: 23.0% (85,213)
 - Diana DeGette: 73.8% (272,892)
 - Raymon Anthony Doane: 3.1% (11,606)
5. Declare the Winner of the Election: 
 - Winner: Diana DeGette
 - Winning Vote Count: 272,892
 - Winning Percentage: 73.8%
 
After reviewing the 369,711 total votes, Denver County had the highest voter turnout, and the winner of the election is Diana DeGette with 272,892 votes representing a supermajority of 73.8% of all votes, meeting the popular majority criteria of greater than or equal to 50.1%. 
 
## Challenge Summary
In this election, the winner had a supermajority, but the criteria was for a popular vote, greater than or equal to 50.1%.  This script could be easily modified to run a check for a supermajority, greater than or equal to 66.7% of the votes as the election criteria.  A second way to change the code, with the county data, weights could be assigned to the counties to represent the weights of the electoral college votes.  With these 2 changes to the script, perhaps the election commission would consider a business proposal to make these two adjustments, and the script could calculate almost any election.  

## Text File Printout of Results
![Pic 4](https://github.com/Baylex/Election_Analysis_Challenge/blob/main/Text_Devliverable2.PNG)
