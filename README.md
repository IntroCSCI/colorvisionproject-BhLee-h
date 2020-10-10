# Red Groups Color Vision Test

## Description

We are going to run a color blindness test using inputs of users decisions (else/if). 

// get the correct color values from the users and determine if its the correct color from the images provided. 
## Developer
-Brian Lee

## Example

To run the program, give the following commands:

```
g++ --std=c++11 main.cpp -o cvp
./cvp
```

Here is an example of the program running:

You will 1 point for each color correct
Picture 1: Please look at Picture 1
Do you see green? (y/n)
y
Do you see orange?
y
Picture 2: Please look at Picture 2
Do you see blue ? (y/n)
y
Do you see yellow ? 
y
Picture 3: Please look at Picture 3
Do you see blue ? (y/n)
y
Do you see red ?
y
Picture 4: Please look at Picture 4
Do you see green ? (y/n)
y
Do you see red ?
y
you got 8 points
Type n if you do not want to retake the test.

## C++ Guide

### Variables and Data Types

I used "string" to represent the colors of the images because I want it to act as an answer for the userinputs.

Also used "Char" to represent either "y" or "n" to allow the user to select whether or not they want to repeat the program. 
### Input and Output

The inputs and outputs have been used effectively to make sure that the userinputs are stored and can be shown as points for every one they get.

### Decisions
The code acts as a point system, everytime they get the correct color of the images, they get a point, and everytime they get it wrong.
 //(Couldn't figure out with my group on how to skip the question.)


### Iteration
I used a "while if" statement in order for the user to correctly be able to restart the whole test if possible.

### File Input and Output

We had a "ofstream" code in our project and it opens a file called "file.txt". It doesn't really do anything for our project but we included it in our color blindess anyways.
