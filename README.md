# Chess-Data-Analysis-and-Visualization
If you take a look at a graph showing how many chess players have each rating, it would look like a bell curve, which is the shape of a normal distribution. This matches up with data from Lichess, a popular chess platform, where the meadian and mean player ratings are both around 1500.

![image](https://github.com/irinkesh/Chess-Data-Analysis-and-Visualization/assets/159822614/9278d30e-de08-4e1e-bf02-e0791397f279)

Analyzing the average number of moves to finish a game (focusing on the "eating racket" scenario) reveals a fascinating trend: games tend to last longer as player ratings increase. This can be explained by several factors:
1. Stronger players are more likely to shepherd the game into an endgame, where strategic planning and precise calculations reign supreme.
2. Experienced players are less susceptible to surprises in the opening, meaning they can react calmly and develop a solid position.
3. Lower-rated games are more prone to blunders, where a critical mistake can swing the game in one move, leading to quicker finishes.



Once we've cleaned and finalized the chess dataset, let's delve into how frequently specific opening moves appear at each player rating level.
![image](https://github.com/irinkesh/Chess-Data-Analysis-and-Visualization/assets/159822614/b29ff1d7-c28e-4432-9b43-c2e44fef51f4)

This heatmap visually represents the popularity of chess openings at different rating levels. Darker squares indicate openings played more frequently within that specific rating bracket.



As we all know that White player has first move advantage in chess. Let's see how significant impact of this advantage and whether it fluctuates across different player skill levels.
![image](https://github.com/irinkesh/Chess-Data-Analysis-and-Visualization/assets/159822614/bdefdc36-6666-4b88-861f-ed04ce9a0929)
* As we move towards the higher rating side the tendency remains clear:" White player has a sight advantage".
* At the very top level (2300+ rating), it seems Black might actually win more! But there might be a reason for this: there are fewer games played at this level, so the data might not be super accurate.
* As we move up the traning bracket as players get better (higher ratings), there are more and more games that end in a tie (draw).



![image](https://github.com/irinkesh/Chess-Data-Analysis-and-Visualization/assets/159822614/b493a375-912f-478d-b2ca-9192338685e2)
![image](https://github.com/irinkesh/Chess-Data-Analysis-and-Visualization/assets/159822614/8ea2bac1-d6cc-4fd3-8944-403fa25f81f9)
![image](https://github.com/irinkesh/Chess-Data-Analysis-and-Visualization/assets/159822614/b66c728c-d196-4eb4-a9ab-89b7e7914e8d)
