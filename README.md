# Election_Analysis
## Overview of the Election Audit
My company was hired to assist the Colorado Board of Elections with an audit of their recent election in one of their Congressionsal precint. Our audit deliverable will be a vount count summary report which will certify the final elections results across all 3 of the primary voting methods (mail-in, punch cards, and DRE).
Our company will also deliver the python script that was used to complete the audit and create the audit summary report.
## Elections Audit Results
The results of the Elections Audit are as follows:
![alt text](https://github.com/ericajackson8/Election_Analysis/blob/main/analysis/Elections_Results.png?raw=false)
- The total Votes cast across all three counties Jefferson, Denver, Arapahoe)  and by all voting methods (Mail-In, Piunch Card, DRE) is 369,711.
- The distribution of votes cast by county is Jefferson, 10.5% or 38,855; Denver 82.8% or 306,055; and, Arapahoe 6.7% or 24,801.
- Denver County had the largest voter turnout; accounty for approx 83% of the Voters or 306,055 votes cast.
- The distribution of votes cast by candidate is Charles Casper Stockham, 23% or 85,213 votes; Diana DeGette, 73.8% or 272,892 votes; and, Raymon Anthony Doane, 3.1% or 11,606 votes.Diana DeGette received 73.8% of the vost cast, or 272,892 votes.

Based on the results of a thorough audit, our company certifies that Diana DeGette is the popular majority winner of this Congessional seat.

## Election Audit Summary
The Pypoll.py script that was delivered as part of this electon audit, can be used with every election to audit and summarize the election results.  Currently, the summary will provide total votes cast, total votes cast by ccounty, and by candidate for all voting modalities.  You will be able to identify the county with the largest voter turnout, and the candidate with the most votes.  You could also utilize this in other precincts.
Future modifications to this cript could include
1. Modifying the script to count the number of votes for each candidate, within each county.This would be usefult o see if there were certain counties that favored one candidate ofver the other.  
2. If given the dataset that included the voting method for each vote cast, that could also be included as another dimension to summarize.

