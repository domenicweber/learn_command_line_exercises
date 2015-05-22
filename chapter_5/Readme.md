> Do More #1 cd to the joe directory with one command.

`cd workspace/davinci_coders_t2_2015/homework/learn_command_line_exercises/chapter_4/temp/stuff/things/frank/joe`


> Do More #2 cd back to temp with one command, but not further above that.

`cd ../../../..`

> Do More #3 Find out how to cd to your "home directory" with one command.

To get to the home directory from anywhere use `cd` all by it's lonesome

> Do More #4 cd to your Documents directory, then find it with your GUI file browser (Finder, Windows Explorer, etc.).

`cd` gets me to 'thoth' then `ls` shows me the directories inside thoth and OH Look!!! there is 'documents' so then we `cd documents`
Open finder and under favorites find 'thoth' then find and open 'documents'

> Do More #5 cd to your Downloads directory, then find it with your file browser.

`cd` then `ls` then `cd downloads`.  Open Finder and click 'Thoth' under favorites and file the folder named 'Downlaods'.  Click on that and we're in business

> Do More #6 and #7 Find another directory with your file browser, then cd to it.
                    Remember when you put quotes around a directory with spaces in it? You can do that with any command. For example, if you have a directory I Have Fun, then you can do: cd "I Have Fun"

Let's find the artwork for iTunes.  `cd Music/iTunes/"Album Artwork"`


> Can you cd into the temp directory?

I'm already in the chapter_5 directory after using `mkdir temp` so to get into the temp directory I type `cd temp`

> Why don't we go into the temp directory?

Well, for that I would type `cd temp`

> Can you go to the slash temp directory?

This assumes I'm in the chapter_5 directory so that I only need to `cd temp` to get to the temp.  If I were in User/thoth/workspace and typed cd temp it tells me `bash: cd: temp: No such file or directory`


> Can you go to the slash temp slash log directory?

No.  I'm in the chapter_5 directory. There is a temp directory but no log directory so I can't go somewhere if it hasn't been created yet.  Were there a log directory I could type `cd temp/log`
