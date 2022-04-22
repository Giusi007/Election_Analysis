# Colorado Election Analysis
Analysis of local election to validate results.

## Candidate Analysis Overview
This project involved validating election results from an election in Colorado. The Colorado Board of Elections asked for the following candidate information regarding the election:

1. The total number of votes cast.
2. A complete list of candidates who received votes.
3. The total number of votes each candidate received.
4. The percentage of votes each candidate won.
5. The winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.10, Visual Studio Code 1.66.2

### Candidate Analysis Results
The analysis of the election by candidate shows that:
- There were 369,711 total votes cast in the election.
- The candidates in the election were:
      - Charles Casper Stockham
      - Diana DeGette
      - Raymon Anthony Doane
- The results were:
      - Charles Casper Stocham received 23.0% of the votes with a total of 85,213 votes.
      - Diana DeGette received 73.8% of the votes with a total of 272,892 votes.
      - Raymon Anthony Doane received 3.1% of the votes with a total of 11,606 votes.
- The winner of the election was:
      - Diana DeGette won with 272,892 votes, which accounted for 73.8% of the vote.

## County Analysis Overview
In addition to analyzing the results of the election based on each candidate, we also examined voter turnout in three counties: Araphoe, Denver, and Jefferson.

### County Analysis Results
The analysis of the election by county shows that:
- There were 369,711 total votes cast in the election.
- The number of votes cast in each county, and the percentage of the total vote from each county were:
      - 24,801 votes were cast in Arapahoe county, making up 6.7% of the total vote.
      - 306,055 votes were cast in Denver county, making up 82.8% of the total vote.
      - 38,855 votes were cast in Jefferson county, making up 10.5% of the total vote.
 - The county with the largest turnout was:
      - Denver
 
 # Election Analysis Summary
Using the Python script written for this analysis, we were able to analyze a large data set in order to determine the number of votes cast in an election and how those votes break down by candidate and by county. We were able to determine the winner of the election, the county with the largest voter turnout, and percentage of votes that each candidate received, and the percentage of votes that came from each county.

The value of this script is apparent in the results of this analysis, and it can be used again in the future. Replacing the data in the file that is being read in this analysis would allow us to run the script on future elections as long as the data is organized in the same way in a CSV file. We could also add additional code to this script to analyze the percentage of votes that candidates received in each county so that we can determine the winner in each county. 
