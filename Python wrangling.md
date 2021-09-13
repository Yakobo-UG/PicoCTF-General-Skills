Python Wrangling
10 points
Tags: 

Author: syreal
Description

Python scripts are invoked kind of like programs in the Terminal... Can you run this Python script using this password to get the flag?

Hints

1. Get the Python script accessible in your shell by entering the following command in the Terminal prompt: $ wget https://mercury.picoctf.net/static/1b247b1631eb377d9392bfa4871b2eb1/ende.py
2. $ man python

Solution:

we are required to run a python script using the passward to get the flag, this is simply down by using the:
cat pw.txt which will open up the file and reveal the passward

next is combining it with | python3 ende.py command in order to execute and run the the program with python using the passward

and finally also combining -d flag.txt.en to obtain the flag

the final command to be used is cat pw.txt | python3 ende.py -d flag.txt.en thus revealing the flag

![exc](https://user-images.githubusercontent.com/65670517/133158780-b66aecf5-f923-4424-8a75-61ff306ab8e5.PNG)


Lessons learned:

1. Learned that you can run python programs using python3
2. Learned that you can run a python progrmas using a file
