# Election_Analysis

## Overview

A colorado board of elections employee has asked us to audit a recent congresional election. The tasks we needed to complete are as follows:

1. Calculate the total number of votes cast
2. Get a complete list of canidates who received votes
3. Calculate the total number of votes each canidate received.
4. Calculate the percentage of votes each canidate won.
5. Determine the winner of the election based on popular vote.

## Resources

 - Data source : ecetion_results.csv
 - Software: Python 3.7.6, Visual Studio Code

 ## Summary

 The analysis of the election shows that:

  - The total number of votes cast was 369,711 votes.
  - The cadidates who received votes were:
        Charles Casper Stockham
        Diana DeGette
        Raymon Anthony Doane
  - The canidate results were:  
        Charles Casper Stockham: 23.0% of the vote with a total of 85,213 votes.
        Diana DeGette: 73.8% of the vote with a total of 272,892 votes.
        Raymon Anthony Doane: 3.1% of the vote with a total of 11,606 votes.
  - The winner of the election was Diana DeGette who won 73.8% of the vote with a total of 272,892 votes.
    

## Challenge overview

For our challenge, we were asked to find out more details pertaining to the election data. What we were looking for specifically was:

  - The voter turnout for each county
  - The percentage of votes from each county out of the total count
  - The county with the highest turnout

In order to find these results, a new Python code was written. This code can be reviewed in this repo by clicking PyPoll.Challenge.py. The code gave us the following results:

![Election_results_screenshot](https://user-images.githubusercontent.com/87949792/144537117-8e65fa56-4c56-469d-9880-a727ce5be4fe.png)

Our results are as follows: 

  - Jefferson county accounted for 10.5% of the total vote, with a vote count of 38,855 votes
  - Denver county accounted for 82.8% of the vote, with a vote count of 306,055 votes
  - Arapahoe county accounted for 6.7% of the vote, with a vote count of 24,801 votes

  - Denver county had the largest number of votes
   


## Challenge Summary 

Our code is extremely malleable, so long as we are given the raw voter data for whatever county we find interest in. This code can provide many insights: knowing where the larger percentage of voters are can infrom a candidate on where they should focus their campaign efforts. With more couties of colorado provided, we can determine what spots to hit hard with a campaign in a future election. It would also be usueful to know what percentage of the population did NOT vote - knowing where voters are untapped can hold lots of potential energy, so long as you have a candidate that excites voters to the polls! 


 

