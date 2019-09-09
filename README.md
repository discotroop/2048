# 2048
2048 Clone built in vanilla JavaScript.

Version 1:
It needs to display a 4 x 4 grid
It needs to generate new tiles.
    New tiles need to equal 2 or 4
It needs to respond to key strokes.
    a. all tiles that can move key stroke direction need to.
    b. tiles that can add new to add.

To Do:
1. sketch out basic html layout and add css styling.
2. build tile container.
3. write js for tile(s) constructor
4. write getNewTile
5. figure out how to snap tiles to grid locations.
6. figure out how to transform/animate/move tiles to new locations. 
    probably gonna be arrays essentially.
7. write code to move tiles on key up.
 a. basically.
  on.keyUp, iterate through tile array(s), 
  
  if (tile.hasLegalMove === "true") {
     tile.move(legalMove);
 }

 move: function(legalMove) {

 }

 example board.
 arr1 = [0, 0, 0, 0];
 arr2 = [0, 2, 4, 0];
 arr3 = [0, 0, 0, 0];
 arr4 = [0, 2, 0, 0];

on up:
arr1[1] = 2;
arr1[2] = 4;
arr2[1] = 0;
arr2[2] = 0;
call new random tile.
render

on right: 
arr2[3] = 4;
arr2[2] = 2;
arr2[1] = 0;
call new random tile.
render.

on left:
arr2[0] = 2;
arr2[1] = 4;
arr2[2] = 0;
call new random tile.
render. 

 on down:
 arr2[1] = 0;
 arr4[1] = 4;
 arr4[2] = 4;
 call new random tile.
 render
