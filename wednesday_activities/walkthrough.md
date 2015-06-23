### Goal
Create a game where you collect some objects that fall from the sky and avoid others

### Create a main character
1. Select an existing sprite to use as your main character
2. Name the main character
3. Create a script that makes the sprite follow your mouse left/right across the screen.
![control](https://s3.amazonaws.com/scratch-blocks/control.png)![motion](https://s3.amazonaws.com/scratch-blocks/motion.png)![sensing](https://s3.amazonaws.com/scratch-blocks/sensing.png)
4. Run this script when the flag is clicked. ![events](https://s3.amazonaws.com/scratch-blocks/events.png)

### Create a falling object
1. Select another existing sprite to use as the (good) falling object, give it a name.
2. Drag the sprite to the top of the screen
3. Create a script that moves the sprite to the bottom of the screen. ![motion](https://s3.amazonaws.com/scratch-blocks/motion.png)
  - Make it fall straight down no matter where you start
5. Make it move to the top and fall again when it hits the bottom. ![sensing](https://s3.amazonaws.com/scratch-blocks/sensing.png)![motion](https://s3.amazonaws.com/scratch-blocks/motion.png)
6. Hide the object when it hits the bottom and show it when you move it to the top. ![looks](https://s3.amazonaws.com/scratch-blocks/looks.png)
7. Run this script when the flag is clicked. ![events](https://s3.amazonaws.com/scratch-blocks/events.png)

### Create a score
1. Create a score variable
2. When the falling object touches the main character, hide it and add 10 to the score
3. Reset the score to 0 when the flag is clicked

### Create another (bad) falling object
1. Click on your good object sprite
2. Open the backpack (drawer on the bottom of your screen)
3. Drag the two scripts into your backpack. This will make them available later.
4. Select an existing sprite to use as your bad falling object
5. Drag the two scripts from your backpack into this sprite's scripts
6. Drag the sprite to the top left

### Create a lives variable
1. Create a lives variable
2. Change the script in your bad object to subtract a life instead of add 10 to the score
3. Reset lives to 3 when the flag is clicked

### Create a game over screen
1. In the stage area, create a new backdrop for when the game is over
2. When lives is 0, change the backdrop to your game over screen
3. Also stop all scripts
4. Reset the backdrop when the flag is clicked

### Move the falling objects around
1. Instead of falling from the top left/right, have the sprite change where it starts (hint: random)

### Make lots of falling objects
1. Learn what a clone in scratch is
2. In your 2 falling objects change out the when flag clicked and forever blocks
for when I start as clone
3. After the object hits the bottom, delete it
4. In the stage area, create a forever loop that creates clones of the good object
5. After it creates the clone, have it wait
6. Try waiting .5, .75, 1, and 2 to see what feels right
7. Redo steps 4-6 for the bad object
