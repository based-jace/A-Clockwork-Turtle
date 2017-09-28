# A-Clockwork-Turtle
Made in 11 hours in Python's Turtle graphics.
The goal of the project was to make something (anything) using Turtle. Most people's go-to was to experiment a little with Python's random function creating semi-random geometric designs. I thought, "Hey. I want to re-create a still from A Clockwork Orange." So that's what I did. 

My first order of business was to open up VLC along with the movie, and then I took a screenshot of the clip I wanted to use. 

My first attempt was to sort of eyeball it, but that proved to be ugly and time-consuming (not that the final product wasn't time consuming in itself).

I opened up that screenshot in Photoshop, and then I realized that the coordinates 0,0 in Photoshop were in the top left of the screen, whereas 0,0 in Turtle was directly in the center. I then thought to myself, "How am I going to reconcile this?" Soon after I realized I could easily write a program that would essentially just convert the Photoshop coordinates where I had the mouse cursor placed into Turtle graphics coordinates. Throughout the night I worked on the picture, I also gradually improved upon the program to what it is now, being able not only to convert coordinates, but also automatically write the code for each individual geometric shape, making the entire process, although tedious and time consuming, exponentially more efficient. Here's a link to the repository containing that application: https://github.com/jacemedlin/PS-Turtle-Coordinator

The entire thing was meant to be a dark, tongue-in-cheek parody of an example project from one of my teacher's former students where it drew a little Rudolph the Red-Nosed Reindeer to his eponymous song. At the very end of the project, it asks "Would you like to light up Rudolph's Nose?" If you typed yes, of course his nose would light-up red. I wanted to do something much more elaborate.

In order for the program to work properly to it's full effect, you'll need a WAV of Gene Kelly's "Singin' in the Rain" (not uploaded because even the zipped file was too large for github's 25MB cap), and you need to name it SING.wav. Then put that file in the same folder as the .py file. After that, un-comment lines 9 and 2004.
