# Project Overview

This is a browser-based game where players use a paddle to keep a ball in play and break bricks arranged at the top of the canvas. The objective is to break all the bricks without letting the ball fall off the screen. As the game progresses, it becomes more challenging, requiring quick reflexes and precise control.

## Features

- **Canvas Drawing:** Elements such as the paddle, ball, and bricks are drawn on the HTML5 canvas using canvas paths and shapes.
- **Animation:** Smooth gameplay animation is achieved using `requestAnimationFrame(callback)`.
- **Paddle Control:** Use the left and right arrow keys to move the paddle and keep the ball in play.
- **Collision Detection:** Detect collisions between the ball and bricks, walls, and the paddle to keep the game dynamic and challenging.
- **Scoring System:** Earn points by breaking bricks. The game keeps track of your score as you play.
- **Rules Button with Slider:** A button to display the game rules, with a slider to control additional game settings.

## How to Play

1. **Start the Game:** Load the game in your browser and press the Start button to begin.
2. **Control the Paddle:** Use the left and right arrow keys to move the paddle horizontally.
3. **Break the Bricks:** Bounce the ball off the paddle to hit and break the bricks at the top of the canvas.
4. **Score Points:** Each broken brick increases your score.
5. **Win or Lose:** Break all the bricks to win the game. If the ball falls below the paddle, the game is over.

## Game Controls

- **Left Arrow Key:** Move the paddle left.
- **Right Arrow Key:** Move the paddle right.
- **Rules Button:** Click to view the game rules and adjust settings with the slider.

## Technologies Used

- HTML5
- CSS
- JavaScript
- HTML5 Canvas API

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/breakout-game.git
