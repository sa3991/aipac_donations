# AIPAC'S influence on congressional elections
This is my submission for the Lede Program for Data Journalism's first assignment. 

I saw news stories that claimed the donations by the American Israel Public Affairs Committee political action committee determined the outcome of the Democratic primary congressional election between Westchester County Executive George Latimer and U.S. Rep. Jamaal Bowman to oust Bowman, who has been critical of Israel's war in Gaza.   

I wanted to analyze AIPAC's donations to see how much influence they had over the primary and how that has compared to how much the organization has donated to other candidates. 

I took data from the Federal Election Commission's campaign finance data. Data from both Latimer's campaign and AIPAC's dontaions was able to be exported directly from the website into a CSV file. 

I then used pandas, a Python library, to filter the data to only see this year's donations from political action committees and I removed duplicates from the data. I sorted the filtered data through pandas to produce a table of the candidates AIPAC had given the most money to. 

I used that table to create a graph in Data Wrapper and added details to the graph in Adobe Illustrator.  

My analysis showed that Latimer was the Democratic candidate that had recieved the most money from AIPAC this year and showed that the Democratic candidate who had recieved the second largest sum of donations from AIPAC was also challenging an incumbent candidate who was critical of Israel's actions in Gaza. 

The two datasets I used for the analysis can be downloaded here: 
[Link](https://www.fec.gov/data/receipts/?data_type=processed&contributor_name=C00797670&two_year_transaction_period=2024)
[Link](https://www.fec.gov/data/receipts/?data_type=processed&committee_id=C00859041&two_year_transaction_period=2024)

## What I learned
The main skill I got to practice in this project was analyzing data in pandas. The FEC data was challenging to sort, filter and organize because there was a lot of information in the datasets and some duplicates that I had to methodologically remove from the dataset. I learned how to create a sum of all the different receipts of donations for each candidate and I also learned how to filter data from a specific date. I also got to practice making basic graphs in Data Wrapper and editing them in Adobe Illustrator to make them clear to read. 

## Things I would have liked to do
I wanted to look at AIPAC donations from the last election cycle to create a more comprehensive comparison. Unfortunately, the FEC did not have data from AIPAC donations available from before 2021. 
