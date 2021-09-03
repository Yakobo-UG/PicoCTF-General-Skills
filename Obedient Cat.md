Description: This file has a flag in plain sight (aka "in-the-clear").

Hint 1: Any hints about entering command into the Terminal(such as the next one), will start with a '$'... everything after the dollar sign will be typed(or copy and paste) into your terminal

Hint 2: To get the file accessible in your shell, enter the following in the Terminal prompt: $ wget https://mercury.picoctf.net/static/fb851c1858cc762bd4eed569013d7f00/flag

Hint 3: $ man cat

Points: 5


This challenge simply requires us to check the meta data of the file and this is easily archieved by using the linux  "cat" command and then placing the file we want to check infront of the command e.g cat Name of file

Steps to get the flag:

1. Download the file
2. While in terminal move to the directory where the file is located i.e using the cd command
3. Final step is to reveal the meta data of the file and this is done by using the cat command with the name of the file placed infront of it e.g cat flag, this will easily reveal the flag

NOTE: cat command does not work with image files