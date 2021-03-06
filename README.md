# Election-Analysis
## Overview of Election Audit

The purpose of this election audit was delivering several final products as a result of a Python code. The overall products involved election results. The first was obtaining the results of the election from around ~370,000 votes. These votes were counted from three counties: Jefferson, Denver, and Arapahoe and included three final candidates: Stockham, DeGette, and Doane. The results included the voter count by county, the count by candidate, and the largest turnout by county along with the winner of the election. All of this information printed both in the terminal and in a [text file](https://github.com/teachjanderson/Election_Analysis/blob/main/Resources/election_results.txt). 

[The Election Results](https://github.com/teachjanderson/Election_Analysis/blob/main/Resources/election_results.csv), in a CSV file, were analyzed using Python 3.76 and Vistual Studio Code 1.6

## Election-Audit Results

The results of the election and pertinent questions pertaining to the election are answered below. 

<p align="center">
<img src="https://github.com/teachjanderson/Election_Analysis/blob/main/Resources/OutputTerminal.png" width="600" />

**How many votes were cast in this congressional election?**
  
The election included 369,711 total votes split between three counties. Overall, Denver received the most votes with 82.8% or 306,055 votes. Jefferson followed after with 10.5% or 38,855 votes. Arapahoe received 6.7% or 24,801 votes. 
  
For the candidates, Diana DeGette won the election with 73.8% or 272,892 votes. Charles Casper Stockham came in second and received 23% or 85,213 votes. Raymon Anthony Doane received 3.1% or 11,606 votes. 

**Total Votes:**
369,711
  
**Breakdown by County**
1. Denver 82.8% (306, 055)
1. Jeferson 10.5% (38.855
1. Arapahoe 6.7% (24,801)
  
**Highest Voter Turnout:**
Denver with 306,055 votes

**Breakdown by Candidate**
1. Diana DeGette 73.8% (272,892)
1. Charles Casper Stockham 23.0% (85,213)
1. Raymon Anthony Doane 3.1% (11,606)
  
**Election Winner:**
Diane DeGette 73.8% of the votes or 272,892 total votes
  
## Election-Audit Summary
The script developed for this election audit is beneficial in future or alternative elections as it is easily modifiable. While the simplest use is similar elections, modification for the criteria can easily be made if the dataset provides more information. This might include demographical or specific geographic information about the voters. This could lend itself to finding patterns in the data that could increase voter turnout for future elections. As this dataset loads information from [The Election Results](https://github.com/teachjanderson/Election_Analysis/blob/main/Resources/election_results.csv) file, this is easily interchangeable with similar elections. While this election took place at the county level, state or federal elections could easily be changed. In the image below you can see the script is general and used for any candidate. this could include elections outside the realm of politics. 
  
<p align="center">
<img src="https://github.com/teachjanderson/Election_Analysis/blob/main/Resources/Script.png" />
  
Similar code exists to analyze the county level data. Adjustments could be made as these are simply variables in the data. As the data changes, these variables can still exist to analyze their new content and context. Please consider this script for use in future elections where it can be of benefit. 
