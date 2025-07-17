# Breakout
Atari Breakout from 1976 in Python

## Features
* Breakout game
* Settings
* Points counter
* Lost balls counter

## About Breakout
Breakout is a game in which you need to break all the bricks on the screen to win. You control the paddle with your mouse to hit a ball. There are 4 colors of bricks each with 2 rows so eight rows in total. The first two rows are yellow, they are worth 1 point. The next two are green, they are worth 3 points. The next ones are orange, they are worth 5 points. And the last two rows are red, they are worth seven points. When hitting a ball with the paddle the speed of the ball gets higher after first 4 hits then after another eight (so after first twelve) the speed gets little higher again. If you hit the orange or red bricks the speed is then highest no matter when you hit them (independent from hits with the paddle). When the ball hits the top wall the paddle shrinks. When you clear the first eight rows the second eight appears and when you clear the second ones the game ends and you win. When you loose the ball five times you loose the game.

## Controls
* Mouse buttons - start, serve the ball
* S - open settings menu
* ESC - close settings menu
* G - serve the ball
* D - show / hide debug variables

## Settings
* Ball rotation mode - choose which rotation mode you want to play with.
    * Dynamic - the closer the ball's center is to the center of the paddle the straighter the angle will be
    * Static - if you hit the ball with the same half of the paddle that the ball is coming from it will get reflected back by 180 degrees but if ball hits the other half it will get reflected by 90 degrees
* Left wall glitch - choose if you want to play with the left wall clippable like in the original Breakout or if you want to play with instant colissions instead.
    * On - the glitch is on and the ball will clip through the wall and reflect when it hits it left edge
    * Off - the glitch is off and the ball will reflect instantly when it touches the wall

## Settings controls
* B - toggles the Ball rotation mode setting
* L - toggles the Left wall glitch setting
* I - gives you infinite lives

<br>
<br>

---
I hope that you will enjoy this game. The game was made in three days. Shoutout to my older Breakout and other arcade Games on Scratch. Have Fun!
