# Query-Domain-Classification
Query Domain Classification


Build a system to categorize the query on the basis of the domain using Natural Language Processing.



## Problem Statement

DSForum is a community-based portal where users can post queries related to data science topics such as machine learning, statistical analysis, data visualization, etc. The company optimizes the response time of the query by answering the query to the earliest. Nevertheless, the community can answer the queries through discussion forums. The queries might be related to different domains like Techniques, Tools, Careers, etc. 


Currently, the users manually tag the queries while posting the query into any of these categories: Techniques, Tools, Career, Hackathons, Resources, Misc, or Other. The query is then forwarded to the concerned team. This process is more error-prone and impacts the query response time. 


Can we design and develop a model that can accurately classify queries based on their domain? This will help the team to improve the response time of the platform by accurately identifying the domain of a query and redirecting it to the appropriate team and resolving the queries to the earliest. 



## Data Dictionary

You are provided with 3 files - train.csv, test.csv, and sample_submission.csv


## Train and Test Set

The train and test set contains the queries from different timespans. The train set includes the target variable ‘domain’ whereas in the test set, you need to predict the target variable ‘domain’. The target variable category contains multiple classes like  Techniques, Tools, Career, Hackathons, Resources, Misc, Other.



Variable

Description

ID

Unique identifier of the query

Title

Title of the query

Domain 

Domain of the query (Target Variable)




## Submission File Format

The solution file should follow a format similar to that of the sample submission file. sample_submission.csv contains 2 variables - ID and Domain.



Variable

Description

ID

Unique identifier of the query

Domain

Domain of the query




## Evaluation metric

The evaluation metric for this hackathon would be Macro F1 Score.



## Public and Private Split

Test data is further divided into Public (40%) and Private (60%) data. Your initial responses will be checked and scored on the Public data. The final rankings would be based on your private score which will be published once the competition is over.



## Submission Tutorials

All Submissions are to be done at the solution checker tab.
For a step-by-step view on how to make a submission check the below video






## Guidelines for Final Submission

Please ensure that your final submission includes the following:

Solution file containing the predictions for the ID in the test set (Format is given in sample_submission.csv)
A zipped file containing code & approach
Code: Clean code with comments on each part
Approach: Please share your approach to solve the problem (doc/ppt/pdf format). It should cover the following topics:
A brief on the approach used to solve the problem. 
Which Data-preprocessing / Feature Engineering ideas really worked? 
How does your final model look like? How did you reach it?


## Rules and Conditions

The final standings would be based on the private leaderboard score.
Setting the final submission is recommended. Without a final submission, the submission corresponding to the best public score will be taken as the final submission
Use of external data is not allowed.
The submitted code file must be able to reproduce a similar score to that of the final submission file.
The code file pertaining to your final submission is mandatory while setting final submission.
Entries submitted after the contest is closed, will not be considered
Throughout the hackathon, you are expected to respect fellow hackers and act with high integrity.
Use of multiple Login IDs will lead to immediate disqualification
Analytics Vidhya holds the right to disqualify any participant at any stage of the competition if the participant(s) are deemed to be acting fraudulently.
