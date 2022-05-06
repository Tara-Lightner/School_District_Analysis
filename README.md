# School District Analysis

## Overview of School District Analysis

## Mastery Skills demonstrated
This project demonstrates mastery of Python Pandas through: 
- Open Jupyter Notebook files from local directories using a development environment.
- Read an external CSV file into a DataFrame.
- Format a DataFrame column.
- Determine data types of row values in a DataFrame.
- Retrieve data from specific columns of a DataFrame.
- Merge, filter, slice, and sort a DataFrame.
- Apply the groupby() function to a DataFrame.
- Use multiple methods to perform a function on a DataFrame., 
- Perform mathematical calculations on columns of a DataFrame or Series.

- Creating and Activating a Development Environment
- Working with Jupyter Notebook and Pandas
- Converting CSV Files to Pandas DataFrame
- Exploring and Cleaning the Data
- Generating a School District Summary
- Generating a School Summary
- Sort to find the High and Low Performing schools
- Create a new DataFrame from an exsisting DataFrame by:
 - Creating a series by filtering the metaDataFrame
 -  Using groupby function to filter by column
 - Applying the mean() ????? functionORmethod to a column
    - get the average math and for each school
    - get the average reading scores for each school



## Background/ Application for Use
The Chief Data Scientist for PyCity Schools District is in charge of preparing all state-standardized test data for analysis for reporting to help share performance trends and patterns.  These data insights are shared with the school baord and superintendent for decision making at the school level and district level.  The client has reached out for help in the areas of student funding and student standarized test performance to aid in the decision making for school budget and priorities.  This project demonstates my work in aggregating the data and showcasing trends in school performance.

Unfortunetly, after I submitted the analysis the school board sent notice that the files showed academic dishonesty for Thomas High School 9th grade students in math and reading.  As state-testing standards must be upheld the associated student scores should not be calculated into the performance reporting, but must still be reflected in the count for funding consideration.  Therefore, the client is asking for the reports to be run, to look at the extent in which the academic dishonesty affected the reporting and to provide addiquite reporting that reflect state-testing standards to make adequte decisions.

## Deliverables
### Deliverable 1: Replace ninth-grade reading and math scores
* In[7] and In [10]
### Deliverable 2: Repeat the school district analysis
school_data_complete_df
* Image of the original District Summary DataFrame
* Image of the original Thomas High School Budget Data Frame
* Image of the updated District Summary DataFrame
* Image of the updated Thomas High School Budget Data Frame
* 
Per_school_summary
* Image of original per_school_summary_df
* Image of orignial THS_school_summary
* Image of updated per_school_summary_df
* Image of updated THS_school_summary
* Image of High and Low Performing Schools (X2)
* Image of Math and Reading Scores by Grade (X2)
* Image of Scores by School Spending
* Image of Scores by School Size
* Image of Scores by School Type

### Deliverable 3: A written report for the school district analysis (README.md)

- Election Results Printed from Command Line (Git Bash)
![Election Results through command line: this file can be found in Election_Analysis/analysis/Deliverable_1_Election_Results_Command Line.PNG](https://github.com/Tara-Lightner/Election_Analysis/blob/main/analysis/Deliverable_1_Election_Results_Command%20Line.PNG)
- Election Results Saved to a Text File (election_analysis.txt)
![Election Results saved as a text file: this file can be found in Election_Analysis/analysis/Deliverable_2_Election_Results_Text_File.PNG](https://github.com/Tara-Lightner/Election_Analysis/blob/main/analysis/Deliverable_2_Election_Results_Text_File.PNG)
- This Written Analysis of the Election Audit

## Conclusion
### Results: Election Outcome Analysis
- How is the district summary affected?
- How is the school summary affected?
- How does replacing the ninth graders’ math and reading scores affect Thomas 
- High School’s performance relative to the other schools?
- How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
- Scores by school spending
- Scores by school size
- Scores by school type


How many votes were cast in this congressional election?
- 369,711 district votes were cast for this congressional election.
What was the breakdown of the number of votes and the percentage of total votes for each county in the precinct; which county had the largest number of votes?
- **County Makeup: Vote Count & Percentage of Total**
  - *<u>**Denver**, with the largest county turnout, </u> cast a county total of 306,055 making up 82.8% of the total district votes.
   - **Jefferson** cast a county total of 38,885 votes making up 10.5% of the total votes cast 
   - **Arapahoe** cast a county total of 24,801 votes making up 6.7% of the total district votes.
Provide a breakdown of the number of votes and the percentage of the total votes each candidate received; Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
- **Candidate Summary: Percentage and Count**
  - <u>**Diana DeGette**, election winner</u>, receiving 73.8% of total votes, consisting of 272,892 votes
  - **Charles Casper Stockham** received 23.0% of total votes, made up of 85,213 votes
  - **Raymon Anthony Doane** received 3.1% of total votes, made up of 11,606 votes

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

### Challenges and Difficulties Encountered
There were many challenges and lessons learned along the way.  One of my biggest frustrations was trying to run my code inside VSCode using the play button vs. trying to launch it from the command line.  I had to change my file path code back and forth to get it to run using the play button because it was launching from a folder at a higher level and not from where my python script was located. I thought I had to make it work for both deliverables to get the assignment done correctly.  I even tried using a direct path, but this did not resolve it.  I think the error was that I had my VSCode opened from my MSU folder which is the overarching folder I have all my boot camp work in.  
####
#### Another issue that I had was in deciding to use the provided code from the challenge_starter_code or to get the output to format both the Print Statement and the election analysis txt the same way.  Below is the image of the formatting for the results requirements:
![Required Print Statement Output Solution](https://github.com/Tara-Lightner/Election_Analysis/blob/main/analysis/Module3_Requirement_Challenge_election_results_Print_Statement.png)
vs. The Required Output for the Election Analysis Text File: 
![Required Text File Output with different formating](https://github.com/Tara-Lightner/Election_Analysis/blob/main/analysis/Module3_Requirement_Challenge_election_results_txt_Results.png)
####
#### In general, the lack of continuity was bothersome in the reporting.  Why would there be a title for County Votes, but not for Candidate Results? Additionally, why would one section be single-lined and the other double-lined.   The largest count is titled about the county section, yet the winner is below the candidate section.  It is redundant to print the same specs for the winning candidate twice.  The space could have been used better.



