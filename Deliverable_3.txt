# Election_Analysis: PyChallenge

## Project (Challenge) Review
A Colorado Board of Elections employee has given you the following tasks to compelte the election audit of a recent local congressional election.

## Resources
- Data Source: election_results.csv
- Software: Python 3.10, Visual Studio Code 17.2.32210.308

##Overview of the Election Audit

1. Calculate the total number of votes cast.
2. Get a complete list of counties who voted.
    a. Calculate the total number of votes each county contributed.
    b. Calculate the percentage of votes county contributed.
    c. Determine the county with the largest turnout.
3. Get a complete list of candidates who received votes.
    a. Calculate the total number of votes each candidate received.
    b. Calculate the percentage of votes each candidate won.
    c. Determine the winner of the election based on popular vote.
    
###Election Audit Results

There was a total of 369,711 votes cast during this Colorado election. 

Denver had the largest turnout among counties, with 306,055 votes, which constitutes for about 82.8% of the total votes cast.
- Jefferson: 10.5% (38,855)
- Denver: 82.8% (306,055)
- Arapahoe: 6.7% (24,801)

The winner of the election was Diana DeGette, who won 272,892 votes, which constitutes for 73.8% of the total votes cast. 
- Charles Casper Stockham: 23.0% (85,213)
- Diana DeGette: 73.8% (272,892)
- Raymon Anthony Doane: 3.1% (11,606)

More information can be found in the election_analysis.txt

###Election Audit Summary

####The analysis of the election show that:
- There were "x" votes cast in the election.
- The candidates were:
  - Candidate 1
  - Candidate 2
  - Candidate 3
- The candidate results were:
  - Candidate 1 received "x%" of the vote and "y" number of votes.
  - Candidate 2 received "x%" of the vote and "y" number of votes.
  - Candidate 3 received "x%" of the vote and "y" number of votes.
- The winner of the election was:
  - Candidate (1,2, or 3), who received "x%" of the vote and "y" number of votes.
  
####The analysis of the largest vote per county show that:
- There were "x" votes cast in the election.
- The counties involved were:
  - County 1
  - County 2
  - County 3
- The county results were:
  - County 1 contributed "x%" of the vote and "y" number of votes.
  - County 2 contributed "x%" of the vote and "y" number of votes.  
  - County 3 contributed "x%" of the vote and "y" number of votes.
- The county that made the most contribution to this electrion process was:
  - County (1,2, or 3), who contributed "x%" of the vote, which is "y" number of votes.

####This script can be used for any election.

The foundation of both candidate-vote analysis and county-vote analysis are the same. Utilizing this code, we can apply it to any other electoral process- whether it be on a county level, state-level, or federal. Tailoring this code to utilize in bigger pools of populations would simply be the matter of giving it a new data set, and minorly modifying the names of variables to further clarify what we are trying to analyze.

Ex 1: The Electoral College Process can be analyzed with this code by assessing Candidates and Statewide electors. Further fine-tuning of the code may allow insight on which states contributed most to electing a certain candidate, and we can add dimentionality by also attributing the states' general political stance (Dem/Rep).
Ex 2a: Similarly, this code can very easily analyze the Popular Vote of the election. In this case, we will be looking at candidates and states, as well as state population.
Ex 2b: Inversely, knowing the total population eligible for voting in a state may allow us to calculate for how much of the population did not vote at this time, and this can be applied to all levels of the electoral process.

