The window screen was the first thing to be created 
The title of the game is Dead snake game 
The background color is yellow 
The code has two turtle objects which are head and food 
The width and height is 400 and the head is used to control the snake and food is used as the game's object 
The head is triangular and it's color is white 
The food stores information about the shapes and colors of the food that will be displayed on the screen and the shape and color functions are used to create different types of food with three colors and three shapes and a set speed
There is the function called goto() that takes two arguments: position(in pixels) and direction (which can be "up" "down" "right" "left"). The goTo() uses these values to move the object to a specific location onscreen and set its properties
The code creates three variables: head,wn and godown. the head stores information about the player's position on the screen (xcor and ycor), wn is a listening object that tracks keyboard input.
Godown stores information about where the player should go next (left,right,up and down) and there ae certain keys to listen to which are (w,s,a,d)
If anything changes, the code updates itself accordingly and there's also a timer set to 0.1 seconds 
