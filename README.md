# Neon Pong Multiplayer

A two-player browser game that works across separate devices.

## Rules
- Player 1 creates a room and shares the 6-character code.
- Player 2 joins using that code.
- Player 1 controls the left paddle; Player 2 controls the right paddle.
- Use W/S or Up/Down arrows, or drag on the game board on touch devices.
- The ball bounces off paddles and the top/bottom walls.
- When the ball passes a paddle, the opponent scores.
- First player to 7 points wins.

## Multiplayer
The game uses PeerJS/WebRTC data connections. No game server is required; PeerJS provides the signaling service and the gameplay data travels peer-to-peer.

## Publish
This repository is intended to be served as a static GitHub Pages site. The entry point is `index.html`.
