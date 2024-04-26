# Alex-Land-individual-project.
This GitHub file contains the finished code of my third year individual project.
This code allows the training and application of a neural net, capable of calculating how long to ball is 'in-play' in a football match.

USER GUIDE (for training) :
1) open the 'FINAL PROJECT CODE' and when prompted, select open in Colab.
2) connect, then run cell 1, which imports librarys.
3) run cell 2, which connects google drive, and sets colour ranges.
(blue colour detection is configured right now, you will need to edit the code to accomodate other colours)
4) run the next cell, click upload when prompted and select your video file for training.
5) when complete, run the following cell. An excel file will be produced on the left side of the screen.
6) open 'FINAL_CODE', change the upload link to path of your video being used to train.
7) run the code, it will open the football clip you are using to train the video. Whilst open, hold spacebar whenever the ball is in play.
8) An Excel file will be generated, copy the column titled 'space_pressed' then paste it into the excel file generated from step 5.
9) run the next cell on 'FINAL PROJECT CODE' this will train the network, then evaluate it.

to see how much in-play time there is on a new clip, repeat step 4. use the file it generates as the 'input_file_path' in the section lablled eith 'Submit the unseen data file into 'input_file_path' variable to generate the predictions.'
run the final cell and it will read how much added time is requried.
