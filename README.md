
# Project-1: NBA Player Game Performance vs MVP Votes

# Team 6: Let's Go Nuggets
## Team Members: Bobby Chang, Kevin Downes, Eliezer Flores, Bhagya Prasad

# Project Scope:
Based on the player's regular season's performance data, which factor affects the MVP(Most Value Player) votes. 
## Research Questions to Answer:
### How to value a player’s individual performance
### How to value player’s impact on team results
## Datasets to Be Used: https://api-sports.io/documentation/nba/v2#section/Introduction
  
# GitHub repository summary: 
Url location: https://github.com/kebb-pseg/project-1
1. Project 1 Final-checkpoint.ipynb (Jupyter Notebook file)
2. api_keys.py (the file contains the key to use in API calls, no key contains inside the file. just for reference)
3. Team6-RutgersProject01-Deck.pptx (Presentation slides)
4. README.md (Project information)

# Code Logistics
1.  Due to the API usage restriction (100 calls per day), we pick top 4 MVP candidates (player Id:20, 279, 159, 124) to query the 2021 regular season's player's performance statistics
2.  player20DF, player279DF, player159DF, player124DF dataframe is used for data discovery.
4.  mvp_votes_df: MVP votes dataframe from data source: https://ak-static.cms.nba.com/wp-content/uploads/sites/46/2021/06/2020-21-NBA-MVP-Voting-Results-Announcement.pdf
5.  statistics_df dataframe: the final dataframe is used to generate analysis graphic 
6.   

