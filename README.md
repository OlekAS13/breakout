# Breakout
Atari Breakout from 1976 in Python

## Features
* Breakout game
* Settings
  * Ball Rotation Mode
  * Left Wall Glitch
* Points counter

## About Breakout
Breakout is a game on which you need to break all the bricks on the screen to win. You control the bat with your mouse to hit a ball. There are 4 colors of bricks each with 2 rows so eight rows in total. The first two rows are yellow, they are worth 1 point. The next two are green, they are worth 3 points. The next one are orange, they are worth 5 points. And the last two rows are red, they are worth seven points. When hitting a ball with the bat the speed of it gets higher after first 4 hits then after another eight (so after first twelve) the speed gets little higher again. If you hit the orange or red bricks the speed is then highest no matter when you hit them (independent from hits with the bat). When the ball hits the top wall the paddle shrinks. When you clear the first eight rows the second eight appears and when you clear the second ones the game ends and you win. When you loose the ball six times you loose the game.

## Controls
* Mouse buttons - Start
* S - open settings menu
* ESC - close settings menu
* G - serve the ball
* D - show / hide debug variables
