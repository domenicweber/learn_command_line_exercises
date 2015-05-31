> Can you touch blah.txt?

In my chapter_9 directory I typed `touch blah.txt` and voila, a new text file is there when I type `ls`


> Let's create foo.txt.

In the same chapter_9 directory I typed `touch foo.txt` and wouldn't you know it the same thing happened again.

> Touch an existing file


####Update

If you run `touch <filename>` and the file already exists you will update
the file with a new time stamp.  I would not consider this an overwrite as it doesn't change anything inside the file

##Do More

> Unix: Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.

It's not really an error in the "bash" sense.  I made a directory called goaway and put a built a file using `touch nooo.txt` and it built the file.
I then backed out and tried `rmdir goaway` and it says "Directory not empty"

