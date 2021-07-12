# Chess_Learning_Algorithm
I really enjoy chess and decided to build a project where I could enjoy that interest with my data science skills.
#I found this chess dataset on kaggle (found here: https://www.kaggle.com/datasnaek/chess) and decided to build a machine learning model to see how well it could predict the winner/outcome of matches. 
 
#After testing multiple models and running grid search on parameter combinations, I was able to produce a model with 84% accuracy.
#The data cleaning prior to modeling was by far my favorite part of this project. I had to work through some interesting methods to covert the data which made sense as chess code into information that could be interpreted by a model. 

#I also went over some visualizations of the data to look at some overall trends and get a better understanding of the data. 

![image](https://user-images.githubusercontent.com/82009362/125327922-4c585400-e309-11eb-8d2a-b051f445f3ba.png)

#I find a lot of use in histograms and like to use them as a visualization tool to look at the data is distributed. This visualization shows the distribution of player ratings, how common each time setting is, and even the amount of turns that most games finish with.

![image](https://user-images.githubusercontent.com/82009362/125331084-216fff00-e30d-11eb-8a68-ee06fcea991d.png)


#I thought it would be important to visualize and note that white pieces win more often than black pieces. This occurs since the player with the white pieces gets the first move and starts off with an advantage. This impacts players move choices and overall gameplans esspecially in tournaments. 

![image](https://user-images.githubusercontent.com/82009362/125328221-aeb15480-e309-11eb-864f-99e7b358a71b.png)
 
#I also found it useful to visualize how player rating was related to the amount of time spent in the opening phase of the game. For this visualization I plotted player ratings (Both white and black pieces) against the amount of moves spent during the opening. I foudn that players with lower ratings tended to spend less turns in the opening phases of the game. I think a potential cause of this is that the more experienced a player is (higher rated) the more likely they are to have memorized opening theory. Opening theory is sequences of moves in each opening that have the highest probability of producing a win (Also refered to as the most accurate move). When two players who but understand opening theory play, they both play the most accurate moves. This results in more moves played in the opening.
