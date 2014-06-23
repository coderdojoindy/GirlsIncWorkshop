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
![Diagram](https://raw.githubusercontent.com/coderdojoindy/GirlsIncWorkshop2014/master/images/if_else_activity.png)
+ Setup
  + designate a "mouse hole" spot on the floor. 
  + need 1 "computer"
  + need 1 "if-else statement"
  + need 1 "expression"
  + need 1 "mouse"
  + need 3 "instructions", "run and hide", "find food", "squeak"
+ Execution
  + the mouse needs to be in an open spot, the hide instruction makes the 
    mouse go back to her hole which will just be another designated spot on the floor, find food instruction
    will cause the mouse to turn right, take 2 steps and then walk in a circle.
  + the computer will ask the if statement which instruction is next.
  + the if statement will ask the expression "is there a cat here?" (expression will answer yes or no, her choice).
  + the if statement will tell the computer the appropriate next instruction to go to based on the expressions answer.
  + the computer will read that instruction and make the mouse do the action.
+ Repeat by switching roles, choose a new expression, if-else statement, mouse and instructions.

### Scratch

+ add a green flag clicked event.
+ drag out an if - else block from control
+ drag a > block from operators into the if statement expression container
+ drag a [x position of sprite 1] block from sensing into the left side of the [>].
+ drag a [move 10 steps] block to the inside of the if clause, change 10 to -10
+ drag a [say] block to just below the move block in the if clause make it say "to the left!"
+ drag a [move 10 steps] block to the inside of the else clause.
+ drag a [say] block to just below the move block in the else clause make it say "to the right!"


```
change notes:
activity 2:
the hide instruction will hold the if computer
the search for food instruction will hold the else sign
get rid of the if person.
expression is still in play.
first time through volunteer should be the computer.
the "question" should tell the computer Yes -> go talk to the if person. or No -> go talk to the else person.
add a new statement after the if/else that makes the mouse squeak.
```
