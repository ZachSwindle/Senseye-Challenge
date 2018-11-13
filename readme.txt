#==============================================================================#
#                                                                              #
#                  Seneye Data Engineer Code Challenge                         #
#                                                                              #
#                                                                              #
#==============================================================================#



Overview

This challenge is designed to give us an idea of how you solve problems related 
to data processing and analysis. This challenge is designed to be short, taking 
no longer than 4 hours. This is a suggestion of course, and none of this will 
be timed. We know looking for a new position is time consuming and we want to 
respect that. What we would like to discover with this challenge should be
demonstratable within the alloted time.


Contents

Within the home folder, there are folders titled 'raw_data', 
'processed_data',  and the readme (the one you are reading now!). 
Contained within the raw_data folder are three files. These files are each an 
experimental output from a single experiment run on a single participant. 
These files are labeled with the participant number (participant_1, participant_2,
etc.). The goal of this challenge is to process those three files into a single 
dataframe, perform some brief analysis and export the combined frame. The project 
is also a part of a git repository, which you should use to version control 
your work and show your progression.




Directions

Here's the challenge!
    1. Create a Jupyter Notebook in this folder where you will showcase the work
    2. Deal with NAs, outliers, missing data, in any way you see fit (Removing data is fine)
    3. Explore the data and provide a very brief overview (have some analysis comparing the different participants)
    4. Export a single csv with any new coulmns you've added into the processed_data folder
    5. Along the way, track your progress with git commits!
    6. When you are finished, zip it up and beam it back to us!



Data Description

Each data file is the result of a single experiment on a single participant. 
The experiment consists of a series of questions with varying difficulty. 
All questions are defined by moving through three consecutive block types, 
BEGIN_SPAN, CUE_ANSWER, and RESPONSE always in that order, and not containing 
any other block types. The columns "correct" and "difficulty" 
represent information for each question. 

timestamp: time in seconds since the experiment has started
r_size:  pupil size in the right eye
r_conf: confidence of capturing pupil information from right eye
r_x_pos: x-coordinate location of right eye gaze
r_y_pos: y-coordinate location of right eye gaze
l_size:  pupil size in the left eye
l_conf: confidence of capturing pupil information from left eye
l_x_pos: x-coordinate location of left eye gaze
l_y_pos: y-coordinate location of left eye gaze

block_number: current block the participant is in, counts up as integer starting at 0.
block_type: the type of the block that the participant is in
correct: whether the participant answered correctly or did not 
difficulty: level of difficulty the participant was at (1 = low, , 2 = med, 3 = high)


Thats it! Feel free to contact us with any questions. 

