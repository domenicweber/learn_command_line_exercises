> How big are is foo.txt?

Not sure what this has to do with the chapter but I used `ls -lh foo.txt` to see how many bytes the file is


> Can you output all the txt files in this directory?

To show all the txt files use `ls *.txt` meaning ANY file ending in .txt


####UPDATE

> Show me the content of the text files in slash temp.

We're looking for the actual stuff inside the txt files inside the /tmp directory so

I'm in the /chatper_16 directory and type `cat tmp/*.txt` and it will print me the contents of all the txt files
