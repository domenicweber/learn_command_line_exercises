## Do More

####UPDATE2

> Move a file in newplace to somewhere else and back

Type `mv place1/foo.txt place2/` and you'll move the foo.txt file inside the /place1 directory into the /place2 directory.

## Questions

> Can you rename foo.txt to blah.txt?

`mv foo.txt blah.txt` changes the name but technically what you are doing is creating a new file with a different name 
and deleting the old one and then you are moving the contents of the file

> Can you move the production.log file in the log directory to the slash temp dir?

Yes, from the /tmp/log directory I used `touch production.log` to make the file.  
Then I used `mv production.log /tmp` and checked in the /tmp directory with `ls` it worked.



####Update2
> Can you zero out that file


All that being said I moved the production.log file from /tmp/log to just /tmp

`mv /tmp/log/production.log /tmp` Then I ran `echo '' > production.log` making the file 1 byte
