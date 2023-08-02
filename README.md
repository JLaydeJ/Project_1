![image](https://github.com/JLaydeJ/Project_1/assets/134284646/89f1495e-c91b-4c7b-9467-d260c0593ab7)
# Washington Powerball/Powerplay Lottery
Team Members: Erika Evergarden '2020', Jamee Jones '2021', Evan Woodard '2022'

# Project Description
“How can you best play the lottery?”

That question has two components:
1. What numbers can you pick to help your odds?
2. When can you play to win the most money?

To answer these questions, we looked for the most often drawn numbers and the highest dollar winnings, both filtered by day and by month. The goal of this project is to determine the frequency of the powerball/powerplay to increase our odds of maximizing our payout. 
 
# Data Source
The data source is from Kaggle https://www.kaggle.com/datasets/stetsondone/lottery-data-winning-numbers-and-jackpots as an aggregate .csv. This CSV file covers past lottery data in Washington State from June 2014 - November 2022. The original source was pulled from Lottery Corner - https://www.lotterycorner.com/wa/powerball/2022. 
This file includes the following data: 

date - date of winnings

weekday - day of week winnings were announced

winning numbers - string of winning numbers for jackpot

powerball - Winning powerball number; If your Powerball matches the one that is drawn you will get your $2 ticket purchase back and a couple of bucks more, for a total of $4.

powerplay - Winning powerplay number - for an additional $1 per play, the powerplay feature multiplies non-jackpot prizes. The multiplier number is randomly selected just before each drawing.

jackpot - total jackpot amount in USD

# Prepare the Data
We reduced our original CSV file from the years 2014 - 2022 to 2020 - 2022. We then sliced the CSV file into 3 separate CSV files for the years 2020, 2021, and 2022. Using Pandas, we were able to import the data, and then merge the combined year DataFrames into a single DataFrame. After merging the Dataframes, we will then use the data to solve our exploratory questions. 

# Exploratory Question 2020 - 20222
1. What were the most common powerball/powerplay numbers depending on the day?
2. What were the most common powerball/powerplay numbers depending on the month?
3. What were the most common powerball/powerplay numbers overall?
4. What are the top five greatest dollar months jackpot?
5. Which day of the week had the highest jackpot? 





# Summary Statistics
Null hypothesis: There is no better or worse way to play the lottery.
Alternative hypothesis: There is a projectable difference in outcomes based on the numbers you choose, the time of year, and the day of the week you play. 

# Resources
