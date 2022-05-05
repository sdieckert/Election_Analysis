# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the elections based on popular vote.
6. Get a complete list of counties where votes where cast.
7. Calculate the total number of votes in each county.
8. Calculate the percentage of votes cast in each county.
9. Determine which county had the largest number of votes. 

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.66.2

## Summary
The analysis of the election shows that:
- There were 369,711 total votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockam received 23.0% of the votes and 85,213 number of votes.
  - Diana DeGette received 73.8% of the votes and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the votes and 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette who received 73.8% of the vote and 272,892 number of votes.
- The counties where votes were cast:
  - Jefferson
  - Denver
  - Arapahoe
- The voter turnout for each county:
  - Jefferson received 10.5% of the votes and 38,855 number of votes.
  - Denver received 82.8% of the votes and 306,055 number of votes.
  - Arapahoe received 6.7% of the votes and 24,801 number of votes.
- The county with the largest voter turnout:
  - Denver county who received 82.8% of the votes and 306,055 number of votes.

Results Printed to Command Line:

![election_results_terminal](https://user-images.githubusercontent.com/87085239/166861341-60f97e4c-57ef-4f0c-af0f-35288df725c3.png)


Results Printed to Text File:

![election_results](https://user-images.githubusercontent.com/87085239/166860856-d7c7db2a-d029-437b-baec-c4ade1210592.png)


## Election-Audit Summary
As demonstrated by the additional request to analyze voter turnout by county, the current python script is adaptable for additional analysis with relative ease. The code is setup in a format that only needs to be duplicated for any new analysis by addiing new variables, copying and replacing the new variables in the code and adding new text output. 

Because of the flexibility with the script, it could be utilized for many types of elections such as local, state and federal with replacing the counties with districts or states. Should a new election_results file be provided based on multiple races and positions, a new list could be added for position allowing for the analysis to be grouped by elected position. In addition, because the script is easily adaptable, new voter insights can be obtained, such as percentage of each candidates' total vote within each distict, county, or state by adding a nested for loop. This would provide valuable informaiton for targeting those areas with low voter turnout and distribution of voters' party affiliation.




