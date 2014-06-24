# Variables

Variables are a way to keep track of information in your program. For example, while
running a game there may be a variable storing the name of the current user, the score,
the number of lives, and the current level. You can do a couple of things with variables: 
read from them (what is the value) and set them (replace the value with a new value).

### Unplugged
We are going to build on our mouse foraging program. This time we are going to count 
the number of food searches a mouse does before the cat shows up. Instead of the mouse
hiding at the end of the loop, our program will execute an instruction that shouts the
value of the searchCount variable.
```
while the cat is not around, search for food, add 1 to the search count.
when the cat shows up, then hide, shout searchCount.
```
![Diagram](https://raw.githubusercontent.com/coderdojoindy/GirlsIncWorkshop2014/master/images/variables.png)
+ Setup
  + 1 computer
  + 1 expression
  + 1 mouse
  + 5 instructions: search for food, hide, squeak, add 1 to searchCount, and shout searchCount
  + Create one shoulder to shoulder line with the expression, the hide instruction and the squeak instruction.
    The girls with the search for food card should stand in line behind the expression.
+ Execution
  + the computer will ask the expression her question "is the cat around?"
  + if the answer is no, then the computer goes to the girl with the NO card. 
    starting with the no card instruction, do every instruction in the line and then go back to the expression.
  + if the answer is yes, go to the gir with the YES card the rest of the instructions in the should to shoulder line
+ Repeat switching roles.

### Scratch
This program will make the cat run back and forth until you click on the cat 10 times.
Each time you click on the cat the clickCount variable has 1 added to it.
+ make a variable called clickCount (under data section)
+ add a green flag click event.
+ add a [repeat until] block to green flag event.
+ add a [ _ = _ ] operator block to the until expression (equality operator)
+ add your clickCount variable to the left side of the equality operator.
+ enter 10 on the right side of the equality operator.
+ add a [move 10 steps] block from motion inside the [repeat until] block
+ add a [if on edge bounce] block from motion below the [move 10 steps] block
+ add a [when this sprite clicked] event from events.
+ add a [change clickCount by 1] block from data to the [when sprite clicked] event.
