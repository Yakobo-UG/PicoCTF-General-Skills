Static ain't always noise
20 points
Tags: 

Author: syreal
Description

Can you look at the data in this binary: static? This BASH script might help!

Hints

(None)

Steps taken to find the flag

In this challenge we simply have to use to strings command which helps to view whether a certain document contains human readable characters

while in the terminal we use the strings static command and thus viewing the strings in the file, a problem comes in when there are many strings in the file which makes it hard to sort out the strings using the human eye, this issue is solved by using the simple command as seen below;

strings static | grep picoCTF , this command helps us sort through the very many strings in a file and thus clearly obating the flag we need

Note: the sorting is done by looking out for the word picoCTF in this case

Lessons learned:

1. Learned that you can use the strings command to find readable characters within a file
2. Learned that you can use the grep | command to sort out what you specifically want within a file

