# Election_Analysis

## Project Overview
The purpose of this project is to complete an election audit of tabulated results for the US congressional election Colarado. A Colarado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.
1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
 
The election commission has requested some additional data to complete the audit:
1. The voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

### Election-Audit Results:
    * Calculate the total number of votes cast.
      The total number of votes counted by a for loop through the election_results.csv file
   ![Total number of votes](Resources/Total_number_of_votes.png?raw=true "Total number of votes")

    * A breakdown of the number of votes and the percentage of total votes for each county in the precinct.
        The votes for each county is calculated using 'if' statement and the  percentage of each county is calculated using 'for' loop.

 ![Number of votes for each county](Resources/County_Vote_Count.png?raw=true "Number of votes for each county")
 ![Percentage of votes for each county](Resources/County_Vote_Percentage.png?raw=true "Percentage of votes for each county")
    
    * Which county had the largest number of votes?
        An if statement is used to determine which county had the largest number of votes.
 ![County with largest number of votes](Resources/County_max_votes.png?raw=true "County with largest number of votes")

    * Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
 ![The number of votes and the percentage votes each candidate received](Resources/Candidate_Percentage_of_votes.png?raw=true "The number of votes and the percentage votes each candidate received")

    * Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
![Winning candidate](Resources/Winning_Candidate_Result.png?raw=true "Winning candidate")

### Election Results Printed to the Terminal
![Election Result](Resources/Election_Result_CommandLine.png?raw=true "Election Result" )

### Election Results Saved to a Text File
![Election result in text file](Resources/Election_Result_TextFile.png?raw=true "Election result in text file")

  

The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane

- The candidates results were:
    - Charles Casper Stockham received 23.0% of votes and 85,213 number of votes.
    - Diana DeGette received 73.8% of votes and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of votes and 11,606 number of votes.   

- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

- The voter turnout and the percentage of votes from each county
    - Jefferson: 10.5% (38,855)
    - Denver: 82.8% (306,055)
    - Arapahoe: 6.7% (24,801)

- The county with the highest turnout
    - largest County Turnover: Denver

    
## Summary
We can modify the script to use it for local elections and Senatorial districts. The modifications we need to do are as below,
1. Allow user to enter the input and output files so that the election audit program can be run on any election data file.
2. To accomodate the type of elections, we need to remove county related hard coding and accept the type from the user. Example, instead of county in congressional elections we should use Patries for Senatorial/Presidential election.



