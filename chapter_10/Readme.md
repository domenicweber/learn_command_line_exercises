> Can you copy the foo.txt file to slash temp?  (Create foo.txt first...)

So I literally created this file in the chapter_10/tmp diretory then used `cp foo.txt /tmp` and this copied it to my /tmp directory on the root as I just checked at it's there.

> Can you copy .bash_profile in your home directory to the current directory?

This took a bit from the home directory I typed in this:

`cp .bash_profile workspace/davinci_coders_t2_2015/homework/learn_command_line_exercises/chapter_10/tmp/`

I then went into the ../chapter_10/tmp directory and used `ls -al .*` and .bash_profile is in there, so it worked!

> What is Robocopy

It copies the contents of a file not just the name.  As this command only works in Windows, I'm not sure why I'm even asked this.

## Do More

> Use the cp -r command to copy more directories with files in them.

I built a direcory called "oldplace". I built a bunch of files in /newplace then used `cp -r newplace oldplace ` and all the files in /newplace were then generated in /oldplace

> Copy a file to your home directory

While in the /oldplace directory I copied the grom.txt file to the home directory by typing:

`cp grom.txt ~`

And then checked the home directory with `ls ~` for the file and yes, it is there.


> Find these files in your graphical user interface and open them in a text editor.

Um, yea, they are empty so there is nothing in them.  

However .bash_profile looks like this

>
[[ -s "$HOME/.profile" ]] && source "$HOME/.profile" # Load the default .profile
>
[[ -s "$HOME/.rvm/scripts/rvm" ]] && source "$HOME/.rvm/scripts/rvm" # Load RVM into a shell session *as a function*

