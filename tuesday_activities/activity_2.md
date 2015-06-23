# Decisions

Having the computer execute a series of instructions is great, but it isn't very useful, the computer will do the same thing over and over and over and over every time you run it.  You can have your program do different things based on the answer to a question.  This is done with an **IF** statement.  An **IF** statement looks at a question that can be answered with Yes or No and then tells the computer which line of instructions to start executing next.

### Unplugged
This time we are going to be a mouse, mice are very afraid of cats, if they sense a cat 
they run back to their holes. This time we need 1 computer, 1 if else statement, 1 question 
or "expression" that has an answer of yes or no, 1 mouse and 2 instructions.

```
if the cat is around then mouse runs and hides.
else then mouse searches for food.
tell the mouse to squeak.
```
![Diagram](https://raw.githubusercontent.com/coderdojoindy/GirlsIncWorkshop2014/master/images/if_else.png)
+ Setup
  + designate a "mouse hole" spot on the floor. 
  + need 1 "computer" (the first time through the volunteer should be the computer)
  + need 1 "expression"
  + need 1 "mouse"
  + need 3 "instructions", "run and hide", "find food", "squeak"
  + Create one shoulder to shoulder line with the expression and the squeak instruction.
    The girs with yes and no cards should be standing in two lines behind the expression.
+ Execution
  + the mouse needs to be in an open spot, the hide instruction makes the 
    mouse go back to her hole which will just be another designated spot on the floor, find food instruction
    will cause the mouse to turn right, take 2 steps and then walk in a circle.
  + the computer will ask the expression her question "is the cat around?"
  + if the instruction answers yes, then the computer goes to the girl holding the "yes" card. otherwise she goes to the girl holding the no card.
  + the computer will read that instruction and make the mouse do the action.
  + then the computer will go to the next instruction after the if expression.
+ Repeat by switching roles, choose different people for the expression, mouse and instructions.

### Scratch

+ add a green flag clicked event.
+ drag out an if - else block from control
+ drag a > block from operators into the if statement expression container
+ drag a [x position of sprite 1] block from sensing into the left side of the [>].
+ change the right side of the [>] to be 0
+ drag a [move 10 steps] block to the inside of the if clause, change 10 to -10
+ drag a [say] block to just below the move block in the if clause make it say "to the left!"
+ drag a [move 10 steps] block to the inside of the else clause.
+ drag a [say] block to just below the move block in the else clause make it say "to the right!"

