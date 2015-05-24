cd temp

ls

cd stuff

ls

cd things

ls

cd frank

ls

cd joe

ls

cd alex

ls

cd john

ls

cd ..

ls

cd ../../../

ls

cd ../../

ls


> What does -iR do?

`ls` means you list the contents in a directory and the `i` parameter shows you some sort of numbered assignment to folder and file that has to do with the size b/c as I write this the number for the Readme.md file is growing.
Google tells me that -i "Lists file's inode index number" and if you look up inode it's essentially an address system for data blocks in Unix files.
If I just use `ls -i` it shows me only 2 numbers associated with the Readme.md and tmp directory inside Chapter_6.  
The `R` shows me everything recursively, meaning everything inside everything so that it lists all the subdirectories as far deep as they go.


> What's in the tmp directory?

In the chapter 6 directory I type  `ls tmp` and my computer says "stuff"


> Can you show me what files are in that directory?

I could alternately used `cd tmp` then `ls` go to the tmp directory and then look inside


> What files are in your home directory?

Now that just doesn't seem fair.  This implies I know where my "Home" directory is.  As I know it's in the root of the HDD I type `cd /` and now type `ls` This shows me the contents in the root and there is "home"  

I can `cd home` or I can `ls /home` both get the same result...showing me there is nothing in the folder

> What's in slash temp? 

From anywhere I can type `ls /tmp` and I get a ton of stuff.  Some very long hexadecimal looking number and other stuff and a log directory.  Note I did copy/paste this next portion as I wasn't gonna try to rewrite it!

F7C71944B49B446081C0603DE90E4855_IN

F7C71944B49B446081C0603DE90E4855_OUT

KSDownloadAction.HzfvNpE7mw

KSOutOfProcessFetcher.502.IW-ShwaXJwmHlkfc5wb2ZMHOaJY=

KSOutOfProcessFetcher.502.qQkpPp2uZLdVc5pukHmfJMR4bkM=

KSOutOfProcessFetcher.BuG4ZFcuLl

com.adobe.AdobeIPCBroker.ctrl-thoth

com.apple.launchd.DcPpb1qoGi

com.apple.launchd.V0gqTKKC89

log
