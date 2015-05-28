> Use quotes to find "new file" and "old file" and "This is".

`grep "new file" *.txt` will only find the lines with "new" and "file" next to each other

`grep "old file" *.txt` will only find the lines with "old" and "file" next to each other, I checked by adding a line to the oldfile.txt that just says "old old old" and it didn't show that line

`grep "This is" *.txt` will only find the lines with "This is" and the T must be capitalized or else it won't fine it unless you use -i


> Take the list of videos you created (or any other list) and use it to find some videos you want to find.

I want to find videos where Michael Bay blows something up, which would be anything Michale Bay has ever made.

So in the directory full of videos I run a  `grep Michael Bay *.txt` to find the videos with Michael Bay's name

> Unix: You can use -i to ignore case with grep. Try grep -i new *.txt

So I think the -i stands for insensitive meaning that it will look for capital and lower case letters as the grep command is case sensitive


> Show me the lines in foo.txt that have "ERROR" in them.

`grep ERROR foo.txt`


>Show me the lines in bar.txt that have "davinci" in them.

`grep davinci bar.txt`

>Can you print all the lines in text files that have your first and last name in them?


`grep "domenic weber" *.txt | pbcopy`

command+V = `newfile.txt:this says domenic weber`

I do have a question on this last one: I built my newfile.txt with domenic weber on one line but Weber on a different one.  How would I search for both domenic AND weber?
