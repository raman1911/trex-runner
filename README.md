# T-Rex Runner

A simple browser game built with p5.js and p5.play.

## Overview

This repository contains a clone of the classic T-Rex Runner game. The player controls a running T-Rex that must jump over obstacles while the score increases over time.

## Files

- `index.html` - Main HTML file that loads the game.
- `sketch.js` - Game logic, including spawning obstacles, clouds, scoring, and game states.
- `style.css` - Basic page styling for the canvas.
- `p5.js` - p5.js library.
- `p5.play.js` - p5.play extension for sprite and group support.
- `p5.dom.min.js` - p5 DOM helper library.
- `p5.sound.min.js` - p5 sound library.
- Image assets (not listed in the repo tree) such as `trex1.png`, `trex3.png`, `trex4.png`, `trex_collided.png`, `ground2.png`, `cloud.png`, `obstacle1.png` through `obstacle6.png`, `gameOver.png`, and `restart.png`.

## How to Run

1. Open `index.html` in a web browser.
2. The game should start automatically.

## Controls

- `SPACE`: Jump
- Click the restart button after a game over to play again.

## Gameplay

- The T-Rex runs automatically.
- Avoid obstacles by jumping over them.
- Your score increases as long as you keep running.
- The game ends when the T-Rex collides with an obstacle.

## Notes

- The game uses simple physics for jumping and gravity.
- Obstacle speed increases slightly as the score rises.
