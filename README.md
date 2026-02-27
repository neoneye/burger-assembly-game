# Burger Assembly

A retro Commodore 64-style burger assembly game built as a single HTML file with vanilla JavaScript and Canvas.

![Burger Assembly](burger-assembly-game.gif)

## Gameplay

Catch falling ingredients on your plate in the correct order to assemble burgers. Each burger starts with a bottom bun, has a randomized set of middle ingredients (patty, cheese, lettuce, tomato, onion), and finishes with a top bun.

- Catch the right ingredient to build your burger and earn points
- Catching the wrong ingredient costs a life
- Build combos by catching consecutive correct ingredients for bonus points
- Complete burgers to advance through levels with increasing difficulty (faster drops, more ingredients)
- 3 lives per game, high score saved locally

## Controls

- **Arrow keys / A,D** - Move plate left/right
- **Mouse** - Move plate toward cursor
- **Touch** - Mobile touch support
- **Space / Enter / Click** - Start game, continue after game over
- **M** - Toggle music

## Features

- C64 color palette and 4x5 pixel bitmap font
- Pixel art ingredients drawn programmatically
- SID-style 3-channel music engine with three songs (title, gameplay, game over)
- Sound effects for catching, dropping, completing burgers, and more
- Animated chef character that reacts to your performance
- Scanline overlay and border effects
- Particle effects on catches and completions

## Running

Open `index.html` in a browser. No build step or dependencies required.
