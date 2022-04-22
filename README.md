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

The value of this script is apparent in the results of this analysis, and it can be used again in the future. The file that we are reading from is election_results.csv. The file that we are writing to is election_analysis.txt. These files are loaded into variables in lines 8-11 of the code attached to this analysis, as seen in this image:

![image](https://user-images.githubusercontent.com/100658772/164799471-cdccbe1c-8259-4178-a503-ac682294c85a.png)

If we wanted to analyze the results of more counties than only Arapahoe, Denver, and Jefferson, we could replace the election_results.csv file with a file that contains the data from all of the counties that we want to analyze, as long as the data is structured in the same way in the new file (Ballot ID in column A, County in column B, and Candidate in column C, as in the image below).

![image](https://user-images.githubusercontent.com/100658772/164799779-1e6e7777-e32a-4ad4-904f-b9f4db6bc8ec.png)

If we use this script to analyze a different file, we should also create a new .txt file to write the information to, and update the file name in the file_to_save variable to reflect the new .txt file.

This script could also be used to analyze election results from other states, as long as the data is structured in three columns with Ballot ID in column A, County in column B, and Candidate in column C.

