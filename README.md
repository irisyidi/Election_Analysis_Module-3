# **Election_Analysis_Module-3**


## **Overview of Election Audit**

The objective of the election audit is to make sure that the election result is in align with results of the data collected from the mail-in ballots, punch cards, and direct recording electronic, or DRE, counting machines. Meanwhile results will be analyzed and verified by the total number of votes cast, the total number of votes for each candidate and each county, the percentage of votes for each candidate and each county, the winner of the election based on the popular vote and the county with the largest number of voters. By creating the automation process through python, the code can be used to other congressional districts and senatorial districts and local elections. 



## **Election-Audit Results**
**1. How many votes were cast in this congressional election?**

The number of votes cast in this congressional election is 369,711. 


**2. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.**

![County Votes](https://github.com/irisyidi/Election_Analysis_Module-3/blob/main/County%20Votes.png)

County Votes Screenshot from results of code

- In County Jefferson, the total votes are 38, 855 and cover 10.5% in the precinct.
- In County Denver, the total votes are 306,055 and attribute to 82.8% in the precinct. 
- In county Arapahoe, the total votes are 24,801 and contribute to 6.7% in the precinct. 

**3. Which county had the largest number of votes?**

County Denver had the largest number of votes 


**4. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.**

![Candidates Vote](https://github.com/irisyidi/Election_Analysis_Module-3/blob/main/Candidates%20Vote.png)

Candidates Votes Screenshot from results of code

- Charles Casper Stockham earned 85,213 votes, which contributed to 23% of total votes. 
- Diana DeGette received 272,892 votes, covering 73.8% of total votes. 
- Raymon Anthony Doane received 11,606 votes, attributing to 3.1% of total votes. 


**5. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?**

Diana DeGette won the election. The vote count is 272,892 and the percentage of the total votes is 73.8%. 



## **Election-Audit Summary**
![TerminalScreenshot](https://github.com/irisyidi/Election_Analysis_Module-3/blob/main/TerminalScreenshot.png)

Output from Terminal

![TextScreenshot](https://github.com/irisyidi/Election_Analysis_Module-3/blob/main/TextScreenshot.png)

Output from Text

By creating the automation process through python, the code can be used to the elections where the total votes, the number of votes received by each candidates anad the related percentage of support are suppposed to be calculated in the process. The common examples of the situation when the script can be used are congressional districts and senatorial districts and local elections. 

### **Example 1: Local Elections**

For the local elections, the votes information can be collected and transformed to a csv file with information of ID number, candidates name and county. The information needed are the winning candidates, winning count, winning percentage and each candidate’s votes, percentage, and name. Therefore, the code related to the county information such as creating the county list, calculating the total votes and the percentage in each county can be eliminated. 

### **Example 2:  Senatorial Districts

For the election of senatorial districts, the necessary data we need to collect is that ID number, candidates name and the party that candidates belong to. The report of the elections results should include winning candidates, winning count, winning percentage, winning party and each candidates' votes, percentage and party. Therefore, the code for counting for the votes that each party has received should be created. If statement and for statement can be used to get the list of parties and count the number of voters for each party. 
