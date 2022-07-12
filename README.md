# Election_Analysis

## Project Overview
This project conducts an audit of a congressional election in Colorado using data provided by an election employee. The project utilizes election data to provide the following: 
- The total number of votes cast
- The total and percentage of votes cast per county
- A complete list of candidates who received votes
- The total number and percentage of votes each candidate received
- The winner of the election (based on popular vote)

## Resources
- Data Source: election_results.csv
- Software: Python 3.7, Visual Studio Code 3.7.6

## Election Audit Results
- There were 369,711 votes cast in the election
- The total and percentage of votes per county were: 
     - Jefferson: 10.5% of votes and 38,855 votes
     - Denver: 82.8% of votes and 306,055 votes
     - Arapahoe: 6.7% of votes and 24,801 votes
- The largest county turnout was Denver
- The candidates were: 
     - Charles Casper Stockham
     - Diana DeGette
     - Raymon Anthony Doane
- The candidate results were: 
     - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes
     - Diana DeGette received 73.8% of the vote and 272,892 number of votes
     - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes
- The winner of the election was: 
     - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes

## Challenge Overview
In order to identify the total number of votes and percentage of the total vote per county, we primarily utilized decision statements with logical operators. It was necessary first to make a list of counties and then add the total number of votes each county received to a dictionary, as show below. 

INSERT IMAGE

After creating a list of counties and the total votes that each county had, a for loop was utilized to calculate the percentage of the total vote that a county had. Following this for loop, a condictional statement was added to identify the county with the hightest voter turnout. 

INSERT IMAGE 2

## Challenge Summary
This Election Analysis script could be easily modified to support the election commission or specific campaigns in the future. With the addition of the total registered voters per county, the election commision could use this code with small modification to identify voter turnout percentages per county (total votes / total registered voters). This could support the election commission in making decisions on where to expend resources like improved advertising or more polling stations to increase voter turnout.

Specific campaigns could best utilize this script by identifying a candidate breakdown per county. This would allow candidates to understand where they could best expend their campaign energy. This would be even better utilized with a set of polling data that included which county the voter lived in and who they intended to vote for in an upcoming election.
