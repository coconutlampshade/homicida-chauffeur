write the README.md file here
# Homicidal Chauffeur Problem Simulation

This is an interactive simulation of the "Hamstrung Squad Car" game, a variant of the classic Homicidal Chauffeur problem in game theory. The game demonstrates a pursuit-evasion scenario where a squad car (pursuer) tries to catch a crook (evader) on a grid.

## Game Rules

- The squad car (blue) moves twice as fast but can only move forward or turn right
- The crook (red) moves slower but can go in any direction
- The game is played on a 50x50 grid
- Players take turns moving their vehicles
- The squad car wins if it catches the crook (moves to the same or adjacent cell)

## Controls

- **Squad Car:**
  - Move forward: Arrow key or WASD key in the direction you're facing
  - Turn right: Arrow key or WASD key 90° clockwise from current direction
- **Crook:**
  - Move in any direction using Arrow keys or WASD

## Features

- Auto-play options for both vehicles
- Visual indicators for valid moves
- Directional indicator for squad car
- Turn-based gameplay
- Responsive design that works on different screen sizes

## Play Online

You can play the game directly in your browser: [Play Homicidal Chauffeur](https://coconutlampshade.github.io/homicidal-chauffeur/driver.html)

## Background

This simulation is based on a classic problem in differential game theory, where a fast but constrained pursuer tries to catch a slower but more maneuverable evader. The original problem was introduced by Rufus Isaacs in his work on differential games.

## Credits

Inspired by an article from [The Magnet](https://themagnet.substack.com/).

## License

MIT License