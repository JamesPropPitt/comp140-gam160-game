# comp140-gam160-game
Repository for Assignment 1 of COMP140-GAM160

# Two and a half Dimensional Minesweeper
I plan to design and create a 2.5 dimensional take on the popular game _Minesweeper_.

## What my game is based off
The game will follow all of the original minesweeper gameplay mechanics and have a grid full of squares with two possible variants:

1. **A bomb** 

* Activating this tile will end the game with the player losing

* There will be no clear signs which indicate which tile is a bomb and which is not

* The player does not get multiple lives

2. **No bomb**

* Activating this tile will not end the game and the player will continue to play.

* If the tile activated is in proximity of a bomb it will display a number from 1 - 8.





The numbers displayed in the cell indicate how many bombs are in the surrounding area, typically in the original minesweeper it
scanned a 3x3 box and displayed all bombs. This can be used to deduce the location of bombs.





# Why my game is different to the original

My game takes all of what Minesweeper currently is and adds features to enhance it.

~~Players use the mouse to activate cells on the grid~~

### **Players now walk around the map filled with cells and press E when facing the block to activate it**




~~The game two dimensional~~

### **The game I am designing will be 2.5D**




~~The original gave the players a chance to plant flags so as to note down suspect cells~~

### **Players will now be given the ability to remove blocks they are unsure of**



_However in regards to the above feature the player will only be able to remove the amount of bombs placed on the map, e.g if
the map has 16 bombs the player can only remove 16 blocks so if the player realises he has made a mistake he can put a block back down_


# Controller Proposal
My general plan for the controller layout will be a list of the following: 
* 6 buttons
* 2 L.E.Ds (1 red, 1 green)
* Pringle tube

I plan to take a pringles can and slice it in half, cut 4 holes in a horizontal line across the tube and one bigger hole in the center with a slightly smaller hole directly next to it.
The four smaller holes will be used for movement and menu navigation, similar to the D-pad of current popular console controllers
(Xbox, PlayStation) and the bigger button will be used to select an object in game and in the menus. In game this big button will detonate the bomb whilst the slightly smaller button next to it will be used to remove clear blocks which the player has deciphered is safe to remove and does not contain a bomb.

This is my idea for a controller because I want my gameplay to be centered around not just locating the bombs but also exploding them with the 'bomb defusal' equipment. 
