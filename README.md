# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast/
2. Get a complete list of candidates who recieved votes,
3. Calculate the total number of votes each candidate recived.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on pupular vote

## Resources
-Data Source: election_results.csv
-Software: Python 3.7.6, Visual Code Studio 1.67.1 

## Summary:
The analysis of the election show that:
-There were 369,711 votes cast in the electon.
-The candidates were
  -Charles Casper Stockham
  -Diane DeGette
  -Raymon Anthony Doane
 -The candiate results were
  -Charles Casper Stockham: 23.0% (85,213)
  -Diana DeGette: 73.8% (272,892)
  -Raymon Anthony Doane: 3.1% (11,606)
 -The winner of the election was: 
  -Diane DeGette, who received 73.8% of the vote and 272,892 number of votes
  
## Overview of Election Audit
  After helping Seith and Tom submit the original election audit results, the election commission requested additional data to complete the audit. 
  -The commission requested the following information be added to the audit.
    1. The voter turnout for each county
    2. The percentage of votes from each county out of the total count
    3. The county with the highest turnout
  -The purpose of this audit is to visualize the results of the election by looking at who won the election based on popular vote and by looking at what county had the highest turnout.
   -These results will provide useful information when looking at what county had the biggest pull in the election results.
   
## Election Audit Results:
-How many votes were cast in this congressional election?
  -369,711 votes were cast in this congressional election.
  -<img width="234" alt="Total Votes" src="https://user-images.githubusercontent.com/104036750/168720758-8ff13fe4-c4df-401b-941e-11555033c4b3.png">
 
-Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  -Jefferson County had 38,855 votes submitted, which is 10.5% of the total votes.
    -Only a small portion of the total votes came from Arapahoe County, which causes it to not have is much pull in the election.
  -Denver County had 306,055 votes submitted, which is 82.8% of the total votes.
    -The vast majority of the total votes submitted came from Denver County, therefore it had the largest affect on the results of this election
  -Arapahoe County had 24,801 votes submitted, which is 6.7% of the total votes.
    -Only a small portion of the total votes came from Arapahoe County, which causes it to not have is much pull in the election.
  -<img width="212" alt="County Votes" src="https://user-images.githubusercontent.com/104036750/168720843-b2f93331-421e-4392-9c7e-46766428a7cd.png">

-Which county had the largest number of votes?
  -Denver had the largest number of votes, which can be seen on the Largest County Turnout line of the election_analysis.txt file
  -<img width="234" alt="Largest County Turnout" src="https://user-images.githubusercontent.com/104036750/168720983-912360fd-bacf-417c-82ce-465fddec6c8b.png">
  
-Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  -Charles Casper Stockham received 85,213 votes, which is 23.0% of the total votes submitted
  -Diana DeGette received 272,892 votes, which is 73.8% of the total votes submitted
  -Raymon Anthony Doane received 11,606 votes, which is 3.1% of the total votes submitted
  -<img width="288" alt="Canidate Results" src="https://user-images.githubusercontent.com/104036750/168721015-8126adfe-96c5-4e3f-b47a-0a1868b4008e.png">

-Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  -Diana DeGette won the election.
  -She received 272,892 votes
  -She received 73.8% of the total votes submitted
  -<img width="206" alt="Election Winner" src="https://user-images.githubusercontent.com/104036750/168721051-c3157a32-577f-4eef-bbca-633fe2049591.png">
 
## Election Audit Summary
-The results of this audit can be extremely valuable for future canidates. Canidates can use this data to target specific areas that contain the largest portion of voters.
-This script can be useful in many types of elections whether that being at the local, state, or governmental level. In order to use this script for any election a few modifications can be made:
1: Instead of showing counties, you could gather data on/display districts if it is for a local election.
2: Instead of showing counties, you could gather data on/display states if it is for a national election.
