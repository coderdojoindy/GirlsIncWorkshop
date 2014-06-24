# Repeating

Sometimes it is helpful to be able to repeat a set of instructions. This is called looping or iterating. Computers can use a loop that executes a series of instructions and then assks a question to see whether it should execute them again, or it can loop forever.  The question acts a lot like an if statement.  The loop asks the question if it's answer is YES or NO. if it is YES it tells the computer to go back to the first instruction in the loop.  If the answer is NO then it tells the computer to go to the first instruction AFTER the loop.

### Unplugged
We are going to make our mouse find food a little bit better.  Before in our example the mouse would only hide or look for food one time each time our program is run, but then our mouse was stuck in the open.  We want our mouse to keep searching for food until a cat comes, and then hide.
```
while the cat is not around
search for food
when the cat shows up, then hide.
```
![Diagram](https://raw.githubusercontent.com/coderdojoindy/GirlsIncWorkshop2014/master/images/repeating.png)
+ Setup
  + 1 computer
  + 1 expression
  + 1 loop.
  + 1 mouse
  + 2 instructions (search for food - same as prevous activity, and hide - same as previous activity)
+ Execution
  + the computer will ask the loop what instruction it should read next.
  + the loop will ask the expression if the cat is around.
  + the loop will tell the computer what set of instructions to execute.
  + the computer will execute the instructions.
  + the computer goes back to the loop until the loop tells it to go to the first instruction outside of the loop.
+ Repeat switching roles.

### Scratch
We're going to make the cat run across the screen until she hits the edge and then say OUCH!
+ add a green flag click event from events
+ attach a [repeat until] block from control
+ drag a [touching ___] block from sensing into the [repeat until] block's expression slot, select edge.
+ drag a [move 10 steps] block into the repeat until block
+ attach a [say "Hello!" for 2 seconds] after the repeat block, change "hello" to "Ouch!"
+ drag the cat to the left side of the stage, click the green flag.
