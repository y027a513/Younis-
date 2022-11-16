# Read Me for measurement of the diameter of the ball in MATLAB 
This program is an attempt to measure the diameter of the ball using the creation of its own codes in MATLAB.  
## Status (active)
### [Unreleased]
## Creator: S. Younis Al balushi 
### Created: 2022.11.15
## Last Editor: S. AlBalushi 
### Last Edited: 2022.11.15

## Kind of input I will handle: 
# Basic Subplots that mean inserting many plots (grid) into a separate figure.  

## The names of user functions I will build and their general purposes: 
# Syntax function: in order to add more than one input in one function.  
# Function file: to make it easier when I import the data from MATLAB-to-MATLAB Editor. 
# Inline function: to make a single line function.  

## Kind of output I will return: 
# Three separate figures, 1st figure provides three different colors to one image, 2nd provides three different cleanup images, and 3rd provides a line showing the diameter of the ball.  

## Why this program is useful: 
# It is useful because it might save the efforts and time in the future for to calculate any diameter of any ball by just changing the location and name of the image/ ball to the target one.  

## Project Description: 
This program is based on three main aspects:
# the first aspect is that it changes the colors of the ball to three different colors
# The second aspect is an attempt to remove impurities from the background of the ball and the ball itself
# The third aspect is to measure the diameter of the ball through its function.

# I used the first two stages to reach the third stage, because the first stage changes the colors of the ball to darker colors to distinguish between the ball and the background. As for the second stage, it only removes all the impurities in order to give a clear and pure image of the ball and the background to make it easier for the third stage to calculate its diameter. In terms of the challenges I faced personally, I had trouble measuring the standard of the ball, but then I figured out its function. I also struggled in determining the function for removing simple and complex impurities in the ball image. In the future, I want to develop my programming skills in finding the diameter of the ball from many sides and not one side or position.  

## How to Use
Download the "'C:\Users\y027a513\OneDrive - University of Kansas\ball 3.jfif'" file and open it by imread function in MatLab. 

## Running The Program: 
# First, I exported the image of the ball to MATLAB and then I activated the imread and imshow functions. Then I used for the first stage (figure) the subplot function, imshow and title for each color of image. 
# For the second stage, I tried to calculate the standard/ level for figure 2, then I used im2bw function, subplot and imshow. After that, I repeated the method of this stage to three other stages, except for a different in their functions, imfill, imclearborder, and imopen.
# In the last stage, I tried to calculate the diameter by connecting it to the imopen function and then I used imdistline function.  

## Using The Project in The Future:  
# Subscribers could run and activate the program simply by clicking the Run button and then it will appear three separate figures showing three different stages.  

### Bugs and updates
#### [0.1.3] - 2022.11.12 
I tried to find figure(1)
#### [0.1.2] - 2022.11.13 
I tried to find figure(2) and (3)
#### [0.1.1] - 2022.11.13
I tried to calculate the diameter of figure(3)
#### [0.1.0] - 2022.11.15
I tried to start in ReadMe file, which writing general and specific information about this program. 


## License
S. ALbalushi, allow others to browse, publish, and print in the program “measurement of the diameter of the ball in MATLAB ” (which provides figures data) written by  S. ALbalushi.

signature of S. ALbalushi 15 Novamber 2022
S. ALbalushi, Owner

This program is free software: you can easily download the image on MATLAB and then proccess it. 

This program could be useful for many people especially students who want to explore more about the facts of calculating the diameter of any ball in MATLAB 

