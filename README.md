# Bowling Scorecard 
Bowling Game (Makers Academy week5)

##What does this button do? 
It counts and sums the scores of a bowling game of one player (in Javascript).  

Screenshot:  

![Alt text](/ScoreCard.png?raw=true "ScoreCard")

##How to run
`git clone git@github.com:sandagolcea/bowling.git`  
`cd bowling`  

To run tests:  
`open SpecRunner`  

To see the scoreCard:  
`open views/index.html`  

##Bowling rules

A bowling game consists of 10 frames in which the player tries to knock down 10 pins. 
In every frame the player can throw one or two times (The actual number depends on strikes and spares).   
The score of a frame is the number of knocked down pins plus bonuses for strikes and spares. 
After every frame the 10 pins are reset.

#### Strikes

The player has a strike if he knocks down all 10 pins with the first roll in a frame. 
The frame ends immediately (since there are no pins left for a second roll). 
The bonus for that frame is the number of pins knocked down by the _next two rolls._ That is the next frame, except if the player rolls a strike again.

#### Spares

The player has a spare if he knocks down all 10 pins with the two roles of a frame. 
The bonus for that frame is the number of pins knocked down by the next roll (first role of next frame).

#### 10th frame

If the player rolls a strike or spare in the 10th frame he can roll the additional balls for the bonus. 
But he can never roll more than 3 balls in the 10th frame. 
The additional rolls only count for the bonus- not for the regular frame count.

10, 10, 10 in the 10th frame gives 30 points (10 points for the regular first strike and 20 points for the bonus)
1, 9, 10 in the 10th frame gives 20 points (10 points for the regular spare and 10 points for the bonus)
Gutter Game

A Gutter Game is when the player never hits a pin (20 zero scores).

#### Perfect Game

A Perfect Game is when the player rolls 12 strikes (10 regular strikes and 2 strikes for the bonus in the 10th frame). The Perfect Game scores to 300 points.


### Other Resources
* [Wikipedia Article](http://en.wikipedia.org/wiki/Ten-pin_bowling)
