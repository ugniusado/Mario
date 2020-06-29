# Mario

First level of 2D Mario game, done with Unity

## v1.0


1. Fixed small code errors (Bracket '}' missing in function Update())

2. Added a Rigibody 2D to the Player

3. Assigned 'player transform' to Player


## v2.0

Used tilemap to fill the missing parts such as(Window>2D>TilePallete):

1. Ground

2. Pipes

3. Stairs

https://prnt.sc/t75bcg

## v3.0

Probably most chalenging one and most time consuming part of the task.

1. Firstly needed to update and create a new script for QuestionBlocks.cs, into InvisibleQuestionBlocks.cs

2. Deleted the QuestionBlock script of the invisible block and replaced it with InvisibleQuestionBlocks.cs, added prefab of the coin

3. Added colidder to trigger, when player hits the block.

4. Removed sprite rendering from the invisible block.

## v4.0 (v5.0)

I tried makin the UI, which I succeeded

1. modified the code (ScoreManager.cs)

2. Added TextMeshPro UI

3. Generated Mario font asset, so the font would be usable with TextMeshPro

4. Adjusted the canvas position in the game

## v5.0 (v4.0)

Did not succeed creating goal pole using Timeline, could not find the way to connect the Recorded Timeline with the actual game

Although Mario did things he was supposed to do slide down the Pole and walk around the Castle, i did not succeed conecting the game and the clip track


I tried phisically moving mario down the pole and around the castle using animation track and after I did not do it successfully I gave up on the fireworks animation aswell


P.S. Also I did not fix the Mario moving animation, he was just rolling around, i did not even tried to make it right because the task was not asking for it
