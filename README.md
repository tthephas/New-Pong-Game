# Pong-game
Recreation of the famous game Pong

**Overview**

Pong is a table tennis type game, where a player is trying to hit or save the ball from going past their side (or end of the table as in table tennis). The player controls a "paddle" or in this case, a rectangular block, by moving it back and forth across the screen. The ball is moving around the screen and the object of the game is for the player to keep the ball from passing their paddle/block. They achieve this by positioning the block under the ball, and moving it to the next location of the ball. They can compete against the computer or another player (bonus feature). The goal will be for the player to reach 10 points/hits to move onto the next round. 

Round 1 will start off "easy" and subsequent rounds will get more difficult. Extra difficulty can occur in a few ways. 
  1) The player's paddle will get smaller
  2) The ball will move faster
  3) There could be more balls added (bonus feature)


**User Stories**

I want to be able to ...
  - Move quickly from left to right
  - Be reasonably able to get past round 1 and to subsequent rounds
  - The ball to be moving at a reasonable speed
  - The playing field to be visually appealing
  - My score to be clear
  - Clearly see when i win (move up levels) or lose
  - Clearly see the differences between levels
  - Use my keyboard OR mouse to play (bonus feature)
  - Restart whenever i want to 
  - Have a pause between clicking restart and the ball moving (maybe even a countdown)
  - Be able to see a computer paddle (bonus feature)
  - Keep track of my high score (bonus feature)

**Screenshots**

### Game play 
![Screenshot 2022-12-22 at 4 28 23 PM](https://user-images.githubusercontent.com/47870092/209236385-b183e761-10d9-4339-8cd3-f534f9705db7.png)


![Screenshot 2022-12-22 at 4 33 23 PM](https://user-images.githubusercontent.com/47870092/209236895-9038c6eb-334d-4faf-80d9-ac98c78c5ad9.png)


### Start Screen

![Screenshot 2022-12-22 at 4 40 08 PM](https://user-images.githubusercontent.com/47870092/209237524-5161782a-4f0f-4e0c-9851-997d7b2129c0.png)

### Game over screen

![Screenshot 2022-12-22 at 4 47 23 PM](https://user-images.githubusercontent.com/47870092/209238272-854d6b2e-b13e-4573-bea9-936c949a0e6b.png)


### Level, score, lives left (bonus feature)

![Screenshot 2022-12-22 at 4 51 38 PM](https://user-images.githubusercontent.com/47870092/209238689-a37a4993-7f82-44d2-a501-df22251bb54b.png)

### Alternative scoreboard position

<img width="751" alt="Screenshot 2022-12-22 at 7 34 17 PM" src="https://user-images.githubusercontent.com/47870092/209253457-5391721c-c95e-41c2-997a-324ee3bea3c0.png">

### Ball speed, paddle size, extra ball (bonus feature)

![Screenshot 2022-12-22 at 4 56 28 PM](https://user-images.githubusercontent.com/47870092/209239080-9749613f-8d77-4d39-92f2-bf02009c8ee6.png)

**Technical Requirements**

- Javascript
  -   Canvas tags
- HTML
- CSS


**Approaches taken**
- Build out game board with space for the game play, scoreboard, message board (HTML)
- Build out CSS styling for visual appeal. Make sure ball and paddle are clear for User Experience
- Use Javascript to control gameplay, scoreboard changes, screen changes for starting and ending screens
- Make ball bounce visually realistic although edges might not seem to touch paddles 
- *Possible Bonus features*
-   Create a level board for user to see what game changes happen when difficulty increases
-   Create different bouncing features, possibly random, to simulate real bouncing or erratic bouncing for difficulty increases
-   Create a local scoring system so user can track their all time scores and high scores
-   Create a real computer player at top of screen that increases in difficulty to beat (a second paddle)



