> Describe in your own words what pushd and popd do

`pushd` and `popd` are give you the ability to `cd` between directories that aren't adjacent very quickly.  The way I phrase it is that `pushd` allows you to PUSH into a certain directory just as `cd <dir>` would do.  Then you can immidiately POP out to where you were with `popd`
This is useful when you are 15 directories deep and you don't want to type `cd ../../../../../../....etc ad nauseum. to get back to where you were at.
Essentially you can go somewhere and then right back with pushd popd.

> What directories did you use in the "Do More" section

I created sub directories under "John" 1/2/3/4/5/6/7 to understand what was happening.  
For example from ../john/ I can `pushd 1/2/3/` and then pwd shows I'm in ../1/2/3  
Then `cd ..` brings me to 1/2/ but then I can `cd /3/4/5/` and `pwd` shows I'm in 5.  Now if I `popd` I go all the way back to ../john no matter where I was before.  It's like temporarily leaving a place that you can always return to with `popd`
