# Election Analysis Project

## Overview of Election Audit
### Purpose
  The data analytics team met with Tom and Seth, both Colorado Board of Elections employees, to discuss the results for a recent US Congressional Precinct election. The Colorado Board of Elections team already obtained a final vote count report and would like to perform an audit on the results. The three methods to collecting ballots, included mail-in ballots, punch cards, and direct recording electronic or "DRE" ballots. Historically the team performed all the analysis in Excel, but decided this year to automate this process using Python programming language to ensure the results of each election are identified as fast and accurate as possible. The overall goals for the data analytics team include:

  1. *Write Python script to automate the election audit process*
  2. *Calculate the total number of votes cast*
  3. *Calculate the total number and percentage of votes for each county*
  4. *Identify the county with the largest turnout*
  5. *Calculate the total number and percentage of votes for each candidate*
  6. *Identify the winning candidate and their respective total and percentage of votes*
  7. *Provide to business proposals for how this script can be used for future elections*

## Election-Audit Results
### Python Script
Once the data analytics team was provided a task list, the team developed Python script to automate the election audit. Below are the major psuedocoding steps the data analytics team had to perform to automate this process:

1. **Import "csv" and "os" dependencies**: This allows us to view the file [election_results.csv](https://github.com/Sborresch/election_analysis/blob/main/Resources/election_results.csv) that is the final vote count report and join our files using the teams Microsoft operating system **(see appendix A)**.
2. **Initialize variables**: incuding our total_votes counter, lists (candidate_options and county_options), dictionaries (candidate_votes and county_votes), and our winning candidate/county variables **(see appendix B)**.
3. **Set for candidate loop**: To add candidate_names to candidate_options and track candidate votes **(see appendix C)**.
4. **Repeat step 3 for county loop**: **(see appendix D)**.
5. **Set for loop to calculate winning county**: Calculates the total count and percentage for each county **(see appendix E)**.
6. **Repeat step 5 for winning candidate**: Calculates the total count and percentage for each candidate **(see appendix F)**.


### Results
Below is an image the results of the Colorado congressional election
- How many votes were cast in this congressional election?
  - There was a total of 369,711 totoal votes for this congressional election
- Provide a breakdown of the number of votes and percentage of total votes for each county in the precinct.
- Which county had the largest number of votes?
- Provide a breakdown of the number of votes and the percentage of total votes each candidate received.
- Which candidate won the election, what was their vote count, and what was their pecentage of total votes?

## Election-Audit Summary
### Business Proposal
### Example One
### Example Two

## Appendix A
![Screenshot](https://github.com/Sborresch/election_analysis/blob/main/Appendix%20A.png)

## Appendix B
![Screenshot](https://github.com/Sborresch/election_analysis/blob/main/Appendix%20B.png)

## Appendix C
![Screenshot](https://github.com/Sborresch/election_analysis/blob/main/Appendix%20C.png)

## Appendix D
![Screenshot](https://github.com/Sborresch/election_analysis/blob/main/Appendix%20D.png)

## Appendix E
![Screenshot](https://github.com/Sborresch/election_analysis/blob/main/Appendix%20E.png)

## Appendix F
![Screenshot](https://github.com/Sborresch/election_analysis/blob/main/Appendix%20F.png)
