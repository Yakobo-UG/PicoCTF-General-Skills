Wave a flag
10 points
Tags: 

Author: syreal
Description

Can you invoke help flags for a tool or binary? This program has extraordinarily helpful information...

Hints

1. This program will only work in the webshell or another Linux computer.
2. To get the file accessible in your shell, enter the following in the Terminal prompt: $ wget https://mercury.picoctf.net/static/a00f554b16385d9970dae424f66ee1ab/warm
3. Run this program by entering the following in the Terminal prompt: $ ./warm, but you'll first have to make it executable with $ chmod +x warm
4. -h and --help are the most common arguments to give to programs to get more information from them!
5. Not every program implements help features like -h and --help.

Steps taken to find the flag:

The first is obviosly downloading the file

While in terminal we us the cd command to go into the directory where the file is download/saved, in my case its in the Downloads directory

next is that we use the ls -l command to check where the file is excecutable or not, and in this case the file is definalty not excecutable

To make the file excecutable we run a simple command chmod +x warm, to make the file excecutable, for confirmation use the ls -l command agina to determine wherther the file is now excecutable

Now that the file is excecutable we can run the file using the command ./warm, when we run the file it asks us to pass -h inoder to see what the file can do, without argue we do as required and we input the command ./warm -h, and thus obatining the flag

Lessons learned:

1. Learned how to make a file excecutable using the chmod +x command
2. learned how to run a file using the ./ command 