# Activity 1

We're going to learn that the cat follows our directions exactly.

### Blocks for this activity:
* motion - `turn left [] degrees`: ![turn_left](https://s3.amazonaws.com/scratch-blocks/motion_turn_left.png)
* motion - `turn right [] degrees`: ![turn_right](https://s3.amazonaws.com/scratch-blocks/motion_turn_right.png)
* motion - `move [] steps`: ![move_steps](https://s3.amazonaws.com/scratch-blocks/motion_move_steps.png)

### Instructions
Add a series of `move [] steps`, `turn left [] degrees`, and `turn right [] degrees` instructions to a sprite in Scratch:
- Experiment with changing the number of steps you move.
- What happens if you increase the number of degrees you turn right or left?
- Can you make the cat go straight up and and then back to where you started?
- Can you make the cat go straight left or right and then back to where you started?
- Can draw a square?
 
# Activity 2

We are going to learn about decisions (`if` blocks) and a little bit about sensing
our environment. In this activity the cat will desperately want to get to the middle
of the screen along the x or side to side axis.

### Blocks for this activity:
* events - `green flag clicked`: ![flag_clicked](https://s3.amazonaws.com/scratch-blocks/events_flag_clicked.png)
* control - `if else`: ![if_else](https://s3.amazonaws.com/scratch-blocks/control_if_else.png)
* operators - `greater than`: ![gt](https://s3.amazonaws.com/scratch-blocks/operators_gt.png)
* motion - `x position`: ![x position](https://s3.amazonaws.com/scratch-blocks/motion_x_position.png)
* motion - `move [] steps`: ![move_steps](https://s3.amazonaws.com/scratch-blocks/motion_move_steps.png)
* looks - `say []`: ![say](https://s3.amazonaws.com/scratch-blocks/looks_say.png)

### Instructions: 
+ add a `green flag clicked` event. 
+ drag out an `if else` block.
+ drag a `greater than` block into the `if else` expression.
+ drag a `x position` block from sensing onto the left expression of the `greater than` block.
+ click on the right expression of the `greater than` block and type `0`.
+ drag a `move [] steps` block in between the if and the else in the `if else` block.
+ click on the `move [] steps` expression and change it from `10` to `-10`.
+ drag a `say` block to just below the `move steps` block inside the `if`.
+ click on the `say` expression and change it to `to the left!`
+ drag a `move [] steps` block to the inside of the `else`, it should say `move [10] steps`
+ drag a `say []` block to just below the `move steps` block in the `else`. 
+ make the `say []` block say `to the right!`
  - what happens when you click the green flag once?
  - what happens when you click the green flag over and over?
  - try dragging the cat to different places on the screen and clicking the green flag,
    what happens then?

#### Finished Script:
![script](https://raw.githubusercontent.com/coderdojoindy/GirlsIncWorkshop2014/master/images/d2_a2.png)

# Activity 3

We're going to make the cat run across the screen until she hits the edge and then say OUCH!

### Blocks for this activity:
 * events - `green flag clicked`: ![flag_clicked](https://s3.amazonaws.com/scratch-blocks/events_flag_clicked.png)
 * control - `repeat until <>`: ![repeat_until](https://s3.amazonaws.com/scratch-blocks/control_repeat_until.png)
 * sensing - `touching []`: ![touching](https://s3.amazonaws.com/scratch-blocks/sensing_touching.png)
 * motion - `move [] steps`: ![move_steps](https://s3.amazonaws.com/scratch-blocks/motion_move_steps.png)
 * looks - `say [] for [] seconds`: ![say_for](https://s3.amazonaws.com/scratch-blocks/looks_say_for.png)

### Instructions:
+ add a `green flag click` block.
+ attach a `repeat until <>` block.
+ drag a `touching []` block into the `repeat until <>` block's expression slot.
+ click the drop down arrow in the `touching []` block's expression, select "edge".
+ drag a `move [] steps` block into the repeat until block
+ attach a `say [] for [] seconds` after the repeat block.
+ click on the first expression in the `say [] for [] seconds` block and make it say "Ouch!"
+ drag the cat to the left side of the stage, click the green flag.
  - what happens?

#### Finished Script:
![script](https://raw.githubusercontent.com/coderdojoindy/GirlsIncWorkshop2014/master/images/d2_a3.png)

# Activity 4

This program will make the cat run back and forth until you click on the cat 10 times.
Each time you click on the cat the clickCount variable has 1 added to it.

### Blocks for this activity:
- events - `green flag clicked`: ![flag_clicked](https://s3.amazonaws.com/scratch-blocks/events_flag_clicked.png)
- control - `repeat until <>`: ![repeat_until](https://s3.amazonaws.com/scratch-blocks/control_repeat_until.png)
- operators - `equals`: ![eq](https://s3.amazonaws.com/scratch-blocks/operators_eq.png)
- data - `make variable`: ![make_var](https://s3.amazonaws.com/scratch-blocks/data_make_var.png)
- motion - `move [] steps`: ![move_steps](https://s3.amazonaws.com/scratch-blocks/motion_move_steps.png)
- motion - `if on edge, bounce`: ![if_edge_bounce](https://s3.amazonaws.com/scratch-blocks/motion_if_edge_bounce.png)
- events - `when this sprite clicked`: ![this_sprite_clicked](https://s3.amazonaws.com/scratch-blocks/events_this_sprite_clicked.png)
- data - `var`: ![var](https://s3.amazonaws.com/scratch-blocks/data_var.png)
- data - `change [] by []`: ![change_var](https://s3.amazonaws.com/scratch-blocks/data_change_var.png)

### Instructions:
+ `make a variable` called clickCount (under data section)
+ add a `green flag click` block.
+ attach a `repeat until <>` block to green flag event.
+ drag a `equals` block to the `repeat until <>` expression (equality operator)
+ drag your clickCount `variable` to the left side of the `equals` operator.
+ enter 10 on the right side of the equality operator.
+ add a `move [] steps` block inside the `repeat until <>` block
+ attach a `if on edge, bounce` block from motion to the `move [] steps` block
+ add a `when this sprite clicked` event.
+ attach a `change [] by []` block to the `when this sprite clicked` event.
+ make sure `change [] by []` has clickCount selected in the first expression (drop down)
  - What happens when you run the program by clicking the green flag, click on the sprite until it stops, and then click on the green flag again?
  - What happens if you keep clicking on the sprite?
  - How might you fix the things you found?

#### Finished Script:
![script](https://raw.githubusercontent.com/coderdojoindy/GirlsIncWorkshop2014/master/images/d2_a4.png)