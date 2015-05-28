> Can you show me all the files in slash temp slash foo?

Let's say /foo is in the /tmp directory, then I would use `find /tmp/foo/*.*` and if I wanted everything I would use `*` without the `.*`


> What log files are in your log directory?

Depending on where your log directory will change things.  Let's say we're in the folder that also contains the /log. 

Then we type `find log/*.log` to bring up all files ending in "log"


>Run find in the class directory, 
pipe the output to pbcopy and create a gist with the content.  
Paste the Gist URL as a comment on this story.

So here is what I used

`find * -print | pbcopy`

This printed everything it was finding and copied it to the clipboard

Then I went to gist.github.com and pasted the contents. I then pasted that URL into the comments seciton of this story

NOTE:  FLYCUT did NOT make a record with `pbcopy`
