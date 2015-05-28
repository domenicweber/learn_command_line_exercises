> Can you put "This class is fun" into bar.txt?

First make the file `touch bar.txt` then use the following

`echo 'This class is fun' > bar.txt`


> Can you put "Oh so much fun" into foo.txt?

Same process: `touch foo.txt`


`echo 'Oh so much fun' > foo.txt`


### Some comments

So I understand the > does something with the thing on the left to the thing on the right
Therefore < does something with the thing on the right to the thing on the left

For example: `cp cat13.txt cat15.txt` does the same as `cat ex13.txt > ex15.txt` 

In the first you are saying copy ex13.txt and call it ex15.txt

In the 2nd example you are saying "Print ex13.txt to ex15.txt"

If I used 2 >  that is to say `>>` then it appends the files together so I can type
cat ex13.txt >> ex15.txt it will add the stuff in ex13.txt to ex15.txt but not erase anything.

Pipe `|` always takes the output on left and "pipes" it into the command on the right. What I don't get is how this is differnt than just typing the command followed by the file.

