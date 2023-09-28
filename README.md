# Steam_Video_Game_Data_Analysis

<p align="center">
  <img src="https://github.com/xuqc01/Steam_Video_Game_Data_Analysis/assets/38637431/faada5c4-376e-47c2-bff5-e7b06ee4784d" width="500" height="500">
</p>

## Introduction

The objective of this study is to determine the most popular style or genre of Steam's video games. Popularity is gauged by considering either the genre's playerbase, measured by the number of active players, or the sheer volume of games associated with that genre. The ultimate aim of this project is to streamline the game development process by identifying a genre which eliminates one of the crucial steps in creating a successful video game.

## Game Distribution Analysis
A vast majority of Steam games have less than 100 active players. On the other hand, the games Counter-Strike 2, Team Fortress 2, and Dota 2 have over 100,000 concurrent players because of its competitive nature; they require multiple players to compete with one another. Games that require multiple players will always remain on top of the playerbase hierarchy. However, this does not mean that games without the multiplayer trait will have no playerbase. Other factors such as the lack of advertisement, substandard player feedback, or simply poor game development can result in a small playerbase and vise versa. Unfortunately, many of these games, approximately 60,000 of the 90,000 Steam games, have 0 active players. 

![image](https://github.com/xuqc01/Steam_Video_Game_Data_Analysis/assets/38637431/83955cf9-06af-466f-af5f-2a49ffe18d5b)

## Tag-Game_Count Analysis
The top 5 tags were determined with a simple linear regression model which calculated a best fit line for the change in number of released games per tag from the years 2006 to 2022. The tags with the largest slope (greatest increase in number of games) were displayed in the graph below. As seen, the tags (genres) Indie, Casual, Action, Adventure, and 2D were the most grossing produced style of games. The tags 'Singleplayer' and 'Multiplayer' were removed from the pool of tags because these two tags are nearly associated with all Steam games.

![image](https://github.com/xuqc01/Steam_Video_Game_Data_Analysis/assets/38637431/2a318444-ffc5-45be-bcec-e0e29849d8ca)

## Tag_playerbase Analysis
The 5 video games genre by average player count in descending order are action, indie, adventure, simulation, and strategy. This is expected because the genre of games that were created the most in the recent years were also indie and action. 

<p align="center">
  <img src="https://github.com/xuqc01/Steam_Video_Game_Data_Analysis/assets/38637431/c670bc5a-b8f0-49ea-b88f-8da2bddf60d8">
</p>


## Tag_price Analysis
As seen below, the cost of games have gradually increased from $10 to $25. This can be due to various economical reasons or simply the overall improvement in quality of Steam games. The price of the Indie and Casual tag have one of the lowest prices in the present day which is logical because they are primarily created by independent game developers or small indie game studios.

![image](https://github.com/xuqc01/Steam_Video_Game_Data_Analysis/assets/38637431/9d5eb74d-4b90-4a8e-93e0-da5361a70f93)


## Conclusion
Game developers should create indie, action, or strategical-styled games or a mixture because of their consistent rise in popularity in both playerbase and the shear number of games created. However, it's important to consider external factors besides the genre that would also increase the game's playerbase such as advertising, optimal price points, release time, and especially player feedback from alpha and beta tests. The price point for a typical indie game should be in the range of $15 to $20 as indicated in the price analysis of video game genres over the years. With one obstacle out of the way, you will be one step closer in creating a popular Steam game.
