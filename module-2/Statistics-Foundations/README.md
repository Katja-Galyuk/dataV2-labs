![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Statistics Foundations
In this lab we are going to put into practice what we learned about the foundations of statistics. You won't need to use Python, just your brain and a little bit of *Markdown*. 

## Your task
Today you'll need to complete the challenges described below.


## Challenges

### Challenge 1

One player rolls two dices. Describe the measurable space and the random variable for:

A. The values that the player obtains. Ω1 = {1, 2, 3, 4, 5, 6}. Ω2 = {1, 2, 3, 4, 5, 6}.
B. The sum of the values obtained. Ωsum = {2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12}.
C. The maximum value obtained after rolling both dices. 12
Describe the following events:

Case A: Both values are greater than 5. 2 / 6 * 2 / 6 = 4 / 36 = 2 / 18
Case B: The sum of values is even. 3 / 6 * 3 / 6 = 9 / 36 = 3 / 12 = 1 / 4
Case C: The maximum is the value of both rolls. 1 / 36


                                       ***
### Challenge 2


One player picks two cards from a poker deck. Describe the measurable space and the random variable for:

A. The number of figures he picks. Measurable Space - The Full deck Random Variable - 0, 1 or 2 figures

B. The sum of card values. Consider that the value of figures is 10 and the value of aces is 15. Measurable Space - The Full deck Random Variable - Can be any value between 4 and 30.

C. The number of hearts or spades he picks. Measurable Space - The Full deck Random Variable - Can be 0, 1 or 2

Describe the following events:

Case A: The number of figures in the cards the player picked is two.
Case B: The sum of card values is 17.
Case C: The value of both cards is less than 8.

                                         

### Challenge 3

Two players roll a dice. Describe the measurable space and the random variable for:

A. The score of player A. Measurable Space - Any Value between 2 and 12 Random Variable - The score A

B. The greatest score. Measurable Space - Any Value between 2 and 12 Random Variable - Score A and Score B

C. The earnings of player A if the game rules state that:
"The player with the greatest score gets a coin from the other player.". Measurable space - Any Value between 2 and 12 Random Variable - Win (+1) or Lose (-1)

D. The earnings of player A if the game rules state that:
"The player with the greatest score gets as many coins as the difference between the score of player A and player B.". Measurable space - Any Value between 2 and 12 Random Variable - Can be any value between 0 and 5

Describe the following events:

Case A: The score of player A is 2 » {(2,1),(2,2),(2,3),(2,4),(2,5),(2,6)}
Case B: The greatest score is lower or equal than 2. {(1,1),(2,1),(2,2),(1,2)}
Case C: Considering the case where the winner gets as many coins as the difference between scores (D), describe:
Player A wins at least 4 coins. {(5,1),(6,1),(6,2)}
Player A loses more than 2 coins. {(1,4),(1,5),(1,6),(2,5),(2,6),(3,6)}
Player A neither wins nor loses coins. {(1,1),(2,2),(3,3),(4,4),(5,5),(6,6)}



## Bonus challenges
### Bonus Challenge 1
Three players take balls from a box. Inside that box there are red, blue, green and black balls. The players can take three balls at mosts with the following rules:

* If the ball is blue, they can take another ball.
* If the ball is green, they get one point and they can take another ball.
* If the ball is red, they can’t take another ball.
* If the ball is black, they lose one point and they can’t take another ball.

Describe the measurable space and the random variable for:
* A. Player A wins. Do not consider ties as a win.
* B. Player A and B get the same points.
* C. All players get 0 points.

### Bonus Challenge 2
Consider the situation of bonus challenge 1 but now with four players. Does anything change in your solutions? What are the changes in each case?

### Bonus Challenge 3
One player takes three balls from a box. Inside the box there are 5 balls: two of them are black and the other three are white. 

Describe the measurable space and the random variable for:
* A. The number of white balls if every time we take a ball we keep it.
* B. The number of white balls if every time we take a ball we put it back again into the box.
* C. The number of black balls if every time we take a ball we keep it.
* D. The number of black balls if every time we take a ball we put it back into the box.