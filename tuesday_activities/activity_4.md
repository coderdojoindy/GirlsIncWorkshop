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
+ Setup
  + 1 computer
  + 1 expression (is the cat around?)
  + 1 loop
  + 1 mouse
  + 1 variable (searchCount)
  + 3 instructions (search for food, increment searchCount, shoutSearchCount
+ Execution
  + the computer will do the loop things it did from the previous activity.
  + the searchCount variable has two jobs, when the computer asks what number it contains,
    the searchCount variable will tell it to the computer. When the computer SETS the searchCount
    variable the searchCount just has to remember that number and can forget any previous number.
  + the twist is we'll add an incrementCount action which will read the searchCount, 
    add 1 to it and set that value back to the searchCount variable.
  + the shoutSearchCount instruction will read the searchCount variable and shout the 
    "the mouse searched .... times" inserting the searchCoutn into that sentence.
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
