# **Election_Analysis**

## **Project Overview**
The project is to analysis the recent election results for the Colorado Board of Elections. The election audit would enable the board to examine the various results of the election process such as the total number of votes, list of candidates and the respective votes received along with the percentage votes obtained by each candidate I have used Python programming language for the quicker analysing of dataset provided by the Board in csv format. The report helps to quickly view at a glance the information regarding the winning candidate and the winning percentage votes.


## **Election-Audit Results**: 

- **Total Votes casted in the congressional election** - As per the dataset provided, there was a total of 369,711 votes casted. 

- **Breakdown of the number of votes and the percentage of total votes for each county in the precinct.** - The audit of the election results illustrates the outcomes for three counties – Jefferson, Denver and Arapahoe.

  - Jefferson County results: The vote count was 38,855 for the county, which constituted 10.5% of the total votes casted during the election.
  -  Denver County results: The vote count was 306,055 for the county, which constituted 82.8% of the total votes casted during the election. Denver county had the highest vote count among the three counties.
  - Arapahoe County results: The vote count was 24,801 for the county, which constituted 6.7%, the lowest vote count among the counties during the election.
  
  
- **Largest vote count county**- The county with the largest vote count was Denver, as they constituted 82.8% of the total votes casted. It shows that majority of the voters in the county voted this election for their preferred candidates. 

- **Breakdown of the number of votes and the percentage of the total votes each candidate received.**- As per the election data analysed, there were three candidates who stood for this election.
  -	*Charles Casper Stockham* :
      Vote Count - 85,213, Percentage of Vote - 23.0% 
  -	*Diana DeGette* : Vote Count - 272,892, Percentage of Vote - 73.8%
  - *Raymon Anthony Doane* : Vote Count - 11,606, Percentage of Vote - 3.1% 

- **Winning candidate’s vote details** - The winning candidate for the election was Diane DeGette. She won the majority with a vote count of 272,892, which was 73.8% of the total votes casted this election.

The outcome of the election result can be summarized by the below summary
<<screen shot of county results>>


## **Election-Audit Summary**: 

The current script enables the election commission to run results based on the election information quickly without any error and time consumption. The script also facilitates to summarize the large data in a simplified and easily understandable layout. The same script can be used with minor modifications for other elections based on election commission requirements or purpose. 


 - For instance, the same script can be used for various county elections by modifying the source data for running the report. The change would be done to identify or recognize the file pathway for the new election data frame. As a result, we would be able to get the desired election results without creating a new script from scratch. 
 
 *To change the data source for the analysis, we could just modify the below code specifying a new file*  
  **File_to_load = os.path.join (“Resources”,”election_results.csv”)**

 Another example, for using the same main script is for analysing the Statewide election. The election commission would need to change the code to read the state instead of county rows from the corresponding data source file which is preferred to be in csv format.
	
- To gather the information for the State-wise analysis, we could just modify the below code specifying the row with the information relating to the state. So, modification is done to the code to extract the state name from each row.

**County_name = row[1]** would be replaced with **State_name = row[1]**

 

- The parent script can also be used to analyse the data further based on the additional information available in the data source file. It can be used by the election commission to get more insight of the towns with the most voter participation, gender wise participation analysis of the election, mode of vote, etc.


## **Resources**
- Source Data: election_result.csv
- Software: Python & Visual Studio Code
