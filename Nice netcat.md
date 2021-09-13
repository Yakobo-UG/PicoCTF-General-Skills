Nice netcat...
15 points
Tags: 

Author: syreal
Description

There is a nice program that you can talk to by using this command in a shell: $ nc mercury.picoctf.net 22902, but it doesn't speak English...

Hints

1. You can practice using netcat with this picoGym problem: what's a netcat?
2. You can practice reading and writing ASCII with this picoGym problem: Let's Warm Up

Solution: 

In this challenge we are required to connect to an remote server using the nc command in
the linux terminal and the server we are supposed to connect to is mercury.picoctf.net 22902

step followed to get the flag
when we input nc mercury.picoctf.net 22902 in the terminal we are able to connect to that server

After inputing the command into the terminal we get multiple of numbers(decimal number) which we shall convert to ASCII to get the flag

![nc pic 1](https://user-images.githubusercontent.com/65670517/133158359-7c96d971-680d-4788-bc0f-b03ea35aba1b.PNG)

next step is finding away to convert the decimal values to ASCII in my case i googled "decimal to ASCII convert" and found a nice online convert which did the job perfectly as seen in the diagram below thus obating the flag

![pic 2](https://user-images.githubusercontent.com/65670517/133158578-38470548-0ec9-4090-a94d-ca47c2d09642.PNG)


Lessons learned:

1. learned that you can connect to a remote server using the nc command
2. lesrned that you can hide information in decimale values
