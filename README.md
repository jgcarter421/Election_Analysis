# Election Analysis

## Overview of Election Audit
A Colorado Board of Elections employee gave me the following tasks to complete in order to audit a recent election in a Colorado precinct.
  * Calculate the total number of votes cast in the election.
  * Calculate the total number of votes cast in each county.
  * Calculate the percentage of votes from each county, out of the toal vote count.
  * Calculate the county with the hight voter turnout.
  * Calculate the total number of votes cast per candidate.
  * Calculate the percentage of votes for each candidate.
  * Calculate the winning candidate of the election.
For this election audit, I used Python, version 3.9.7, to read the election results from a csv file and to write the analysis in a text file.
    * This text file is saved as election_analysis.txt in the Analysis folder.

## Election-Audit Results
In this election, there were 369,711 votes cast.

### County Breakdown
The following is a breakdown of the total votes cast and the percentage of votes cast per county:
  * Jefferson County had 10.5% of the vote count, with 38,855 votes cast.
  * Denver County had 82.8% of the vote count, with 306,055 votes cast.
  * Arapahoe County had 6.7% of the vote count, with 306,055 votes cast.

<b>Denver County had the overwhelmingly largest voter turnout.<b>

### Candidates
The candidates for this election were the following:
  * Charles Casper Stockham
  * Diana DeGette
  * Raymon Anthony Doane
### Candidate Vote Count
  * Charles Casper Stockham received 23.0% of the vote with 85,213 votes cast for him.
  * Diana DeGette received 73.8% of the vote with 272,892 votes cast for her.
  * Raymon Anthony Doane received 3.1% of the vote with 11,606 votes cast for him.

### Winner
 * Diana DeGette received 73.8% of the vote with 272,892 votes cast for her.
<img width="284" alt="Screen Shot 2022-03-26 at 9 49 19 PM" src="https://user-images.githubusercontent.com/99417460/160264592-cbe28277-1149-4a77-8285-93652958441f.png">

## Election-Audit Summary
This code (scrpt) analyzing the election can be used for any election to determine vote counts, percentage, locations of the votes, and determine the winner.  Using this code, it will be much faster and more accurate to count and tally the votes of the election and determine the winner, rather than analyzing each vote by hand.  All that would be needed to do would be to change the variables.  For example, in a federal election, one could change the following:
  county_options = [] to state_options = []
  county votes = {} to state_votes ={}
  and
  largest_county = "" to largest_state = "".
  
