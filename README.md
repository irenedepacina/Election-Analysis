# Election_Analysis

## Overview of the Project

### Purpose
The purpose of this analysis was to retrieve data for an election dataset in order make sense of the audit results. The election commission requested the following information:
- The total number of votes casted in the election.
- The voter turnout and the percentage of votes from each county out of the total votes.
- The county with the highest turnout.
- The names of the individual candidates in the election and the total number of votes each candidate won.
- The winner of the election based on total number of votes received and their percentage of their total vote.

Using Python, `for` loops and `conditional` statements with membership and logical operators were implemented to find the requested results. In addition, `print` statements were used to print out the candidate and county election results. The findings were saved to a text file entitled, "Elections Results," which presented the information in a clear and understandable manner. 

## Election-Audit Results
 - How many votes were cast in this congressional election?
    - The total number of votes was 369,711.
 - Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
    - The breakdown of the number of votes and the percentage of total votes for each county is as follows:
    - ![](https://github.com/irenedepacina/Election_Analysis/blob/main/Resources/County_results.png)
 - Which county had the largest number of votes?
    - **Denver** was the county with the largest number of votes with 306,055.
 - Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
    - The breakdown of the number of votes and percentage for each candidate is as follows:
    - ![](https://github.com/irenedepacina/Election_Analysis/blob/main/Resources/Candidates_results.png)
 - Which candidate won the election, what was their vote count, and what was their percentage of the total votes? 
    - The winner of the election was **Diana DeGette**. Her vote count and percentage of the total votes was 272,892 and 73.8% respectively.

## Elections-Audit Summary 
The PyPoll script serves the purpose for any election. It calculates the total number of votes in the election and adds the vote to the selected candidate. The script also breakdowns number of votes and percentages based on county and candidates. Therefore, this script can extend further and can be used for other elections.
 
Two ways the PyPoll script can be modified to be used for other elections:
1. Based on total number of votes and percentage of total votes, the program can rank the results from 1st, 2nd, 3rd and so on. A ranking system would be beneficial if the purpose of the election was to build a cabinet. The roles of the cabinet are filled based on the most and least number of votes. Therefore, the positions range from president, vice president, secretary, treasurer, etc. 
2. The election commission can use this script for a federal election. They would have to include the states or the provinces; depending on the country. The script can show the breakdown of each province, city, etc. This data would be beneficial for future elections. It would help get a better understanding on the popularity of certain political parties in a given area. That way politicans running for office know where they need to focus their campaigns to gain votes.
