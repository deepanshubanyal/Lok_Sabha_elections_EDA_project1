# Lok_Sabha_elections_EDA_project
# Step 1 Data Cleaning

In 2014, Andhra Pradesh underwent bifurcation. For simplicity, all constituencies
from that year should be attributed to Telangana state. This includes constituencies
such as Adilabad, Hyderabad, Warangal, etc., which should be considered part of
Telangana rather than Andhra Pradesh for the year 2014.



# Step 2 Data transformation

Establish suitable dimension tables and primary keys to link the CSV files
effectively.

Construct aggregate tables using append and groupby functions as needed to
format the data appropriately to answer the queries.

# Step 3 EDA

Questions from the available data

1. List the top 5 / bottom 5 constituencies of 2014 and 2019 in terms of voter turnout
ratio.
2. List the top 5 / bottom 5 states of 2014 and 2019 in terms of voter turnout ratio.
3. Which constituencies have elected the same party for two consecutive elections,
rank them by % of votes to that winning party in 2019
4. Which constituencies have voted for different parties in two elections (list top 1 0
based on the difference (2019-2014) in winner vote percentage in the two elections)
5. Top 5 candidates based on margin difference with runners in 2014 and 2019.
6. % Split of votes of parties between 2014 vs 2019 at the national level
7. % Split of votes of parties between 2014 and 2019 at the state level.
8. List the top 5 constituencies for two major national parties where they have gained vote
share in 2019 as compared to 2014.
9. List the top 5 constituencies for two major national parties where they have lost vote
share in 2019 as compared to 2014.
10. Which constituency has voted the most for NOTA?
11. Which constituencies have elected candidates whose party has less than 10% vote
share at the state level in 2019?
12. Is there a correlation between postal votes % and voter turnout %?
