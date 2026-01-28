# Hex Game

A web-based implementation of the classic Hex board game with AI opponent.

## Goals

- Provide a fully playable Hex game in the browser with no dependencies or build process
- Support both 2-player local mode and 1-player mode against AI
- Implement an intelligent AI using pathfinding, virtual connections, and minimax with alpha-beta pruning
- Create a responsive UI that works across desktop and mobile devices

## Tech Stack

- Pure HTML5, CSS3, and vanilla JavaScript (single-file architecture)
- SVG for hexagonal board rendering
- No external dependencies

## Game Rules

- 11x11 hexagonal grid
- Red connects top to bottom, Blue connects left to right
- Players alternate placing stones on empty hexes
- First to create an unbroken chain wins

## AI Features

- Virtual connection (bridge) detection and defense
- Dual-distance pathfinding with resistance calculation
- Minimax search with alpha-beta pruning (3-ply depth)
- Strategic evaluation including threat detection and critical cell analysis
