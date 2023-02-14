# Triples iOS Game Application
## Demo: https://youtu.be/KzzI8PRH8vI
The Triples iOS application is a game that follows similar logic to the game, Threes. It has two game modes: random and deterministic. The random mode will randomly initialize the starting locations of the four tiles, and the deterministic mode will always initialize the board the same way. In addition to the directional tap buttons on the screen, swipe gestures for indicating directional moves are recognized. The application also displays tile movement animations to demonstrate when the tiles change values. A tab for viewing a page that maintains the user's high scores using persistence is also included. The game can be played in both vertical and horizontal orientations as it adjusts the screen's layout when the orientation changes.

![Screen Recording 2022-07-03 at 3 17 02 AM (1)](https://user-images.githubusercontent.com/71235972/177029468-e4df055e-c301-4039-b9a5-70a9841301a9.gif)

### How do you play?

The game begins with 4 tiles populated (either randomly or in the same way if played in deterministic mode). The buttons specify the direction that the tiles should move. For example, if 'up' is pressed, all the tiles will move up one space. If they have no space left to move, they will remain where they are. However, if any two adjacent tiles are able to combine to sum to 3, 6, 12, 24, 48, 96... (i.e. 1+2=3, 3+3=6, 6+6=12), then they will collapse to that summed tile value. For each move, a random new tile gets spawned to any of the open tiles as either a '1' or '2'. This pattern continues until all the tiles on the board are full, and no tiles are able to combine resulting in no more possible moves...Game over. 

Please contact me if interested in viewing the Swift code.
