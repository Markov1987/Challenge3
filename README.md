# Challenge3 - Election Audit


## Project Overview
We received the following tasks to complete an election audit for a Colorado Board of Elections: 

1) Calculate the total number of votes. 
2) Get a complete list of candidates. 
3) Calculate the total number and percentage of votes received per candidate. 
4) Determine winner based on simple majority mechanism. 

Additionally, we performed a few additional computations directed to understand voters distribution among the counties:

1) Count vote turnout per county.
2) Identify the largest turnout. 


## Resources Used
To accurately perform the requested analysis we used  the election results basis provided by the Board (election_results.csv) and process the information with Python: 

![Data Source & Software](https://github.com/Markov1987/Challenge3/blob/d4aef6e6ebb7ce4e68be51922b4f24eea72e3370/Challenge%203/Resources/Data%20Source%20&%20Software.png)

## Results

### General
Total votes at the election added to almost 370 k, voters decided among 3 candidates: 

1) Charles Casper Stockham.
2) Diana DeGette.
3) Raymon Anthony Doana. 

After considering the basis of the total votes, distribution between candidates ended as follows: 

![Candidates Results](https://github.com/Markov1987/Challenge3/blob/d4aef6e6ebb7ce4e68be51922b4f24eea72e3370/Challenge%203/Resources/Candidates%20Results.png)

Thus, **Miss Diana DeGette won the election by getting over 70% of the total computed votes:**

![Winner](https://github.com/Markov1987/Challenge3/blob/d4aef6e6ebb7ce4e68be51922b4f24eea72e3370/Challenge%203/Resources/Winner.png)

### County
Per county votes analysis showed an **important concentration being Denver the largest county accounting for over 80% of the total turnout:**  

![Election Results](https://github.com/Markov1987/Challenge3/blob/d4aef6e6ebb7ce4e68be51922b4f24eea72e3370/Challenge%203/Resources/Election%20Results.png)

## Election Audit Summary

Dear Colorado Board of Elections: 

We want to thank you for the confidence to let us work on this project and make you feel sure the analysis was performed with the highest quality standards.

It is also important for you to know **the script we used for this analysis can be used again for future auditions** with the only requirement to remain some construction consistency in the analyzed base as follows: 

- Each row represents a unique voter and its vote decision.
- Column 1: Holds an identifier for each voter.
- Column 2: Holds a specific characteristic of interest for each voter. 
- Column 3: Holds an identifier of the vote.

As an example, instead of Ballot ID, Column 1 can contain Voter's Name or any other ID as long as is unique (the script does not check for duplicate entries). Similarly, the name of the candidates can be substituted by Name of the Party or any Identification Code of the votes and the script will work right.

Finally, note different analyses can be performed if the County of the voter is substituted per any other characteristic of interest as can be Range of Age, Gender, Religion, Race, or any other you want to use to split received votes against. 
