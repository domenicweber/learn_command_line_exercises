## Do More

> Move a file in newplace to somewhere else and back

In the /newplace directory `touch mover.txt`  

Back up: `cd ..` then type `mv newplace a_different_place`

`ls -R` shows /a_different_place/ is now the directory with mover.txt inside of it.

`mv a_different_place newplace` moves the file back from /a_different_place to /newplace

I understand that moving a file is technically creating a new version of it, then deleting the old, 
I don't understand the logic behind `mv` because technically to move a file means the directory would remain
and  `mv` literally deletes the old direcotry and builds a new one in it's place. 
To move a file it seems `cp file.txt <directory where I want file>` is more akin to moving a file than mv

## Questions

> Can you rename foo.txt to blah.txt?

`mv foo.txt blah.txt` changes the name but technically what you are doing is creating a new file with a different name 
and deleting the old one and then you are moving the contents of the file

> Can you move the production.log file in the log directory to the slash temp dir?

Yes, from the /tmp/log directory I used `touch production.log` to make the file.  
Then I used `mv production.log /tmp` and checked in the /tmp directory with `ls` it worked.



> Can you zero out that file

This one is still confusing me, I understand it belongs in the CP chapter but nonethless.

I tried what Jason suggested in Slack but I have no clue what this /dev/null/ has anything to do with the production.log file I made

This is copy/paste

> cp /dev/null log/production.log log/production.log

> usage: cp [-R [-H | -L | -P]] [-fi | -n] [-apvX] source_file target_file

>       cp [-R [-H | -L | -P]] [-fi | -n] [-apvX] source_file ... target_directory

All that being said I moved the production.log file from /tmp/log to just /tmp

Then I ran `echo '' > production.log` making the file 1 byte
