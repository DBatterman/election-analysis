# Election Analysis
Using Python to analyze data from a local election

## Overview of Election Audit

The purpose of this audit was to break down analyze votes in a local Colorado election. By using this code, we get to see in depth what happened in this election. It will tell us the total number of votes, the votes breakdown in each county in the election, and how many votes each candidate got. This will then allow us to figure out which county had the most votes, and which candidate won the election.

## Election Audit Results

###### -How many votes were cast in this congressional election?

There were 369,711 votes cast in this election.

###### -Breakdown for the number of votes and percentage of total votes for each county in the precinct.

There were three counties represented in this data: Jefferson, Denver, and Arapahoe. Out of the 369,711 total votes, Jefferson County cast 38,855 which accounted for 10.5% of the total. Denver County cast 306,055 votes making up 82.8% of the votes cast. Lastly, Arapahoe county cast the remaining 24,801 votes to account for the final 6.7%. 

###### -Which county had the largest number of votes?

Denver county had the largest amount of votes. 

###### -Breakdown for the number of votes and percentage of total votes each candidate recieved.

Similarly to the number of counties, there were three candidates in this election: Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane. Charles recieved 85,213 votes for 23% of the total votes cast. Diana recieved a whopping 272,892 votes; good for 73.8% of all of the votes. The final candidate, Raymon, recieved the final 11,606 votes for the final 3.1%.

###### -Which candidate won the election, what was their vote count, and what was their percentage of total votes?

Diana Degette won the election. Diana recieved 272,892 votes, which was 73.8% of the total votes

## Election-Audit Summary

Although this script was used at a local level, it has much broader applications with some more tuning. With a few simple itterations, the same general framework can be used to analyze all sorts of different elections. For example, if we wanted to look at a national election, it would be very easy to add a "states" category and track those votes as well. You could also go more in depth with the analysis, and figure out which candidate performed the best in each area you want to filter for, whether that be county, state, or even country if we applied this to interational competitions.
