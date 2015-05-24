> Do This!

cd temp

ls

cd stuff/thingsfrank/joe/alex/john/

cd ..

rmdir john

cd ..

rm dir alex

cd ..

ls

rmdir joe

cd ..

ls

rmdir frank

cd ..

ls

rmdir things

cd ..

ls

rmdir stuff

pwd




> Make 20 more directories and remove them all.

mkdir -p 1/2/3/4/5/6/7/8/9/10/11/12/13/14/15/16/17/18/19/20

cd 1/2/3/4/5/6/7/8/9/10/11/12/13/14/15/16/17/18/19/

rmdir 20

cd ..

rmdir 19

cd ..

rmdir 18

cd ..

rmdir 17

cd ..

rmdir 16

cd ..

rmdir 15

cd ..

rmdir 14

cd ..

rmdir 13

cd ..

rmdir 12

cd ..

rmdir 11

cd ..

rmdir 10

cd ..

rmdir 9

cd ..

rmdir 8

cd ..

rmdir 7

cd ..

rmdir 6

cd ..

rm dir 5

cd ..

rmdir 4

cd ..

rmdir 3

cd ..

rmdir 2

cd ..

rmdir 1



###How is this next step different than the prior?
> Make a single path of directories that is 10 deep and remove them one at a time just like I did above.

mkdir -p a/b/c/d/e/f/g/h/j/k

cd a/b/c/d/e/f/g/h/j/

rmdir k

cd ..

rmdir j

cd ..

rmdir h

cd ..

rmdir g

cd ..

rmdir f

cd ..

rmdir e

cd ..

rmdir d

cd ..

rmdir c

cd ..

rmdir b

cd ..

rmdir a


> Can you remove the tmp directory?

If I type `rmdir tmp` from the chapter_7 directory it will remove it

> Let's remove the tmp directory.

I just did that, so now I have to recreat it first using `mkdir tmp` Now I can type `rmdir tmp`
